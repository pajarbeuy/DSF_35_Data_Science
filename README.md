# DSF_35_Data_Science_Portofolio
Breast Cancer Diagnostic Classification Using Random Forest Algorithm
This project is developed as part of Digital Skill Fair (DSF) 35.0 - Data Science by Dibimbing. I am using Wisconsin Breast Cancer Diagnostic Dataset from scikit-learn, which is a classic and very easy binary classification dataset. It has 569 instances, and attributes; including: 30 numeric, predictive attributes and the class. The objective is to build a machine learning model for predicting whether a breast tumor is benign (0) or malignant (1) using Random Forest Algorithm. You can access the dataset through this link: https://scikit-learn.org/1.5/modules/generated/sklearn.datasets.load_breast_cancer.html#sklearn.datasets.load_breast_cancer.

#Goals:

The primary goal of this project is to build a machine learning model that can accurately predict whether a breast tumor is benign (non-cancerous) or malignant (cancerous) based on its characteristics.

# Insights:

Tumor size and shape are highly predictive: The correlation matrix and feature importance analysis revealed that features like radius, perimeter, area, and concavity are strongly associated with malignancy. This suggests that larger and more irregularly shaped tumors are more likely to be cancerous.
Texture and smoothness have less influence: Features like texture and smoothness showed weaker correlations with the target variable, indicating they might be less important for classification.
Random Forest is a promising model: The Random Forest model achieved a high accuracy score, suggesting it's a suitable algorithm for this task. It also provides insights into feature importance, aiding in understanding the model's decision-making process.
Potential for model improvement: Despite the good accuracy, there's always room for improvement. Further exploration of feature engineering, hyperparameter tuning, or trying other models could enhance performance.
# Conclusion

This project demonstrates the potential of machine learning for breast cancer classification. By using features extracted from tumor characteristics, a Decision Tree can effectively distinguish between benign and malignant cases, with the accuracy of 93%. While the current model shows promising results, further development and validation are necessary to ensure its reliability and potential for clinical use.

If you have any questions, suggestions or feedbacks, please do not hesitate to reach me out through Email or 
LinkedIn:pajar280505@gmail.com or https:www.linkedin.com/in/pajar-saputra-88563b2a6
