# Flightperformance
To predict the on-time performance of flight using ML

# Data Overview

The data under consideration was obtained from the official website of Bureau of Transportation Statistics, United States Department of Transportation. 
Details of flights that flew between 15 different airports were isolated over a period of five years, that is, from 2013-2017.Separate weather datasets over 
the same time period and locations were also obtained.
The weather dataset provided the weather details for every hour of every day over the time period. 

# Classification

SMOTE (Synthetic Minority Over-Sampling Technique) was used to rectify the imbalance present in the dataset.
Random Forest algorithm performed best with 92.02% accuracy.

# Regression

Hyper Parameter Tuning was carried out to improve the regression results on a trial and error basis.
The best performing algorithm was found to be Gradient Boosting algorithm along with hyper tuned parameters with variance of 0.9855 
and with a mean absolute error of approximately 6 minutes and a mean squared error of 75.4387.
