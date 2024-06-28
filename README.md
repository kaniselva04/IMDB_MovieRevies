# IMDB_MovieRevies
# Movie Review Sentiment Analysis

## Project Description
This project involves performing binary sentiment classification on a dataset of movie reviews. The goal is to predict whether a given movie review is positive or negative using machine learning techniques.

## Dataset
The dataset consists of movie reviews and their corresponding sentiments (positive or negative). The dataset contains two columns:
- `review`: The text of the movie review.
- `sentiment`: The sentiment of the review (positive or negative).

## Preprocessing Steps
The text data is preprocessed using the following steps:
1. **Remove HTML tags**: Any HTML tags in the reviews are removed.
2. **Remove punctuation**: Punctuation marks are removed from the reviews.
3. **Convert text to lowercase**: All characters in the reviews are converted to lowercase.
4. **Remove stop words**: Common stop words that don't carry much meaning are removed.
5. **Lemmatization**: Words are reduced to their base form (e.g., "running" to "run").

## Model Training
The preprocessed text data is vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) and a Logistic Regression model is trained on the vectorized data.

## Evaluation
The model's performance is evaluated using accuracy and classification report metrics, including precision, recall, and F1-score.

## How to Run the Code
### Prerequisites
Ensure you have the following libraries installed:
- pandas
- numpy
- scikit-learn
- nltk

You can install these libraries using pip:
```bash
pip install pandas numpy scikit-learn nltk
