
# IMDB Movie Review Sentiment Analysis using Simple RNN

This repository contains a project that performs sentiment analysis on customer reviews of movies using a Simple Recurrent Neural Network (RNN). The goal of the project is to classify movie reviews as positive or negative, providing insights into overall audience sentiment.

## Project Overview

The sentiment analysis model leverages a Simple RNN to process and classify movie reviews based on textual data. The dataset, sourced from the IMDb movie review corpus, includes both customer ratings and review text. These reviews are preprocessed and tokenized before being fed into the RNN for sentiment classification

## Approach to the problem

### Load the Data
* The IMDb dataset is loaded from the Keras library's built-in datasets

### Text Processing
- * **Review Inspection**:A sample embeded review is converted to the normal text to see the structure of the review
- * **Data Preprocessing**:
- > * **Padding**: Sequences are padded to a consistent length of 500 words, ensuring uniform input for the RNN.
- > * **Embedding**:Transformed into dense vectors to capture the semantic relationship

### Creating a simple RNN
- * **RNN Model**: A Simple Recurrent Neural Network built to handle sequential text data.

### Evaluation Metrics
* Model accuracy, loss, and confusion matrix are used to evaluate the model’s performance.

  
## Conclusions
This project demonstrates the use of  Recurrent neural network (ANN)  to do sentiment analysi of the movie reviews. While the model shows good predictive ability(80%), future enhancements could involve incorporating advanced architectures such as Long Short-Term Memory (LSTM) or Gated Recurrent Units (GRU). Additionally, integrating more features from the customer data could further improve the model’s performance.
