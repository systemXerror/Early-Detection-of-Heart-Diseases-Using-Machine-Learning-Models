Early Detection of Heart Disease Using Machine Learning

📄 Abstract

Cardiovascular diseases remain one of the leading causes of mortality worldwide. Early detection plays a critical role in reducing fatal outcomes and improving patient care. This project investigates the effectiveness of multiple machine learning classification models for predicting heart disease using clinical and demographic data. Several supervised learning algorithms were trained, evaluated, and compared to identify the most accurate and reliable predictive model.

🔑 Keywords

Heart Disease Prediction, Machine Learning, Classification, PCA, SVM, Healthcare Analytics

📌 Project Objectives

Perform exploratory data analysis on heart disease data

Preprocess and transform features for optimal learning

Train and evaluate multiple machine learning classifiers

Compare model performance using standard evaluation metrics

Identify the best-performing model for early heart disease detection

📂 Repository Structure

├── Group_9_Cse437_Project.ipynb   
├── README.md                     

📊 Dataset Description

Samples: 1025 patient records

Features: 13 input features + 1 target label

Target Variable:

0 → No heart disease

1 → Presence of heart disease

Feature Categories

Numerical Features

Age

Resting blood pressure

Cholesterol

Maximum heart rate achieved

ST depression (oldpeak)

Categorical Features

Sex

Chest pain type

Fasting blood sugar

Resting ECG

Exercise-induced angina

Slope of ST segment

Number of major vessels

Thalassemia

🔍 Exploratory Data Analysis (EDA)

The EDA phase included:

Dataset shape and structure inspection

Feature data types and distributions

Class balance analysis

Correlation analysis

Descriptive statistics

⚙️ Data Preprocessing

Feature scaling and encoding

Train–test split (70% / 30%)

Dimensionality reduction using Principal Component Analysis (PCA)

Final feature space: 33 principal components

🤖 Machine Learning Models Implemented

Logistic Regression

Support Vector Machine (SVM)

(Additional models explored during experimentation)

📈 Evaluation Metrics

Accuracy

Area Under ROC Curve (AUC)

Precision

Recall

F1-Score

Confusion Matrix

ROC Curve

Precision-Recall Curve

🏆 Results & Model Comparison
Model	Accuracy	AUC
Logistic Regression	87.34%	0.946
Support Vector Machine (SVM)	93.83%	0.980

✅ SVM achieved the highest predictive performance, demonstrating strong generalization capability and superior discriminative power.

🧠 Key Findings

PCA significantly improved model efficiency without major loss of information

SVM outperformed Logistic Regression in both accuracy and AUC

The model shows strong potential for assisting clinical decision-making

🛠️ Tools & Technologies

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Environment: Google Colab / Jupyter Notebook

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Open Group_9_Cse437_Project.ipynb

Ensure dataset paths are correct

Run all cells sequentially

📌 Limitations

No hyperparameter tuning was applied

Dataset size is relatively small

External validation dataset not used

🔮 Future Work

Hyperparameter optimization (GridSearch / RandomSearch)

Cross-validation

Explainable AI (SHAP / LIME)

Deployment as a web or mobile application

Integration with real-time medical data

👥 Team Information

Group 9 – CSE437
Department of Computer Science & Engineering

📄 License

This project is intended strictly for academic and educational purposes.
