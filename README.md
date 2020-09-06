# Personalized-cancer-diagnosis

Problem statement is taken from: https://www.kaggle.com/c/msk-redefining-cancer-treatment/

Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

Developed a Machine Learning algorithm that, using this knowledge base as a baseline, automatically classifies genetic variations

#nlp #classification #Machine learning #EDA


SUMMARY:

    As there are 15 different model is tried, among those lowest log_loss is for [ Logistic Regression + Unigram and Bigram With max_features =10000 + Dimentionality reduction techique (Singular value Decomposotion) method ]

    The Worst model is Random forest with Response encoding, which overfits on train data by huge margin gave 44% misclassification error

    The Knn performs well with lowest of 32% misclassification error

    Balanced Dataset performs well as compared to imbalanced dataset

    Tfidf Techniues performs well as compared to One hot encoding techniques in almost all the model

    Word2vec is not tried, since the pretrained glove vector uses wikipedia/news data. But, the problem at hand is medical domain. may be most of the words vector represenation will not be avaliable there (hence w2v and Avg W2v is not tried)
