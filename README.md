# NLP
This is a sentiment analysis project which I did when I took CSCI 544 Applied Natural Language Processing in Fall 2021 at USC. It consists of the following two stages:

1. sentiment analysis1

For this stage, I applied some machine learning algorithms (namely, perceptron, SVM, logistic regression, and multinomial naive bayes) to train a binary classifier on customers' sentiment using real-world data from the Amazon website. For word vectorization, I used TF-IDF.

2. sentiment analysis2

For this stage, I implemented deep learning techniques. Specifically, I applied Forward Neural Networks, RNN and GRU to train both binary (positive and negative) and ternary (positive, negative, and neutral) classifiers on customers' sentiment. For word vectorization, I tried both TF-IDF and word2vec.

The testing results on the multiple models are as follows:

Perceptron with TF-IDF features:

Accuracy: 84.8%
Precision: 87.0%
Recall: 81.8%
F1-score: 84.3%

SVM with TF-IDF features:

Accuracy: 89.2%
Precision: 89.0%
Recall: 89.4%
F1-score: 89.2%
