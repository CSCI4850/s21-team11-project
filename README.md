# s21-team11-project
# ESBN Team

# Convolution Nerual Network with Trained Word2Vec Embeddings for Part-Of-Speech Tagging of English or Latin

The aim of this project is to create a part-of-speech (POS) tagger for either English or a classical Language, in this case, Latin. The taggers were both developed using a Convolutional Neural Network (CNN) with an Embedding layer of trained word embeddings, dropout layers to prevent the common issue of overfitting, dense layers with relu, and a dense layer with softmax at the output layer, implemented with Keras Tensorflow. The English model was trained on the Natural Language Toolkit's (nltk) Brown, Treebank, and Conll200 corpora with an embedding matrix of Word2Vec's pretrained Google News corpus. The Latin model was trained on Universal Dependencies LLCT, ITTB, and PROIEL treebanks with Word2Vec's pretrained Continuous Skipgram of the Latin CoNLL17 corpus. 

Input sentences to both models were padded with zeros for the required uniformity in input sizes. This inflates the rate of accuracy, therefore we use an existing masked accuracy function to get a better gauge of the models' accuracies. The English model reached an accuracy of 98.57% and a masked accuracy of 96.54%. The Latin model reached an accuracy of 98.01% and a masked accuracy of 93.62%.

# Demo

The files needed for our demonstration can be found at:
https://www.dropbox.com/sh/zmxmm7t0xyrpny6/AABVUJjT1ZclwC5pgXE5rc7_a?dl=0
