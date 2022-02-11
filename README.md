# vP0SWodi17JMHnTZ

## Binary Classification Project : Customer Happiness

# Project Overview:

This project is to build a model that predicts what makes our customers happy or unhappy.The answers for below questions are recorded 
1. X1 = my order was delivered on time 
2. X2 = contents of my order was as I expected 
3. X3 = I ordered everything I wanted to order 
4. X4 = I paid a good price for my order 
5. X5 = I am satisfied with my courier 
6. X6 = the app makes ordering easy for me 

The responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer. The goal of the model will be to predict if the customer will be happy(1) or unhappy(0).


# Exploratory Data analysis Findings:

Based on the exploratory data analysis done we have found below facts about the data set

i. The dataset is slightly unbalanced in terms of class data distribution.
ii. 54.76% records belong to class label 1, and 45.24% records belong to class label 0.
iii. All the features have outliers. 
iv. From entire dataset 19.841% records attribute to outliers.


# Machine Learning model used:

To search for the best machine learning model, I have relied on LazyClassifier. Based on the prelim analysis done via LazyClassifier SGDClassifier() model was found to be the best model. 

We trained the  SGDClassifier() classifier to achieve 76.32% accuracy and f1-score of 0.74 for class 0 and 0.78 for class 1 respectively. 

The code for the model can be found  in below notebook
notebook link :  https://github.com/jsJyo/customer_happiness/blob/main/BinaryClassificationProject.ipynb


# Conclusion:

Based on the coefficient values generated by model, we conclude 

i.) Feature X1(my order was delivered on time) is the most important factor in deciding if the customer will be happy with the service provided.
ii.) After feature X1, X5(I am satisfied with my courier) seems to be the most effective criteria in deciding the happiness of a customer.
iii.) Feature X6(the app makes ordering easy for me ), i.e the ease of ordering with app is a feature which tends to make customer unhappy.

