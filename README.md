### Predicting the Effectiveness of Chemotherapy in Breast Cancer Patients

## Overview
This project applies machine learning (ML) and deep learning (DL) models to predict the effectiveness of chemotherapy in breast cancer patients. It utilizes clinical and genetic data to improve accuracy and reliability in real-world healthcare applications.

## Dataset
The dataset used is METABRIC_RNA_Mutation.csv, which contains 1904 samples and 693 features, including: 
- Clinical data (e.g., age_at_diagnosis, type_of_breast_surgery, cellularity)
- Genetic mutations
- Target variable: chemotherapy (1 = Chemotherapy given, 0 = No chemotherapy)
  
## Models Implemented
1. Logistic Regression (Baseline Model)
2. Random Forest Classifier (ML Model with Hyperparameter Tuning)
3. Deep Learning (Feedforward Neural Network) (Optimized for Accuracy)

   
## Key Evaluation Metrics
- Recall (Sensitivity): Most critical to ensure chemotherapy patients are correctly identified.
- F1-Score: Balances Precision and Recall.
- Accuracy: Overall correctness but may be misleading if the dataset is imbalanced.

## Data Preprocessing & Visualization
1. Missing value analysis & imputation
2. Feature selection using correlation analysis
3. Data visualization for age distribution, chemotherapy distribution, and feature importance


## Future Improvements
- Implement XGBoost or LightGBM for additional comparison.
- Perform SMOTE oversampling if data is highly imbalanced.
- Experiment with different deep learning architectures for higher accuracy.
