# Sentiment-analysis-on-tweets

Project Description:
1.	Definition:
The project is about identifying and classifying whether the tweet is Positive or Negative using sentiment analysis.
Data set link:	https://www.kaggle.com/datasets/kazanova/sentiment140
2.	Data set details: 
The sentiment140 dataset was used in this project which was collected from Kaggle. It is a text dataset with 1,600,000 tweets that are categorized as negative or positive. The dataset contains 800000 positive tweets and 800000 negative tweets. The data is managed into six fields: polarity, tweet ID, date, query username, and tweet content. In practice, 10000 tweets are chosen at random for testing.
3.	Feature taken:
Text data from tweets is considered a feature and Bag-of-Words techniques are used to convert text data into features.   
4.	Hyper parameter tuning used:
To choose optimal parameter for machine learning model I have applied hyperparameter tuning technique. In this process I have used GridSearchCV sklearn library. This library allows you to iterate through specified hyperparameters and fit our model to training data and from result we can choose the best hyperparameters for our model. 
5.	Algorithms used:
Four classification algorithms are used in this project. Random forest, SVM, nave bayes, and logistic regression The accuracy of logistic is 0.75, naive Bayes is 73, SVM is 0.75, and random forest is 0.73.
 
![image](https://user-images.githubusercontent.com/66068702/165534871-a6116268-9197-4c0b-aafd-56305a6035c1.png)
