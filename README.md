
# TMDB Movie Review Sentiment Analysis using Simple RNN

This repository contains a project that performs sentiment analysis on customer reviews of movies using a Simple Recurrent Neural Network (RNN). The goal of the project is to classify movie reviews as positive or negative, providing insights into overall audience sentiment.

## Project Overview

The sentiment analysis model uses a Simple RNN to process and classify movie reviews based on their text. The dataset contains customer ratings and review text, which are preprocessed and tokenized before being fed into the RNN model for sentiment classification.

## 3. Approach 

### Load the Data
* Load the data of imdb from keras datasets

### Text Processing
- **Inspecting a review**:A sample embeded review is converted to the normal text to see how the review looks
- **Data Preprocessing**: Includes tokenization, padding, and word embedding.
>  **Padding**: A length of 500 is consdiered for padding

### Creating a simple RNN
- **RNN Model**: A Simple Recurrent Neural Network built to handle sequential text data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-sentiment-analysis.git
   cd movie-sentiment-analysis
