# Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classification

# ABSTRACT
This project focuses on the development of a machine learning (ML) model for the classification of Chronic Kidney Disease (CKD) using patient data. The aim is to reduce training time while improving accuracy through feature selection and an ensemble approach.

To address the challenge of training time, a comprehensive feature selection process is employed. Various techniques such as 
Pearson Correlation - High absolute value implies more importance for the particular attribute due to stronger linear relationship 
Chi-square - High value implies more importance for the particular attribute due to better association between variables
Recursive Feature Elimination - Low rank indicates more importance
Lasso Regression - High coefficient value indicates more importance
Random Forest - High Gini value indicates more importance
SHAP values - High absolute value implies more importance for the particular attribute
Weighted K-Means - Features with higher weights in the clustering process indicate more importance

are utilized to identify the best common set of features. By selecting the most informative features, the model's training time is significantly reduced while preserving relevant information.

Furthermore, in order to enhance the accuracy of the ML model, a stacked ensemble approach is employed. This ensemble consists of parallel implementations of Random Forest, K-Nearest Neighbors (KNN), and Logistic Regression algorithms. By combining the predictions of these models, the overall accuracy is improved through leveraging the strengths of each individual algorithm.

The developed ML model holds great potential in assisting healthcare professionals in the diagnosis and prediction of CKD. By efficiently utilizing a reduced set of features and leveraging the power of ensemble learning, the model offers a valuable tool for accurate classification. Further evaluation and validation of the model using diverse patient datasets will help establish its reliability and effectiveness in real-world scenarios.

# PROCESS DIAGRAM
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/96631f65-10cf-4953-a095-42203dc6ee3f)
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/db81cff9-29eb-4a16-bc2f-f874fe6a9cab)
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/d1bd8aa9-11d9-4b8c-869a-8b61ddcd0388)
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/0be7ade4-0ef0-4ede-b3a6-19046b729bdc)

# RESULTS
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/44423448-6d2b-4c1c-908a-e7fbed1bfdc5)
Drastic drop of about 8-10% on average is observed in the model Training time.

![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/3ed823fe-ef27-4f67-b09f-b43c43e6aae7)
![image](https://github.com/Vimalan-S/Stacked-Ensemble-of-Parallel-ML-Algorithms-with-best-Attributes-for-Chronic-Kidney-Disease-Classific/assets/105377221/6f9a00fb-7371-46df-9894-a37310524b22)
Accuracy of the Stacked ensemble of ML algorithms still managed to be at higher rates at 99.4% on average, eventhough training times are reduced.




