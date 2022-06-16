# NLP
Here I share some of my NLP projects.
Currently these codes are from when I took CSCI 544 Applied Natural Language Processing in Fall 2021 at USC.
1. sentiment analysis1
In this project, I applied some machine learning algorithms (namely, perceptron, SVM, logistic regression, and multinomial naive bayes) to train a binary classifier on customers' sentiment using real-world data from the Amazon website. For word vectorization, I used TF-IDF.
2. sentiment analysis2
This project is the deeping learning version of the first, in which I applied Forward Neural Networks, RNN and GRU to train both binary (positive and negative) and ternary (positive, negative, and neutral) classifiers on customers' sentiment. For word vectorization, I tried both TF-IDF and word2vec.
3. POS tagging
For this project, I built an HMM model for part-of-speech (POS) tagging. I tried two decoding methods: greedy and viterbi.
4. NER
For this project, I applied deep learning algorithms to realize named entity recognation (NER) tasks. Specifically, I applied bidirectional LSTM and tried both one-hot vectors and pretrained GloVe word embeddings as word vectorizations.
