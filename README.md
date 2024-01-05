# | NLP | LLM | Fine-tuning | Trainer DeepSpeed |

## Natural Language Processing (NLP) and Large Language Models (LLM) with Fine-Tuning LLM and Trainer with DeepSpeed


![Learning](https://t3.ftcdn.net/jpg/06/14/01/52/360_F_614015247_EWZHvC6AAOsaIOepakhyJvMqUu5tpLfY.jpg)


# <b><span style='color:#78D118'>|</span> Overview</b>

In this notebook we're going to Fine-Tuning LLM:

<img src="https://github.com/YanSte/NLP-LLM-Fine-tuning-Trainer/blob/main/img_2.png?raw=true" alt="Learning" width="50%">

Many LLMs are general purpose models trained on a broad range of data and use cases. This enables them to perform well in a variety of applications, as shown in previous modules. It is not uncommon though to find situations where applying a general purpose model performs unacceptably for specific dataset or use case. This often does not mean that the general purpose model is unusable. Perhaps, with some new data and additional training the model could be improved, or fine-tuned, such that it produces acceptable results for the specific use case.

<img src="https://github.com/YanSte/NLP-LLM-Fine-tuning-Trainer/blob/main/img_1.png?raw=true" alt="Learning" width="50%">

Fine-tuning uses a pre-trained model as a base and continues to train it with a new, task targeted dataset. Conceptually, fine-tuning leverages that which has already been learned by a model and aims to focus its learnings further for a specific task.

It is important to recognize that fine-tuning is model training. The training process remains a resource intensive, and time consuming effort. Albeit fine-tuning training time is greatly shortened as a result of having started from a pre-trained model. 

<img src="https://github.com/YanSte/NLP-LLM-Fine-tuning-Trainer/blob/main/img_3.png?raw=true" alt="Learning" width="50%">

<img src="https://github.com/microsoft/DeepSpeed/raw/master/docs/assets/images/DeepSpeed_dark_transparent.svg#gh-dark-mode-only" alt="Learning" width="50%">


[DeepSpeed](https://github.com/microsoft/DeepSpeed)

## Learning Objectives

 By the end of this notebook, you will be able to:
1. Prepare a novel dataset
2. Fine-tune the `t5-small` model to classify movie reviews.
3. Using DeepSpeed
