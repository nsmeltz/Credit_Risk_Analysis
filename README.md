# Credit Risk Analysis

# Overview of the analysis: 
The purpose of this analysis is to apply 6 machine learning algorithms and assess which model produces the best results for the given [credit dataset](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0f3846712b105e79d36c388d4bdbc2354fadf271/LoanStats_2019Q1.csv).

# Results 
### I. Resampling with Logistic Regression Modeling

  - ### Oversampling
    - **Random Oversampling**                                                                            
    ![Random Oversampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/8f288df3588427d9023a88b996eb33d27e2d4e8d/Images/random_oversampling.jpg)
    About 65% of all data points were accurately predicted by the model. The high-risk precision is 1% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.66 (ie how likely it is that the test will correctly predict a high-risk loan)
    
    - **SMOTE Oversampling**
    ![SMOTE Oversampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/8f288df3588427d9023a88b996eb33d27e2d4e8d/Images/smote_oversampling.jpg)
    About 66% of all data points were accurately predicted by the model. The high-risk precision is 1% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.63 (ie how likely it is that the test will correctly predict a high-risk loan)
    
  - ### Undersampling
    - **Cluster Centroid Undersampling**
    ![Cluster Centroid Undersampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0e58922b7860f5c20419b1f405ab33f9bc3c3afc/Images/cluster_centroid_undersampling.jpg)
    About 55% of all data points were accurately predicted by the model. The high-risk precision is 1% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.69 (ie how likely it is that the test will correctly predict a high-risk loan)
    
  - ### Combination Sampling  
    - **SMOTEENN Combination Sampling**
    ![SMOTEENN Combo Sampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0e58922b7860f5c20419b1f405ab33f9bc3c3afc/Images/smoteenn_combosampling.jpg)
    About 65% of all data points were accurately predicted by the model. The high-risk precision is 1% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.73 (ie how likely it is that the test will correctly predict a high-risk loan)
    
### II. Ensemble Learning Modeling
  - **Balanced Random Forest Classification**
  ![Balanced Random Forest Classification](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/fcf5bf6872fc110a0f548d9ca1a7af36e6f35c5d/Images/balanced_random_forest_classification.jpg)
  About 79% of all data points were accurately predicted by the model. The high-risk precision is 3% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.70 (ie how likely it is that the test will correctly predict a high-risk loan)
  
  - **Easy Ensemble AdaBoost Classification**
  ![Easy Ensemble AdaBoost Classification](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/fcf5bf6872fc110a0f548d9ca1a7af36e6f35c5d/Images/easy_ensemble_adaboost_classification.jpg)
  About 93% of all data points were accurately predicted by the model. The high-risk precision is 9% (ie percentage of actual high-risk loans out of the total number of model predicted high-risk loans). The high-risk recall is 0.92 (ie how likely it is that the test will correctly predict a high-risk loan)

# Summary 

In summary all of these machine learning models had nearly the same accuracy (55-65%) except the ensemble learning methods (80-90%). At first glance it may seem that the Easy Ensemble AdaBoost is the best models because of the high accuracy and recall, but it also may be overfitting the noise/ outliers in data. I would choose the balanced random forest classification because it accurately predicts 80% of the input data while also retaining a high recall and increased precision compared to the resampling with logistic regression models 
