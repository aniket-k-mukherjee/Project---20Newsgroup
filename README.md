# 20Newsgroup-Dataset-ML
In this project ,  the 20 newsgroup dataset has been classified using models like SVC, MultinomialNB, LinearSVC and I got an accuracy of 94,1%
This is the code for classifying 20 news group dataset using support vector machine and natural language processing.

# OVERVIEW:
Basically we create a data clean function using nltk which removes non-alpha words (like abc1234) or characters, punctuatons and popular names(like John, James using nltk.corpus.names). And then each word is lemmatized ({close, closely, closed, closer} => close ) using WordNetLemmatizer.

# Dependencies:
nltk
sklearn
numpy
# Usage:
Just run the given jupyter notebook in your browser.
