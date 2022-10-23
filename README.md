# Credit_Risk_Analysis

## Project Overview
The purpose of this project is to use the 6 machine learning models below to predict credit card risk and make a recommendation on which model to use, if any, based on the results.

1. Random Oversampler  
2. SMOTE Oversampler
3. Cluster Centroids Undersampler
4. SMOTEENN Combination Over/Undersampler
5. Balanced Random Forest Classifier
6. Easy Ensemble Classifier

## Results
The results of the 6 machine learning models are shown below and include the model accuracy, high and low risk precision, and high and low risk recall.

- Random Oversampler
  - Accuracy: 64%
  - High Risk Precision: 1%
  - High Risk Recall: 69%
  - Low Risk Precision: 100%
  - Low Risk Recall: 59%  
  <br/>
![Random Oversampler Accuracy](/Resources/ROM_accuracy.png)
![Random Oversampler Report](/Resources/ROM_report.png)
<br/>
- SMOTE Oversampler
  - Accuracy: 66%
  - High Risk Precision: 1%
  - High Risk Recall: 63%
  - Low Risk Precision: 100%
  - Low Risk Recall: 69% 
    <br/>
![SMOTE Accuracy](/Resources/SMOTE_accuracy.png)
![SMOTE Report](/Resources/SMOTE_report.png)
<br/>
- Cluster Centroids Undersampler
  - Accuracy: 54%
  - High Risk Precision: 1%
  - High Risk Recall: 69%
  - Low Risk Precision: 100%
  - Low Risk Recall: 40% 
    <br/>
![Cluster Centroids Accuracy](/Resources/Cluster_Centroids_accuracy.png)
![Cluster Centroids Report](/Resources/Cluster_Centroids_report.png)
<br/>
- SMOTEENN Combosampler
  - Accuracy: 64%
  - High Risk Precision: 1%
  - High Risk Recall: 72%
  - Low Risk Precision: 100%
  - Low Risk Recall: 57% 
    <br/>
![SMOTEENN Accuracy](/Resources/SMOTEENN_accuracy.png)
![SMOTEENN Report](/Resources/SMOTEENN_report.png)
<br/>
- Balanced Random Forest Classifier
  - Accuracy: 79%
  - High Risk Precision: 3%
  - High Risk Recall: 70%
  - Low Risk Precision: 100%
  - Low Risk Recall: 87%
    <br/>
![Balanced Random Forest Classifier Accuracy](/Resources/BRFC_accuracy.png)
![Balanced Random Forest Classifier Report](/Resources/BRFC_report.png)
<br/>
- Easy Ensemble Classifier
  - Accuracy: 93%
  - High Risk Precision: 9%
  - High Risk Recall: 92%
  - Low Risk Precision: 100%
  - Low Risk Recall: 94%
    <br/>
![Easy Ensemble Accuracy](/Resources/Easy_Ensemble_accuracy.png)
![Easy Ensemble Report](/Resources/Easy_Ensemble_report.png)



## Challenge Summary
The results of the 6 models show that the Easy Ensemble Classifier has the highest accuracy at 93% and the Cluster Centroids Undersampler has the lowest accuracy at 54%.  All six models have a precision percentage lower than 10%, meaning the models are predicting a lot more bad credit than it should be. 

Not only does the Easy Ensemble Classifier have the highest accuracy, it also has the highest recall for the High Risk category at 92%. Since it is more important in the case of credit card risk to be able to detect ALL bad risk vs making sure we don't have false negatives, my recommendation is to use the Easy Ensemble Classifier machine learning model.