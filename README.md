# Bank-Data
1.	Using bank-full.csv data set fit the following models and identify the required metrics as shown below.Create the following data frame.
    Make sure you set random_state=100 while splitting data (train & test)and also while fitting the model.

	                             Decision Tree	Random Forest	AdaBoost	KNN
             True Positive				
             True Negative				
             False Positive				
             False Negative				
             Accuracy				
             Sensitivity				
             Specificity				

2.	Using IRIS data set we are going to use techniques used by KNN to predict the species, without using KNN inbuilt model.
    Follow the steps to get the prediction for the first test sample. (use random_state=100 while splitting data in to train & test)
     a.	Take first row in test data and identify Euclidean distance with all rows of training data (Use Euclidean distance function
     b.	Create a series with the distance values. Index value of the series should be same as the index value of the training data. 
        Sort the series in the ascending order of distance
     c.	Pick first 5 neighbors after sorting. For these neighbors, identify their target values. Take a polling and identify which species
        is having higher count. Your prediction will be that species with higher count.
3.	In Kaggle, you have to make submission for MNIST digit classifier competition using the best model among (Decision Tree, Random Forest,
    AdaBoost, KNN).
    a.	Split the train data in to train1 & validate
    b.	Build your model using train1 data. Calculate accuracy using validate data frame
