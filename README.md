# Credit_Risk_Analysis

## Project Overview:
The purpose of this project was to use different Machine Learning techniques to train and evaulate models with unbalanced classes pertaining to credit risk. Using credit card credit dataset from LendingClub to build 4 models with 2 oversampling algorithms of using `Naive Random` and `SMOTE`, 1 undersampling algorithm using `Cluster Centroids`, and 1 over/undersampling algorithm using `SMOTEEN`. Also add 2 additional models that reduce bias usning `Balanced Random Forest Classifier` and `Easy Ensemble Classifier` algrothims. 

## Results:
  - ### Oversampling
      - `Naive Random`

         ![Native Random Oversampling](https://user-images.githubusercontent.com/92836648/156932732-d23dcad1-02f9-42fe-88f3-f5c7e7c11f87.png)
         - Balance accuracy score = 64%
         - Precision score = High Risk 1% , Low Risk 100%
         - Recall score = High Risk 62% , Low Risk 65%
         
      - `SMOTE`

         ![SMOTE Oversampling](https://user-images.githubusercontent.com/92836648/156932733-1c66f72c-6043-41eb-90bc-08643225fc08.png)
         - Balance accuracy score = 63%
         - Precision score = High Risk 1% , Low Risk 100%
         - Recall score = High Risk 62% , Low Risk 64%        

  - ### Undersampling
      - `Cluster Centroids`

         ![Undersampling](https://user-images.githubusercontent.com/92836648/156932734-3b5cb178-3118-4ac9-b5f7-2de6e887e6e4.png)
         - Balance accuracy score = 53%
         - Precision score = High Risk 1% , Low Risk 100%
         - Recall score = High Risk 61% , Low Risk 45%
         
   - ### Combination (Over and Under) Sampling
      - `SMOTEENN`
      
         ![Combination (Over and Under) Sampling](https://user-images.githubusercontent.com/92836648/156932735-a65f7972-63b3-4c09-9dd0-15c3bb975110.png)
         - Balance accuracy score = 62%
         - Precision score = High Risk 1% , Low Risk 100%
         - Recall score = High Risk 71% , Low Risk 54%

   - ### Ensemble Learners
      - `Balanced Random Forest Classifier`
      
         ![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/92836648/156932736-de13cb49-b366-47b4-9e81-b3411a8f822b.png)
         - Balance accuracy score = 79%
         - Precision score = High Risk 3% , Low Risk 100%
         - Recall score = High Risk 69% , Low Risk 89%
         
      - `Easy Ensemble AdaBoost Classifier`
      
         ![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/92836648/156932737-07751062-442e-492d-81e4-894ae818b82d.png)
         - Balance accuracy score = 92%
         - Precision score = High Risk 7% , Low Risk 100%
         - Recall score = High Risk 91% , Low Risk 94% 

## Summary:
Reivew of the 6 models with results pertaining to balance accuracy scores, precision scores, and recall scores it indicates the best predicitive model is the `Easy Ensemble AdaBoost Classifier` based on most balanced mix of precision and recall scores along with the highest balance accuracy percentage too. 
