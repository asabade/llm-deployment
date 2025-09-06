
# Optimizing LLMs with Fine-Tuning and Prompt Engineering


This repository contains code for the Optimizing LLMs with Fine-Tuning and Prompt Engineering


### Notebooks

#### Comparing Fine-tuned OpenAI + BERT

  - [`bert_app_review.ipynb`](notebooks/bert_app_review.ipynb): Fine-tuning a BERT model for app review classification.
  - [`openai_app_review_fine_tuning.ipynb`](notebooks/openai_app_review_fine_tuning.ipynb): Fine-tuning OpenAI models for app review classification.

#### Fine-tuning embeddings

- [Fine-tuning Embeddings For Rec Engines](https://colab.research.google.com/drive/1JfxyxdGCDjYeO52Bk1JzW4Af94xndTws?usp=sharing): Fine-tuning embedding engines using custom preference data

- [Fine-tuning Embeddings  with Synthetic Data](https://colab.research.google.com/drive/1FOr9hgMEcTa8UJJSuKjoHpohVb-Qz-FJ?usp=sharing) - Using GPT-4o to create synthetic queries for a corpus to increase the quality of open-source embedding models

#### Working with FLAN-T5 models using Reinforcement Learning
  - Colab Version: [![Using SAWYER](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wG8lv6drn872HNZHrT7V9kl6JIF1SXpr?usp=sharing)

#### SAWYER - Training a chat model with RLF

  - [`SAWYER_LLAMA_SFT.ipynb`](notebooks/SAWYER_LLAMA_SFT.ipynb): Fine-tuning the Llama-3 model to create the SAWYER bot.
    - [colab version](https://colab.research.google.com/drive/1gN7jsUFQTPAj5uFrq06HcSLQSZzT7hZz?usp=sharing) 
  - [`SAWYER_Reward_Model.ipynb`](notebooks/SAWYER_Reward_Model.ipynb): Training a reward model from human preferences for the SAWYER bot.
    - [colab version](https://colab.research.google.com/drive/1bVjTzOjXCOM8J6tzgt3LK-D0K-yGWzyI?usp=sharing) 
  - [`SAWYER_RLF.ipynb`](notebooks/SAWYER_RLF.ipynb): Applying Reinforcement Learning from Human Feedback (RLHF) to align the SAWYER bot.
    - [colab version](https://colab.research.google.com/drive/1QR_Xf1GsOyChYzReg_JHxsBTrMZ0Vwz6?usp=sharing) 
  - [`SAWYER_USE_SAWYER.ipynb`](notebooks/SAWYER_USE_SAWYER.ipynb): Using the SAWYER bot.
    - [colab version](https://colab.research.google.com/drive/1xUrIbqyKoEjxNyjNI6iuYuSNMyksypEO?usp=sharing)
  - [Adapting SAWYER to know more about ML](https://colab.research.google.com/drive/12JeS96SVLIyY06bzJs96B5PdTt1Pga06?usp=sharing)

#### Distillation + Quantization

  - [`distillation_example_1.ipynb`](notebooks/distillation_example_1.ipynb): Exploring knowledge distillation techniques for transformer models.
  - [`distillation_example_2.ipynb`](notebooks/distillation_example_2.ipynb): Advanced distillation methods and applications.
  - [`llama_quantization.ipynb`](notebooks/llama_quantization.ipynb): Quantizing Llama models for efficient deployment.
  - [`Llama.cpp`](https://colab.research.google.com/drive/1D6k-BeuF8YRTR8BGi2YYJrSOAZ6cYX8Y?usp=sharing) - Using LLMs with llama.cpp
