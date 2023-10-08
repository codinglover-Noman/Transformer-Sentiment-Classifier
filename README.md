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
[Provide instructions on how to use your code, train the model, and make predictions.]

## Installation
[Include any installation instructions or requirements for using your project.]

## License
[Specify the license under which your project is distributed, if applicable.]

## Acknowledgments
[Give credit to any external libraries, tools, or resources you used or were inspired by.]

## Contributing
[Include guidelines for others who may want to contribute to your project.]

## Issues
[Provide a link to the GitHub Issues page for your project, where users can report problems or suggest enhancements.]

## Contact
[Include your contact information for questions or inquiries related to the project.]

