![image](https://github.com/SohailaDiab/Hespress-Stories/assets/70928356/fd5c897e-4326-4e45-929e-7cf8d5f10174)

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
  - Support Vector Machine performed the best with 85%
