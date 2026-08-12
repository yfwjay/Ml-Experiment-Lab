# DATASET UNDERSTANDING

## OBJECTIVE
 To understand what our dataset entails from the columns and their meaning and what we are trying to solve


## STEP 1

### OVERVIEW
The dataset , titanic has been split into 2 groups : training set (train.csv) and testing set (test.csv).

The **training set** SHOULD be used to build our machine learning model. It has the outcome or the ground truth for each passenger.
Model based on features and can use feature engineering to create new features.

The **test set** SHOULD be used to see how your model performs on unseen data.

The test set has no ground truth for each passenger.

For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

## STEP 2

### COLUMNS

#### Features

1. PassengerId = **Numerical Column**.Autoincriment to the number of rows present.
2. pclass =  **Categorical column** for the ticket class. Keys:
```
1 = 1st
2 = 2nd
3 = 3rd
```
3. Name = **Unique Column**. The names of passengers in the titanic.
4. Sex = **Categorical Column**. Either Male or Female
5. Age = **Numerical Column**. This are age in years
6. SibSp = **Numerical Column** . The number of siblings or spouses abroad the titanic.
7. parch = **Numerical Column** The number of parents or children aboard in the titanic.
8. ticket = ** String Column** The ticket number of the passenger.
9. fare = **Numerical Column** The Passengers fare.
10. cabin = **String Column** The Cabin number.
11. embarked = **Categorical Column** The Port of Embarkation. 
```
C = Cherbourg 
Q = Queenstown 
S = Southampton
```

### Target
1. Survival = Whether Passenger survived the titanic.
```
0 = No
1 = Yes
```

**After Step 2. Validate the following**
```
1. Type of column
2. Is the column unique or not
3. The features (X) and the target variable (Y).
```