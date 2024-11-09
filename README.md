# Indian_liver_Patient_Prediction

## Introduction 

Liver disease has become increasingly prevalent due to factors such as excessive alcohol consumption, exposure to harmful substances, and intake of contaminated food and drugs. Early detection is critical to improving patient outcomes and reducing the strain on healthcare systems. This project, "Prediction of Liver Disease in Patients Using Machine Learning Algorithms," aims to build predictive models to assist doctors in diagnosing liver disease at an early stage. By analyzing patient data with machine learning algorithms, this study seeks to provide a tool that supports timely and accurate diagnosis, ultimately aiding in more efficient patient management and treatment.

## Bussiness Goal 
To develop a predictive model for liver disease to assist healthcare providers in early diagnosis, potentially reducing the workload on doctors and improving patient outcomes.

## Task : Classfication Problem 

1.	MISSING VALUE:
•	In this data no missing value is present.

2.	CATEGORICAL DATA:
•	There were no categorical column.

3.	OUTLIER HANDLING:
• In this data the outlier were handle through IQR method	

4.	FEATURE SCALING:
 •  Standar Scalling was used.


## FEATURE SELECTION:

1.	DROP UNIQUE AND CONSTANT COLUMN:
•	In this data only one unique column is present

2.	CHECK THE CORRELATION:
•	In this data no highly correlated feature is present

3.	CHECK DUPLICATES:
•	There is no duplicates present in data

## Smote technique was used to balance the data 

## Model Saving & Results

The logistic regression model shows balanced training and testing accuracy, with a high recall indicating good sensitivity in detecting positive cases, but overall accuracy is low.

Random forest model The model is overfitting (100% training accuracy), but it maintains a good recall, suggesting it effectively identifies positive cases despite lower generalization on test data.

Similar to Random Forest, the model overfits with perfect training accuracy. The recall indicates some effectiveness in identifying positives, but testing performance is significantly lower.

The model exhibits good training accuracy but suffers from poor generalization to unseen data. Recall indicates reasonable performance in detecting positives, but overall effectiveness needs improvement.

All models exhibit some level of overfitting, particularly the Random Forest and Decision Tree models with perfect training accuracy.
