# Personalized-cancer-diagnosis

Problem statement is taken from: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

Developed a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations

#nlp #classification #Machine learning #EDA


## SUMMARY:

### Problem Statement

* Classify the given genetic variations/mutations based on evidence from text-based clinical literature. Develope a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations.

### Use case:

* Classify genetic mutations based on clinical evidence. Interpreting clinical evidence is very challenging even for human specialists. If good model is developed to interpret clinical evidence and classify genetic mutations with high probability can be potentially useful in medical field.

### Bussiness Impact

* In this way the Model can replace/reduce the work of human specialists needed for Interpreting clinical evidence

### Data Cleaning

* Preprocessing of the text data is done

* Dataset is un-balanced (some classes are severely un-balanced)


### Algorithm Applied

* Top 3 Model Architecture deatils. 

* Balanced Logistic regression + One hot encoding + Unigram + Bigram + top 10000 + Dimentionality Reduction

* Knn on Tfidf

* Balanced Logistic regression + Tfidf top 1000 features
