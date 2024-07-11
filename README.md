# Sentiment Analysis on Movie Reviews

This project uses machine learning to perform sentiment analysis on movie reviews, classifying them as positive or negative based on their text content.

## Dataset

We use the IMDb movie reviews dataset, which contains 50,000 reviews labeled as positive or negative.

## Steps

1. **Loading the Dataset**: We load the IMDb movie reviews dataset from a CSV file.
2. **Preprocessing the Data**: We clean the text data by removing stopwords and applying stemming.
3. **Preparing the Data**: We split the data into training and testing sets and vectorize the text data.
4. **Training the Model**: We use a Logistic Regression model.
5. **Making Predictions**: We predict the sentiment of the reviews in the test set.
6. **Evaluating the Model**: We evaluate the model's performance using accuracy, confusion matrix, and classification report.

## Installation

To run this project, you need Python installed along with the following libraries:
- pandas
- scikit-learn
- matplotlib
- seaborn
- nltk

You can install these libraries using pip:

```sh
pip install pandas scikit-learn matplotlib seaborn nltk
