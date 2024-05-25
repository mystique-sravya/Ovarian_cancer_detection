# README

## Ovarian Cancer Prediction using Machine Learning Techniques

### Overview
Ovarian cancer is one of the most significant health challenges faced by women worldwide. Early detection is crucial for effective treatment and improved survival rates. This project aims to develop an accurate and reliable predictive model for early detection of ovarian cancer using advanced machine learning techniques.

### Project Objectives
1. **Data Pre-processing**: Clean the dataset by handling missing values and standardizing numerical features.
2. **Feature Selection**: Use the Minimum Redundancy Maximum Relevance (MRMR) algorithm to select the most informative biomarkers for ovarian cancer prediction.
3. **Model Development**: Utilize the CatBoost classifier for its renowned feature handling ability and high predictive performance.
4. **Model Evaluation and Tuning**: Extensively evaluate the model and re-tune its hyperparameters to improve its configuration and predictive accuracy.
5. **Comparative Analysis**: Compare the performance of the CatBoost model with other machine learning models including Support Vector Machines, Logistic Regression, and various neural networks (Simple RNN, MLP, LSTM).
6. **Statistical Analysis**: Perform statistical analyses to substantiate the significance of the selected features and ascertain the reliability of the model.

### Data Pre-processing
- **Handling Missing Values**: Applied K-nearest neighbours (KNN) imputation to ensure a complete and representative dataset.
- **Standardizing Numerical Features**: Ensured consistency and comparability across features by standardizing numerical data.

### Feature Selection
- **Minimum Redundancy Maximum Relevance (MRMR)**: Selected the most informative biomarkers for ovarian cancer prediction, reducing redundancy and maximizing relevance.

### Model Development
- **CatBoost Classifier**: Chosen for its high predictive performance and efficient handling of categorical features. Achieved a predictive accuracy of 97.0%.

### Model Evaluation and Tuning
- **Hyperparameter Tuning**: Adjusted hyperparameters to optimize the model's performance.
- **Evaluation Metrics**: Used accuracy, precision, recall, F1-score, and ROC-AUC to evaluate the model's performance.

### Comparative Analysis
- **Support Vector Machines**
- **Logistic Regression**
- **Neural Networks**: Evaluated models including Simple RNN, MLP, and LSTM.
- **Performance Comparison**: CatBoost classifier outperformed other models in terms of predictive accuracy and reliability.

### Statistical Analysis
- **Feature Significance**: Conducted statistical tests to confirm the significance of selected biomarkers.
- **Model Reliability**: Assessed the model's reliability and predictive power of individual biomarkers in association with ovarian cancer.

### Conclusion
This study provides a robust predictive model for early detection of ovarian cancer, leveraging advanced machine learning techniques. The developed model contributes to decreasing the mortality rate associated with ovarian cancer through early detection, prognosis assessment, and personalized treatment strategies.

### Keywords
- Ovarian Cancer
- Machine Learning
- CatBoost
- Feature Selection
- Predictive Modeling
- Biomarkers
- Data Pre-processing
- Hyperparameter Tuning
- Statistical Analysis
- Early Detection
- Classification Reports


### How to Run the Project
1. **Install Dependencies**: Ensure you have Python and necessary libraries installed.
2. **Run Pre-processing**: Execute pre-processing scripts to prepare the dataset.
3. **Feature Selection**: Run the feature selection script to identify key biomarkers.
4. **Model Training**: Execute the CatBoost model training script, followed by hyperparameter tuning.
5. **Model Evaluation**: Use evaluation scripts to assess the model's performance.
6. **Comparative Analysis**: Run scripts for other machine learning models and compare results.
7. **Statistical Analysis**: Perform statistical tests to validate feature significance and model reliability.

### Contact
For any queries or further information, please contact [Your Name] at [Your Email].

---

This README file serves as a comprehensive guide to understanding and reproducing the study. It includes detailed descriptions of objectives, methodologies, and instructions for running the project, ensuring clarity and ease of use for future researchers and developers.
