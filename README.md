# Quora-Insincere-Questions-Classification
Kaggle Competition - Quora Insincere Questions Classification

Kaggle page: https://www.kaggle.com/c/quora-insincere-questions-classification


### What we have not tried
* Attempts to handle class imblance such as upsampling, downspampling
* Ensemble
* Embedding concatenation
* Acronym dictionaries
* Truncating questions
* RNN (vanila)
* GRU
* Attention
* k-NN
* SVM
* Logistic regression

### What we tried but did not work
* Naive Bayes (see very_simple_classifiers.ipynb): f1-score = 0.2177
* Decision Tree (see very_simple_classifiers.ipynb): f1-score = 0.1570

### What we tried and work
* Cross validation
* Embedding averaging
* Tokenizer: Keras
* Tokenizer: spaCy
* Tokenizer: NLTK
* Tokenizer: split (python built-in function)
* Spelling correction
* LSTM
* CNN
* MLP
