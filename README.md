![Hespress Logo](https://github.com/SohailaDiab/Hespress-Stories/assets/70928356/16eb8ce7-6c7f-4084-93b0-9b43e47e724a)

# Hespress-Stories
An Arabic NLP Project.

## Business Question
Given news from the Morrocan online news website, Hespress, what is the topic of that story?

## The process:
- EDA
- Label Encoding of the topics
- Removing stopwords, punctuation, numbers, and make english letters lowercase
- Stemming using the Arabic Stemmer "ISRIStemmer"
- Splitting and shuffling the data (Last 20% of each topic is kept for the test set)
- Feature extraction using TFIDF
- Training and testing using the models:
  - Support Vector Machine
  - Multinomial NB
  - Random Forest
  - SGDClassifier
  - Logistic Regression
- Comparing the models
