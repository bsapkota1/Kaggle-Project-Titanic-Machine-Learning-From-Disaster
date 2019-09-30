# Kaggle-Project-Titanic-Machine-Learning-From-Disaster

In this project we first import the training and testing data from the titanic data set. After importing the training and testing
data, the first thing we do is convert the categorical columns into numerical column. We start my dummy coding the sex column
for both training and testing data set. Next thing we do is use the k-means clustering for Fare column. Then we dummy code 
the fare clusters column. This has to be done because the clusters are assigned a number but those numbers don't necessarily 
correspond to the order of the fares. We do this for both training and testing dataset becuase we need to have same number of 
colums for both training and testing data set to predict values at the end. 
Finally we use random forest classifier with minimum sample leaf of 5 and 20. We see that with minimum sample leaf of 20 gives
us better accuracy and prediction so we use this model to predict the values at the end. 
