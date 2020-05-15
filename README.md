# Thai-Sentiment-Classification-Using-BERT

This repository contains python code to 
Finetune BERT for Thai sentiment classification with GPU on Google Colab using the pretrained model from https://github.com/ThAIKeras/bert which uses data from Thai Wikipedia.

## Data
Trained on open-source Wongnai restaurant review data. Source: https://github.com/wongnai/wongnai-corpus.git
  - Input: text review in Thai.
  - Target: rating in star from 1-5.
  
## Transfer Learning Using GPU
Main processes to fintune BERT in Thai using GPU on Google Colab include:
  - setting up Google Colab runtime with GPU acceleration.
  - installing all required libraries.
  - downloading all required files.
  - processing and verifying data.
  - tokenizing data using SentencePiece which implements BPE
  - finetuning BERT.
  - testing model's accuracy.
