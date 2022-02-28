# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to train and compare different machine learning models that help predict credit risk. The data is imbalanced as there are far more low-risk loan status than high risk. We would use Random Over Sampler and SMOTE to oversample, Cluster Centroids to undersample and SMOTEENN to combine over- and undersamples. We also used two machine learning models Balanced Random Forest Classifier and Easy Ensemble Classifier to reduce bias as we predict credit risk.  

### Results

The screenshots below depict the balanced accuracy score, precision and sensitivity (recall) of the different models.

- Naive Random Oversampling
 ![1](https://user-images.githubusercontent.com/92958091/156004426-a4f65d9f-7829-4b30-a750-edb27e0ee167.png)

- SMOTE Oversampling
![2](https://user-images.githubusercontent.com/92958091/156005059-4b9c4311-e44a-481b-b812-96b88e048de7.png)

- Undersampling
![3](https://user-images.githubusercontent.com/92958091/156005240-c9590619-10f1-4535-b25c-ca4b7ab584ef.png)

- Combination (Over and Under) Sampling (SMOTEENN)
![4](https://user-images.githubusercontent.com/92958091/156005408-2f5f6881-6fc0-436a-a45d-9f9e9d8a783a.png)

- Balanced Random Forest Classifier
![5](https://user-images.githubusercontent.com/92958091/156005580-5c67b6d9-ed00-463c-817c-cd1ae5950528.png)

- Easy Ensemble AdaBoost Classifier
![6](https://user-images.githubusercontent.com/92958091/156005828-203f3625-20e1-49d5-a5e5-c597a7a31263.png)

#### Summary
- Among the resampling models, the combination (SMOTEENN) model has the highest balanced accuracy score (67%) which is only a few points higher than the other models. For these resampling models the high risk and low risk predictions were 1% and 100% respectively. 
- The Balanced Random Forest Classifier has a balanced accuracy score of 78.9% while Easy Ensemble AdaBoost shows 93.2%. While both models predict low risk 100% of the time, the high risk prediction of Random Forest is 3% while Easy Ensemble predicts 9%, highest out of all models making it the best option among the choices to predict credit risk.
