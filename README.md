# Fake News Prediction Notebook Summary

## Dependencies
- Libraries for data handling, text processing, and machine learning are imported (NumPy, pandas, NLTK, Scikit-learn).

## NLTK Resources
- Downloads stopwords from NLTK, essential for text preprocessing.

## Data Pre-processing
- Loads the dataset into a pandas DataFrame.
- Checks and handles missing values by replacing them with an empty string.
- Combines author names and news titles into a single column for more comprehensive text data.

## Text Preprocessing
- Text is cleaned to remove special characters and make all words lowercase.
- Textual data is stemmed to reduce words to their root form.
- Stopwords are removed to focus on more meaningful words.
- Text is vectorized using TF-IDF to convert text data into a format suitable for machine learning.

## Model Training
- Data is split into training and testing sets.
- A logistic regression model is trained on the dataset.

## Evaluation
- Model performance is evaluated using accuracy score metrics.
