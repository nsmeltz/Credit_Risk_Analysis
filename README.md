# Credit Risk Analysis

# Overview of the analysis: 
The purpose of this analysis is to apply 6 machine learning algorithms and assess which model produces the best results for the given [credit dataset](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0f3846712b105e79d36c388d4bdbc2354fadf271/LoanStats_2019Q1.csv).

# Results 

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### I. Resampling with Logistic Regression Modeling

  - ### Oversampling
    - **Random Oversampling**                                                                            
    ![Random Oversampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/8f288df3588427d9023a88b996eb33d27e2d4e8d/Images/random_oversampling.jpg)
    - **SMOTE Oversampling**
    ![SMOTE Oversampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/8f288df3588427d9023a88b996eb33d27e2d4e8d/Images/smote_oversampling.jpg)
  - ### Undersampling
    - **Cluster Centroid Undersampling**
    ![Cluster Centroid Undersampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0e58922b7860f5c20419b1f405ab33f9bc3c3afc/Images/cluster_centroid_undersampling.jpg)
    
  - ### Combination Sampling  
    - **SMOTEENN Combination Sampling**
    ![SMOTEENN Combo Sampling](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/0e58922b7860f5c20419b1f405ab33f9bc3c3afc/Images/smoteenn_combosampling.jpg)
    
### II. Ensemble Learning Modeling
  - **Balanced Random Forest Classification**
  ![Balanced Random Forest Classification](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/fcf5bf6872fc110a0f548d9ca1a7af36e6f35c5d/Images/balanced_random_forest_classification.jpg)
  
  - **Easy Ensemble AdaBoost Classification**
  ![Easy Ensemble AdaBoost Classification](https://github.com/nsmeltz/Credit_Risk_Analysis/blob/fcf5bf6872fc110a0f548d9ca1a7af36e6f35c5d/Images/easy_ensemble_adaboost_classification.jpg)
# Summary 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
