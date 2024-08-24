# Parkinsons-Disease-Predictor
This machine learning model takes the biomedical voice information of a patient and predicts whether they are at risk for Parkinson's disease. The classification was perfomred using the Support Vector Model and its Linear kernel. I used Standard Scaler to scale the training and test data in an attempt to increase the accuracy score. 

## Dataset Information<br/>
The data was extracted from Kaggle. It includes the biomdedical voice measurements from 31 people, along with whether or not they have Parkinson's disease.  <br/>
URL Link: https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set n<br/>

## Atrtribute Information: <br/>
name - ASCII subject name and recording number<br/>
MDVP:Fo(Hz) - Average vocal fundamental frequency<br/>
MDVP:Fhi(Hz) - Maximum vocal fundamental frequency<br/>
MDVP:Flo(Hz) - Minimum vocal fundamental frequency<br/>
MDVP:Jitter(%), MDVP:Jitter(Abs), MDVP:RAP, MDVP:PPQ, Jitter:DDP - Several measures of variation in fundamental frequency<br/>
MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA - Several measures of variation in amplitude<br/>
NHR, HNR - Two measures of the ratio of noise to tonal components in the voice<br/>
status - The health status of the subject (one) - Parkinson's, (zero) - healthy<br/>
RPDE, D2 - Two nonlinear dynamical complexity measures<br/>
DFA - Signal fractal scaling exponent<br/>
spread1,spread2,PPE - Three nonlinear measures of fundamental frequency variation<br/>

## Accuracy Score: 
0.8979591836734694
