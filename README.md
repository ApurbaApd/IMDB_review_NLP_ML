## Sentiment analysis of 50k IMDB Movie Reviews Using NLP and ML
### Objective:
This project focuses on sentiment analysis of IMDB movie reviews using natural language processing (NLP) and machine learning (ML) techniques. The goal is to classify movie reviews as either positive or negative based on the sentiment expressed in the text.

### Overview:
In this project, Various NLP techniques has been applied to preprocess the text data and extract meaningful features for sentiment analysis. Steps involved in the project include:

#### 1.Data Preprocessing:
Cleaning and standardization of the text data is done by removing HTML tags, punctuation, stopwords, and performed techniques like lemmatization and stemming to reduce variations of words and improve feature quality.

##### 2.Feature Representation: 
Utilized several techniques for numerical text representation, including TF-IDF (Term Frequency-Inverse Document Frequency), Bag-of-Words (BOW), and Word2Vec. These techniques help capture word importance and semantic similarities.

##### 3.Machine Learning Models:
Applied ensemble ML algorithms such as Random Forest, XGBoost, and Multinomial Naive Bayes on preprocessed features from TF-IDF, BOW, and Word2Vec to perform sentiment analysis.

### Results:
The best-performing model in this analysis was the Random Forest classifier, which achieved an accuracy of 83% on the IMDB movie reviews dataset. This indicates the effectiveness of the ensemble approach and the quality of the features extracted using NLP techniques.

