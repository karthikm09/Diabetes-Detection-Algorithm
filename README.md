# Diabetes-Detection-Algorithm

The dataset you will be using in the following parts is the "Pima Indians Diabetes Dataset".

There are two data files: "Diabetes_training.csv" and "Diabetes_Xtest.csv" Both files have the following fields, except quality which is not available in "Diabetes_Xtest.csv".

Features:

1 - pregnant: Number of times pregnant
2 - glucose: Plasma glucose concentration (glucose tolerance test)
3 - pressure: Diastolic blood pressure (mm Hg)
4 - triceps: Triceps skin fold thickness (mm)
5 - insulin 2-Hour serum insulin (mu U/ml)
6 - mass: Body mass index (weight in kg/(height in m)^2)
7 - pedigree: Diabetes pedigree function
8 - age: Age (years)

Target:

diabetes: ('neg','pos')

Training dataset, "Diabetes_training.csv", contains 576 rows and 9 columns. This is the training set containing both of the features and the target. Test dataset, "Diabetes_Xtest.csv", contains 192 rows and 8 columns. This is the test set which only contains the features. Prediction task is to determine the test for diabetes. (If you transfrom the target as binary values, please make sure "pos" is 1, "neg" is 0)

Data Processing and Feature Engineering:

Standardization and One-Hot encoding
Hyperparameter Tuning using Grid Search
Model:

Random Forest and Decision Trees
