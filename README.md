# AIO_Module3_Sentiment_Analysis

This project involves analyzing sentiment (positive or negative) in the IMDB movie reviews dataset using Decision Tree and Random Forest classifiers. The steps followed in this project are outlined below.

## Steps

### 1. Load Dataset
- **File**: `IMDB-Dataset.csv`
- We load the IMDB dataset using pandas and remove any duplicate rows to ensure data integrity.

### 2. Data Cleaning
- The text data is cleaned by:
    - Removing HTLM tags
    - Expanding contractions
    - Removing punctuation, numbers, and emotions
    - Converting all words to lowercase
    - Lemmatizing words and removing stopwords

### 3. Data Analysis
- We visualize the distribution of sentiment labels (positive/negative) using a pie chart.
- Additionally, we analyze the distribution of the length of reviews for each sentiment class.

### 4. Train-Test split
- We split the dataset into training and testing sets, with 80% of the data for training and 20% for testing.

### 5. Text Vectorization
- We convert the text data into TF-IDF vectors with a maximum of 10,000 features.

### 6. Model Training and Evaluation
- **Decision Tree**: We train a Decision Tree classifier and evaluate its accuracy on the test set.
- **Random Forest**: Similarly, we train a Random Forest classifier and evaluate its accuracy.

## Conclusion
This project provides an overview of building, training, and evaluating machine learning models for sentiment analysis using the IMDB dataset. The models' performance can be improved by experimenting with advanced classifiers like boosting models.

This `README.md` provides a structured overview of each step, from data preprocessing to model training and evaluation, making the project easy to understand and follow.