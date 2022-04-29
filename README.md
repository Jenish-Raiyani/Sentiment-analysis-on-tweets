# Sentiment-analysis-on-tweets

# Project Description:
# 1.	Definition:
The project is about identifying and classifying whether the tweet is Positive or Negative using sentiment analysis.  <br />
Data set link:	https://www.kaggle.com/datasets/kazanova/sentiment140
# 2.	Dataset details: 
The sentiment140 dataset was used in this project which was collected from Kaggle. It is a text dataset with 1,600,000 tweets that are categorized as negative or positive. The dataset contains 800000 positive tweets and 800000 negative tweets. The data is managed into six fields:
- Polarity
- Tweet ID
- Date
- Query 
- Username 
- Tweet Content<br />
In practice, 10000 tweets are chosen at random for testing.
# 3.	Feature taken:
Text data from tweets is considered a feature and Bag-of-Words techniques are used to convert text data into features.   
# 4.	Hyper parameter tuning:
To choose optimal parameter for machine learning model I have applied hyperparameter tuning technique. In this process I have used GridSearchCV sklearn library. This library allows you to iterate through specified hyperparameters and fit our model to training data and from result we can choose the best hyperparameters for our model. 
# 5.	Algorithms used:
Four classification algorithms are used in this project. Random forest, SVM, nave bayes, and logistic regression The accuracy of logistic is 0.75, naive Bayes is 73, SVM is 0.75, and random forest is 0.73.

 
- Logistic Regression: <br />
Using hyper parameter technique I have chosen best parameter for the logistic regression. GridSearchCV find (C =2, max_iter = 100, solver= 'saga') hyperparameters for logistic regression. The accuracy of this model is 0.75.

- Bernoulli Naïve Bayes:  <br />
Optimal parameters for Bernoulli Naïve Bayes is 'alpha': 1.0 and accuracy of naive bayes model is 0.73.   

- Support Vector Machine:<br />
Best optimal parameters for SVM are {'C': 1, 'kernel': 'linear', 'gamma': 0.1} and 0.75 is accuracy of SVM model. 
- Random Forest:<br />
{'criterion': 'gini',
 'max_depth': 8,
 'max_features': 'auto',
 'n_estimators': 500} : this are the optimal parameters of Random Forest and accuracy of this model is 0.73.
 

![image](https://user-images.githubusercontent.com/66068702/165537573-0473a528-76c4-440b-bdba-8e0011111a36.png)
