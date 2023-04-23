# DSAI_mini_project
Welcome to Cardiovascular Disease Predictor Repository

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on predicting whether someone is suffering from a Cardiovascular disease and what are the most influential factors that lead to such diseases.
The dataset we have used is Cardiovascular Disease dataset from Kaggle.
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset

Project Overview - 
This dataset contains information on individuals and whether or not they have cardiovascular diseases. To find the most influential parameters for the type of data, we used the .coef_method for Logistic Regression Model. Since we have both numerical and binary data, they cannot be compared together but rather have to be compared separately. 
Here are the 3 most influential factors for numerical features - 
ap_hi: systolic blood pressure of the patient.
Age: Age of the patient in days.
Cholesterol: Cholesterol level of the patient. 1 represents normal, 2 represents above normal, 3 represents well above normal.
And here are the 3 most influential factors for binary features - 
Active: Whether or not the patient is physically active. 0 represents no and 1 represents yes.
Smoke: Whether or not the patient is a smoker. 0 represents no and 1 represents yes.
alco: Whether or not the patient is an alcoholic. 0 represents no and 1 represents yes.

We have performed an age distribution to calculate the average age of people suffering cardiovascular diseases which is 54.51 years. 
We have also created violin plots to show the influence of cardiovascular diseases on factors such as Systolic and Diastolic Blood Pressure, Glucose and Cholesterol.

We have also created a function that is able to predict whether someone has a cardiovascular disease using sample inputs. We used 2 approaches to calculate the probability which are - 
Max Accuracy Approach - Selects the model which has the highest probability and returns the respective probability
Weighted Mean Approach - Calculates the weighted mean of probabilities with accuracy of models as weights.

Models Used - 
We have used the following models. 
Support Vector Machines (SVM)
Logistic Regression
Naive Bayes
Random Forest Classifier
K-Neighbours

After using these models, we calculated each of their accuracy scores which described how accurate they were. The most accurate model that was used was Support Vector Machines (SVM) with a score of 72.2%.

Contributors - 
Mittal Arnav - Analysis, Exploratory Data Analysis, Machine Learning Models, slides
Samudrala Adithya - Sample Input Predictor,  Machine Learning Models, Comparison of Machine Learning Models, slides & video
Agarwal Dhruv - Data Preparation/ Cleaning, Exploratory Data Analysis, slides

References:-
https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset
https://seaborn.pydata.org/
https://www.geeksforgeeks.org/naive-bayes-classifiers/
https://www.ibm.com/topics/random-forest
https://www.ibm.com/topics/knn
https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc


