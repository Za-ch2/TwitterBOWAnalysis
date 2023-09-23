# Twitter Sentiment Analysis

This project focuses on sentiment analysis using a dataset of tweets. The goal is to train a model that can classify tweets as either positive or negative based on their content.

## Project Overview

- **Dataset**: The dataset used in this project is a collection of tweets, each labeled as either positive (1) or negative (0).

- **Preprocessing**: The dataset was preprocessed by mapping sentiment label 4 to 1 (positive) and selecting only the relevant columns (target and text).

- **Model**: A Random Forest Classifier was chosen as the model for sentiment analysis.

- **Evaluation**: The model's performance was evaluated using accuracy as the evaluation metric.

## Code Structure

### Data Loading and Preprocessing

- The dataset was loaded from the 'twittertrainingset.csv' file and relevant columns were selected.

### Data Splitting

- The dataset was split into training and testing sets, with 80% used for training and 20% for testing.

### Text Vectorization

- The text data was vectorized using the CountVectorizer to convert the text into numerical features.

### Model Training

- A Random Forest Classifier was trained on the vectorized text data.

### Model Evaluation

- The model's accuracy was calculated on the testing dataset to assess its performance.

## Conclusion

The sentiment analysis model achieved a certain level of accuracy on the testing dataset, which indicates its ability to classify tweets as positive or negative based on their content.

