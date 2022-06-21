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

Multinomial Naive Bayes with TF-IDF features:

Accuracy: 87.2%
Precision: 88.0%
Recall: 86.0%
F1-score: 87.0%

Perceptron with pretrained word2vec features:

Accuracy: 77.4%
Precision: 84.6%
Recall: 66.7%
F1-score: 74.6%

SVM with pretrained word2vec features:

Accuracy: 81.5%
Precision: 82.8%
Recall: 79.4%
F1-score: 81.1%

Perceptron with self-trained word2vec features:

Accuracy: 81.8%
Precision: 82.9%
Recall: 80.1%
F1-score: 81.5%

SVM with self-trained word2vec features:

Accuracy: 86.2%
Precision: 86.6%
Recall: 85.6%
F1-score: 86.1%

Feed-Forward Neural Networks (FNN) with the average self-trained word2vec vectors, 50 epochs:

Accuracy: 86.6%
Precision: 87.0%
Recall: 85.9%
F1-score: 86.5%

FFN with the concatenation of the first 10 word2vec vectors, 50 epochs:

Accuracy: 79.9%
Precision: 80.3%
Recall: 79.1%
F1-score: 79.7%

Recurrent Neural Networks (RNN) with each sequence truncated to a length of 20, 50 epochs:


Accuracy: 83.0%
Precision: 82.8%
Recall: 83.3%
F1-score: 83.0%

Gated Recurrent Units (GRU) with each sequence truncated to a length of 20, 50 epochs*:

Accuracy: 81.5%
Precision: 81.7%
Recall: 81.2%
F1-score: 81.4%

*GRU was not fully trained when the training terminated.




