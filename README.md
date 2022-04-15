# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to test 6 different machine learning models and see which one is best for predicting load credit risk.

## Results
* The results of random Oversampling are:
    * Balanced Accuracy Score: 0.66
    * Precision score for high-risk loans was very low 0.01
    * Precision score for low-rist loans was 1
    * Recall was 0.69 (high-risk) and 0.63 (low-risk)

<img width="550" alt="randomOversampling" src="https://user-images.githubusercontent.com/95047485/163514343-035853d2-e45b-4d23-a48e-003339eb14e3.PNG">


* The results of SMOTE oversampling:
    * Balanced Accuracy Score: 0.66
    * Precision score for high-risk loans was very low 0.01
    * Precision score for low-rist loans was 1
    * Recall was 0.69 (high-risk) and 0.63 (low-risk)

<img width="571" alt="SMOTEoversampling" src="https://user-images.githubusercontent.com/95047485/163514346-49f6e3ac-62be-4fca-9908-0b2086494c33.PNG">


* The results of Undersampling yielded slightly different results:
    * Balanced Accuracy Score: 0.66
    * Precision score for high-risk loans was very low 0.01
    * Precision score for low-rist loans was 1
    * Recall was 0.4 (high-risk) and 0.63 (low-risk), this model isn't as good with high-risk

<img width="549" alt="undersampling" src="https://user-images.githubusercontent.com/95047485/163515443-63e439e8-86e7-4040-9a04-fde110bf46f9.PNG">


* The results of Combination (Over and Under) Sampling:
    * Balanced Accuracy Score: 0.54
    * Precision score for high-risk loans was very low 0.01
    * Precision score for low-rist loans was 1
    * Recall was 0.57 (high-risk) and 0.72 (low-risk)
    
<img width="570" alt="comboOverUnderSampling" src="https://user-images.githubusercontent.com/95047485/163515596-bf9f24ea-af65-4169-a713-4e9a88009366.PNG">


* The results of Balanced Random Forest Classifier:
    * Balanced Accuracy Score: 0.70
    * Precision score for high-risk loans was very low 0.03
    * Precision score for low-rist loans was 1
    * Recall was 0.70 (high-risk) and 0.87 (low-risk)

<img width="579" alt="balancedRandomForestClassifier" src="https://user-images.githubusercontent.com/95047485/163515768-a7042018-2ef6-4be8-b8a4-02381d2ba32b.PNG">

* The results of Ada Boost Classifier:
    * Balanced Accuracy Score: 0.79
    * Precision score for high-risk loans 0.85 - Best score of all the models
    * Precision score for low-rist loans was 1
    * Recall was .40 (high-risk) and 1 (low-risk)

<img width="525" alt="AdaBoostClassifier" src="https://user-images.githubusercontent.com/95047485/163515899-d3447724-ce17-4e78-815b-e0330f2bf621.PNG">

## Summary
These results suggest that the Ada Boost machine learning model would be the best solution for predicting credit risk and default risk when assessing potential bank loans. The Ada Boost is most precise with the high-risk loans, which is the type of loan that would be important to correctly identify.


