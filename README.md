# Heart-Failure-Predictor
Logistic Regression on 11 clinical features for predicting heart disease events.

OBJECTIVE:

The main objective of this work is to predict if a patient is at risk of having heart disease or not, based on the common features of patients with heart disease.

DATA USED:

This dataset was created by combining different datasets already available independently but not combined before. In this dataset, 5 heart datasets with a total of 918 observations are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes. The features are as the following:

Age: age of the patient [years]

Sex: sex of the patient [M: Male, F: Female]

ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]

RestingBP: resting blood pressure [mm Hg]

Cholesterol: serum cholesterol [mm/dl]

FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]

RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]

MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]

ExerciseAngina: exercise-induced angina [Y: Yes, N: No]

Oldpeak: oldpeak = ST [Numeric value measured in depression]

ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]

TARGET:

HeartDisease: output class [1: heart disease, 0: Normal]

# Problem at hand:
Based on the data and data dictionary, We have a classification problem.

We wil make classification on the target variable Heart Disease

And we will build a model to get best calssification possible on the target variable.

For that we will look at the balance of the target variable.

# Conclusion
We have developed model to classifiy heart disease cases.

First, we made the detailed exploratory analysis.

We have decided which metric to use.

We analyzed both target and features in detail.

We transform categorical variables into numeric so we can use them in the model.

# Models Developed:

Logistic Regression:  Model Accuracy is:84.24
                      
                      Recall Score is:81.31
                      
Random Forest Classifier: Model Accuracy is:88.04
                          
                          Recall Score is:87.85                    
KNN(k-Nearest Neighbour Classification):Model Accuracy is:86.41%
                                        Recall Score is:82.24%  
                                          
