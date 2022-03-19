# naive_bayes

Implementation of Naive Bayes from scratch in python.

I have implemented multinomial naive bayes classifier to predict whether a movie review is positive or negative. In this project I used a large collection of positive and negative sentiment reviews in the polarity dataset to train the classification model.

In bayes.py you will find the class NaiveBayes621:
- This object behaves like a sklearn model with fit(X,y) and predict(X) functions. Limited to two classes, 0 and 1 in the y target.

test_bayes.py is a script designed by my professor Dr.Parr to test my implementation against Scikit-learn's.
