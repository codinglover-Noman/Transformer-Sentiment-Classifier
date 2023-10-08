# Transformer-Sentiment-Classifier

## Purpose
This project aims to fine-tune a BERT model for sentiment classification, categorizing given text as either POSITIVE or NEGATIVE sentiment.

## Datasets
This project uses datasets for sentiment analysis: https://www.kaggle.com/amitkumardas/sentiment-train

## Framework
PyTorch is the primary framework used for this project.

## Method of Fine-Tuning
The fine-tuning process involves several steps:
1. The pre-trained BERT model's architecture is frozen.
2. New layers are added to the BERT model to adapt it for sentiment classification.
3. Class weights are considered when defining the loss function to handle class imbalance in the dataset.
4. Data is stratified when splitting it into training, testing, and validation sets to address dataset imbalance.
5. BERT tokenizer is utilized to preprocess the text data before fine-tuning.

## Usage
Pandas, Numpy, Pytorch, Transformer, BERT



