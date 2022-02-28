# Credit_Risk_Analysis **Machine learning**
## Overview of the loan prediction risk analysis:

The purpose of this analysis is to use various Machine Learning algorithms to resample the data. These algorithms include RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/1_resample_counter.PNG)
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/7_balance_clissifier.PNG)

**Results of six machine learning models:**

**1. Naive Random Oversampling:** 
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/2_oversampleing%20ac%20score.PNG)
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/3_oversampling_report.PNG)
Accuracy score it 65%.
The precision for the high_risk is 1% and the recall is 71%
The precision for the low_risk is 100% and the recall is 60%

**2.SMOTE oversampling:**
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/4_smote_oversampling.PNG)
Accuracy score it 66%.
The precision for the high_risk is 1% and the recall is 63%
The precision for the low_risk is 100% and the recall is 69%

**3.Undersampling:**
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/5_undersampling_report.PNG)
Accuracy score it 54%.
The precision for the high_risk is 1% and the recall is 69%
The precision for the low_risk is 100% and the recall is 40%

**4.Combination(over and undersampling):**
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/6_combine%20sampling.PNG)
Accuracy score it 63%.
The precision for the high_risk is 1% and the recall is 70%
The precision for the low_risk is 100% and the recall is 58%

**5.Balanced Random Forest Classifier:**
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/8_balance%20samp.PNG)
Accuracy score it 78%.
The precision for the high_risk is 3% and the recall is 70%
The precision for the low_risk is 100% and the recall is 87%

**6.Easy Ensemble AdaBoost Classifier:**
![This is an image](https://github.com/Sirius0531/Credit_Risk_Analysis/blob/main/resources/9_easyensemble.PNG)
Accuracy score it 93%.
The precision for the high_risk is 9% and the recall is 92%
The precision for the low_risk is 1% and the recall is 94%

**Summary:**
Rank all the machine learning models:
EasyEnsembleClassifer: 93.2% accuracy 
BalancedRandomForestClassifer: 78.9% accuracy 
SMOTE: 66% accuracy 
SMOTEENN: 66% accuracy 
RandomOverSampler: 65% accuracy 
ClusterCentroids: 54.5% accuracy 


**Recommendation:**
The EasyEnsembleClassifer model will be recommend to perfform this analysis.
It yielded the best results with an accuracy rate of 93.2% and a 9% precision rate when predicting "High Risk candidates. The sensitivity rate (aka recall) was also the highest at 92% compared to the other models. The result for predicting "Low Risk" was also the highest with the sensitivity rate at 94% and an F1 score of 97%. 
