#  Ecommerce product categorization
![image](https://github.com/pranavvb03/ecommerce-product-categorization/assets/139568635/bf662489-fc10-4179-8102-8abf2093d01a)
# Introduction
Product categorization is the task of classifying products as belonging to one or more categories from a given taxonomy.It helps customers navigate an ecommerce store with ease. It deals with organizing our ecommerce products into categories and tags that give us a system to get customers to the exact product they are looking for quicker. This includes creating categories, tags, attributes and more to create a hierarchy for similar products. It is a field of study within natural language processing (NLP).

# Data 
This project deals with  a huge E-commerce text dataset for 4 categories - 
"Electronics", 
"Household", 
"Books" and 
"Clothing & Accessories".

# Procedure
Basic NLP steps for categorizing the E-commerce dataset include:-
1. Data preprocessing
2. Data Visualisation ( exploratory data analysis )
3. Text Preprocessing such as tokenization,stemming,lemmatization,stopword removal,POS tagging
4. Model Building using ML Classifiers such as Multinomial Bayesian Classifier,SVM,Decison Tree,Random forest,Logistic regression.
5. Testing
6. Prediction 

# Results
We use TF-IDF vectorizer on the normalized product descriptions for text vectorization on Multinomial Bayes Classifier , and perform hyperparameter tuning . The tuned model obtains a validation accuracy of 0.9203.
We employ the tuned model with the highest validation accuracy(Support Vector Machine) to predict the labels of the test observations and obtained a test accuracy of 0.96. We present the confusion matrix depicting the test set performance of the model.
