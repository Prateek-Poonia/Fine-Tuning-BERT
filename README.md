Fine-Tuning BERT on AG News Dataset

This project demonstrates how to fine-tune a pre-trained BERT model (bert-base-uncased) on the AG News dataset using TensorFlow and the Hugging Face Transformers library. The goal is to build a multi-class text classification model capable of classifying news articles into one of four categories: World, Sports, Business, and Science/Technology.

 Project Overview
Task: Multi-class text classification
Model: BERT (bert-base-uncased)
Framework: TensorFlow with Hugging Face Transformers
Dataset: AG News (from Hugging Face Datasets)
Objective: Predict the category of news articles based on their headline and description
Metric Used: Accuracy

 Model Information
Pretrained Model: bert-base-uncased from Hugging Face Model Hub
Tokenizer: BertTokenizer to tokenize text inputs
Architecture: TFBertForSequenceClassification with num_labels=4
Why BERT: BERT’s deep bidirectional transformer architecture makes it effective for capturing contextual relationships in text classification tasks.
