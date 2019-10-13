# 100 Days Of Code - Log

### Day 1: October 6, Sunday

**Today's Progress**: Completed micro-course of Intro to Machine Learning on Kaggle.

- Built basic decision tree model in python, for housing price prediction
- Evaluated best fit tree size for the model
- Built random forest model on the same data set

**Thoughts** First interaction with anything on kaggle. Developed an appreciation for the platform.

**Link(s) to work**
[Into to Machine Learning - Kaggle](https://github.com/nikunjbhalla/kaggle-courses/tree/master/1.%20Intro%20to%20Machine%20Learning)


### Day 2: October 7, Monday

**Today's Progress**: Worked on handling missing values in the data in first exercise of micro-course of Intermediate Machine Learning on Kaggle. Small tricks but huge learning.

**Thoughts** Improved rank in housing price challenge by 3,998 places, but that is nothing compared to learning. Looking forward to learn more, would be great to know thought process of others who worked on this problem without these courses.

**Link(s) to work**
[Handled missing values in data set](https://github.com/nikunjbhalla/kaggle-courses/blob/master/2.%20Intermediate%20Machine%20Learning/Missing%20Values.ipynb)


### Day 3: October 8, Tuesday

**Today's Progress**: Learnt about handling categorical columns in the data in second exercise of micro-course of Intermediate Machine Learning on Kaggle

The basic techniques:
1. Drop the column
2. Use Label encoding for ordinal values
3. One hot encoding for nominal values

**Link(s) to work**
[Handled categorical columns in data set](https://github.com/nikunjbhalla/kaggle-courses/blob/master/2.%20Intermediate%20Machine%20Learning/Categorical%20Variables.ipynb)



### Day 4: October 9, Wednesday

**Today's Progress**: Applied learning from last two days to the kaggle competition. Came across another challenge where test data had some more missing values in other columns, number of which was very small.
Still to get understanding of this, but lot of learning in this handson excercise.

- Handled missing values in train and validation data
- One hot encoded the categorical values with smaller cardinality (<10).

Later, did some excercises on python data types and functions


**Link(s) to work**
[Handled missing values and categorical columns in data set](https://github.com/nikunjbhalla/kaggle-courses/blob/master/2.%20Intermediate%20Machine%20Learning/Categorical%20Variables.ipynb)

### Day 5: October 10, Thursday

**Today's Progress**: Was stuck for hours in a data imputation issue #unblocked. 
Learnt about Pipelines and Cross Validation
- Pipelines : Organizes the data pre-processing steps and modelling code. 
- Cross validation : Running ML model on different subset of data with iterative changes to provide optimal parameters.

Two very useful tools for easy iterations and modularity.


**Link(s) to work**
[Pipeline](https://github.com/nikunjbhalla/kaggle-courses/blob/master/2.%20Intermediate%20Machine%20Learning/3.%20Pipeline.ipynb)


### Day 6: October 11, Friday

**Today's Progress**: Learnt about eXtreme gradient boosting (XGBoost) and it's tuning parameters.

Applied the learning of previous days to my housing price prediction model.
Stepps used in the current random forest model script:
1. Separate transformers for numerical and categorical data.
2. Utilized Pipeline for preprocessing step, rather than individually doing all the  imputation
3. Cross validation of model with different tree sizes, created modell with the optimum one.

With the same preprocessing steps, used XGBoost instead of Random Forest. 
Ran cross validation to find optimum regressor number and learning rate.

A great dip in MAE score, lesser means better here :)

PS: Reached Top 5% in the Kaggle competition (628/14807)

**Link(s) to work**
[Housing Price Prediction - Random Forest](https://github.com/nikunjbhalla/kaggle-iowa-house-prediction/blob/master/notebook/housing-price-prediction-with-randomforest.ipynb)
[Housing Price Prediction - XGBoost](https://github.com/nikunjbhalla/kaggle-iowa-house-prediction/blob/master/notebook/housing-price-prediction-with-xgboost.ipynb)

### Day 7 and 8: October 12-13, Saturday-Sunday

**Today's Progress**: Completed Intermediate Machine Learning micro course on Kaggle with lot of readings related to data leakage. 
Two main categories:
1. Target Leakage : This occurs when your predictors include data that will not be available at the time you make predictions
2. Train Test Contamination : Using pipelines feature can simply avoid these.

Spent time practicing problems related to python list and tuples.

For next few days, focus will be on python practice, pandas and data visualization tools. Some warm-up before the sprint
