

## About

This project delves into the realm of Natural Language Processing (NLP) to understand and interpret human sentiments expressed on social media platforms, particularly Twitter. By analyzing tweets, we aim to gauge the emotional tone behind the text, thereby exploring the power of NLP in sentiment analysis.

## Dataset

The project utilizes the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140?resource=download)
## Key Steps
*1. Data Acquisition:** Downloading the Twitter sentiment140 dataset from [Kaggle]

2. Data Cleaning :** 
- Handling missing values and duplicates.
- Removing irrelevant information (e.g., URLs, dates, usernames).
- Converting text to lowercase for consistency.

3. Text Preprocessing :** 
- Tokenizing text into words.
- Removing stopwords (common words with little meaning)
- Applying stemming to reduce words to their root forms. (example : actor, actress, acting = act)

**4. Feature Extraction :** Converting text into numerical vectors using  [TF-IDF]
5. Model Training :** Building a Logistic Regression classifier to learn sentiment patterns to classify tweets as positive or negative.

6. Model Evaluation :**  Measuring model accuracy using appropriate metrics.

7. Model Deployment :** Saving the model for future use and potential deployment in a web application or API.



