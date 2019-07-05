# Titanic-Kaggle-Problem


#### Data Exploration/Analysis

1) The Data set has 1309 examples and 13 features + the target variable (survived).
2) Need to convert a lot of features into numeric.
3) Features have widely different ranges, that we will need to convert into roughly the same scale.
4) Spot some more features, that contain missing values (NaN = not a number), that we need to deal with.
5) Split the data into training and test set in which 80% data training set and 20% data test set ratio.

<hr>

#### Data Preprocessing

1) Missing Train Data.
2) We have to deal with Cabin(496), Body(496),Boat(495),Home.dest(273).
3) A cabin number looks like ‘C452’ and the letter refers to the deck and missing values will be converted to zero.
4) Missing value of age is replace by its median.

#### Converting Features

1) ‘Fare’ is a float and we have to deal with 4 categorical features: Name, Sex, Ticket and Embarked.
2) Name feature to extract the Titles from the Name, so that we can build a new feature out of that.
3) Convert ‘Sex’ feature into numeric.
4) Drop the Ticket feature it will be a bit tricky to convert them into useful categories.
5) Convert ‘Embarked’ feature into numeric.
6) The ‘Fare’ feature first we will convert it from float into integer.
 <hr>

#### Machine Learning models used

1) Random Forest.
2) Logistic Regression.
3) K Nearest Neighbor.
4) Linear Support Vector Machine Decision Tree.
5) Machine Learning Models.

<hr>
      
#### Summary
 
1) The data exploration where we got a feeling for the dataset, checked about missing data and learned which features are important.
2) Seaborn and matplotlib to do the visualizations.
3) Data preprocessing part, we computed missing values, converted features into numeric ones, grouped values into categories 
and created a few new features.
4) different machine learning models, applied cross validation on it.
5) Lastly, we looked at it’s confusion matrix and computed the models precision, recall and f1-score.
