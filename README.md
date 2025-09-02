# Rainfall_Prediction_ML_Model
🌧️ Predicting tomorrow’s rain today — using machine learning for smarter agriculture and resource planning.

📌 Introduction

Rainfall prediction plays a crucial role in weather forecasting, agriculture, and water management. This project develops a supervised machine learning model to predict whether it will rain tomorrow, using the Australian Weather Dataset from Kaggle.

The model helps improve weather forecast accuracy, supporting better decisions in irrigation planning, crop productivity, and environmental management.

🎯 Objective

To improve rainfall forecast accuracy, particularly for agricultural applications, enabling farmers to:

Optimize irrigation schedules

Manage water resources efficiently

Improve crop yield and productivity

🛠️ Methodology
1. Data Collection

Dataset: Australian Weather Dataset (145,460 samples, 23 features)

Features: Temperature, rainfall, evaporation, sunshine, wind, humidity, pressure, cloud cover, etc.

Target Variable: RainTomorrow (Yes/No)

2. Data Preprocessing

Handled missing values (mode for categorical, mean for numerical)

Encoded categorical variables (Label & One-Hot Encoding)

Standardized numerical features

Split dataset into 80% training / 20% testing

3. Models Implemented

Logistic Regression

Decision Tree

Support Vector Machine (SVM)

Each model was trained with and without Python packages to evaluate performance consistency.

📊 Results
With Python Packages

Best Accuracy: Logistic Regression (83.9%)

Best Balanced Performance: Decision Tree (F1-score = 0.51 for Class 1, 0.86 for Class 0)

Without Python Packages

Best Accuracy: SVM (83.6%)

Best Balanced Performance: Decision Tree (F1-score = 0.54 for Class 1, 0.89 for Class 0)

👉 Overall, Decision Trees consistently showed reliable performance across both scenarios.

✅ Conclusion

Logistic Regression and SVM achieved strong accuracy.

Decision Trees offered better balance in precision, recall, and F1-scores, making them a reliable choice.

Rainfall prediction using ML can effectively support agriculture, irrigation, and water resource management.
