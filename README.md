# Sentiment Analysis on IMDB Dataset with PyTorch and Positional Encoding

There are 50,000 movie reviews in the IMDB dataset, with 25,000 used for testing and the remaining 25,000 for training. Positive or negative sentiment is assigned to each review. 

## Implementation Overview:
Using PyTorch, this project applies sentiment analysis to the IMDB dataset, utilizing positional encoding to efficiently capture sequential information.


## Implementation Steps:

1. **Creating Vocabulary**: Get the IMDB dataset and tokenize it. Utilizing the tokenized sequences, create a vocabulary.

2. **Text Data Processing**: Define functions to process text and label data, truncate sequences, and collate batch data.

3. **Positional Encoding**: To add positional encodings to input sequences, implement a learnable positional encoding module.

4. **Model Architecture**: Define the model architecture using an embedding layer, LSTM layer, linear layer for classification, and the positional encoding module.

5. **Training**: Implement the training function to train the model using the training dataset.

6. **Evaluation**: Define the evaluation function to evaluate the trained model on the testing dataset.


## Author:
`AnkitaMungalpara
