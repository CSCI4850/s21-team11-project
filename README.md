# s21-team11-project
# ESBN Team

# Convolution Neural Network with Trained Word2Vec Embeddings for Part-Of-Speech Tagging of English or Latin

The aim of this project is to create a part-of-speech (POS) tagger for English and Latin. The taggers were developed using a Convolutional Neural Network (CNN) with an Embedding layer of trained word embeddings, dropout layers to prevent overfitting, dense layers with relu, and a dense layer with softmax at the output layer, implemented with Keras Tensorflow. The English model was trained on the Natural Language Toolkit's (nltk) Brown, Treebank, and Conll200 corpora with an embedding matrix of Word2Vec's pretrained Google News corpus. The Latin model was trained on Universal Dependencies LLCT, ITTB, and PROIEL treebanks with Word2Vec's pretrained Continuous Skipgram of the Latin CoNLL17 corpus. 

Input sentences to both models were padded with zeros for the required uniformity in input sizes. This inflates the rate of accuracy, therefore we use an existing masked accuracy function for a more precise evaluation. The English model reached an accuracy of 98.57% and a masked accuracy of 96.54%. The Latin model reached an accuracy of 98.01% and a masked accuracy of 93.62%.

# Demo

1) Download the file Demo.jpynb and open it using Jupyter
2) Follow the directions in Demo.jpynb

# Jupyter Help

Both JupyterLab and Jupyter Notebook can be installed here: https://jupyter.org/

For a quick introduction to Jupyter, check out this step-by-step tutorial here: 
https://realpython.com/jupyter-notebook-introduction/

For more detailed help with JupyterLab or Jupyter Notebook, check out the documentation here: https://jupyter.org/documentation
