# Machine Learning
## Classification Homework

### Credit Risk Resampling Techniques

#### Resampling

We were asked to use data from the Lending Club to build and evaluate logistic regression classifiers using resampled data. 

Using the Lending Club data we did the following:

1. Oversampled using Naive Random Oversampler and SMOTE algorithms

2. Undersampled the data using the Cluster Centroids algorithm

3. Over and under sampled the data using a combination SMOTEENN algorithm

#### Questions

1. Which model had the best balanced accuracy score? SMOTE oversampling had the best balanced accuracy score.

2. Which model had the best recall score? SMOTE oversampling also had the best balanced accuracy score.

3. Which model had the best geometric mean score? Again, SMOTE oversampling had the best geometric mean score.


#### Ensemble Learning 

We were asked to train and compare two different ensemble classifiers to predict loan risk and evaluate each model. 

Using the Lending Club data we did the following:

1. Used the Balanced Random Forest Classifier

2. Used the Easy Ensemble Classifier

#### Questions

1. Which model had the best balanced accuracy score? The Easy Ensemble Classifier had the best balanced accuracy score.

2. Which model had the best recall score? The Easy Ensemble Classifier had the best recall score.

3. Which model had the best geometric mean score? The Easy Ensemble Classifier had the best geometric mean score.

4. What are the top three features? Top three features are: "total_rec_prncp," "total_pymnt," and "total_pymnt_inv."

