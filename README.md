# Transformer-Sentiment-Classifier
Purpose for this project:
Fine tuning BERT to classify sentiment of given text into POSITIVE or NEGATIVE.
Datasest used for this project:
Framework used: Pytorch 
Method of fine-tuning:

    Froze the pre-trained BERT model's architecture.
    Added new layers to the BERT model
    Considered the class weights while deifing the loss function, stratified data while splitting into train, test and validation to handle the imbalance in the dataset.
    Used BERT tokenizer to process texts before fine-tuning.
