<h1 align="center"> Parkinson's Disease Prediction </h1>

This repository contains a machine learning model that stacks multiple of the most used (ex. logistic regression, KNN, decision tree, etc), to create a 95% accurate Parkinson's prediction model based off of several metrics. In the data set, many more individuals that had Parkinson's were tested, thus SMOTE was used to balance the dataset. 

![image](https://github.com/user-attachments/assets/f9fec87a-b01e-4167-9741-e555d710d464)

\
The predictors are mostly centered around voice measures. The metrics include:

name - ASCII subject name and recording number

MDVP:Fo(Hz) - Average vocal fundamental frequency

MDVP:Fhi(Hz) - Maximum vocal fundamental frequency

MDVP:Flo(Hz) - Minimum vocal fundamental frequency

MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP - Several measures of variation in fundamental frequency

MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude

NHR,HNR - Two measures of ratio of noise to tonal components in the voice

status - Health status of the subject (one) - Parkinson's, (zero) - healthy

RPDE,D2 - Two nonlinear dynamical complexity measures

DFA - Signal fractal scaling exponent

spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation


\
Data was sourced from:  

Little,Max. (2008). Parkinsons. UCI Machine Learning Repository. https://doi.org/10.24432/C59C74.


