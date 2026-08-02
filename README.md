# Breast-Cancer-Prediction-Using-Machine-Learning
🎗️ Breast Cancer Survival Prediction Using Machine Learning

📌 Project Overview

This project presents a complete Supervised Machine Learning pipeline for predicting the survival status of breast cancer patients using demographic and clinical information. The goal is to compare multiple machine learning classification algorithms and identify the model that best predicts patient survival.

The project follows the complete data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, handling class imbalance using SMOTE, model training, hyperparameter tuning, performance evaluation, and model interpretation.

🎯 Project Objectives
Perform data cleaning and preprocessing.
Analyze patient demographics and clinical characteristics.
Handle missing values and duplicate records.
Encode categorical variables.
Detect and visualize outliers.
Explore relationships among variables using EDA.
Handle class imbalance using SMOTE.
Train and compare multiple machine learning models.
Optimize the best-performing model using GridSearchCV.
Evaluate model performance using multiple classification metrics.
Identify the most important features influencing survival prediction.
Save the best-performing model for future predictions.

📂 Dataset Description

Dataset: Breast Cancer Survival Dataset:## Dataset The dataset used in this project was obtained from Kaggle. Original Dataset: [https://www.kaggle.com/datasets/reihanenamdari/breast-cancer] Thanks to the dataset author for making this data publicly available.

The dataset contains demographic, clinical, and pathological information collected from breast cancer patients. Each record represents one patient, and the target variable indicates the patient's survival status.

                 Features
Feature	                             Description
Age	                                 Patient age
Race	                               Patient ethnicity
Marital Status	                     Marital status
T Stage	                             Primary tumor stage
N Stage	                             Lymph node stage
6th Stage	                           AJCC 6th Edition Stage
Differentiate	                       Tumor differentiation level
Grade	                               Tumor grade
A Stage	Overall                      cancer stage
Tumor Size	                         Tumor size (mm)
Estrogen Status	                     Estrogen receptor status
Progesterone Status	                 Progesterone receptor status
Regional Node Examined             	Number of examined lymph nodes
Regional Node Positive	            Number of positive lymph nodes
Survival Months	                    Patient survival time
Status	Target Variable             (Alive / Dead)

🛠 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
imbalanced-learn (SMOTE)
Joblib
Jupyter Notebook

📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

Dataset overview
Data types inspection
Missing value analysis
Duplicate record detection
Summary statistics
Histograms
Count plots
Boxplots
Correlation heatmap
Pairplots
Outlier detection using the IQR method
Target class distribution
Feature correlation analysis

⚙ Data Preprocessing

The preprocessing pipeline includes:

Missing value imputation
Label encoding for categorical variables
Feature scaling using StandardScaler
Train/Test split
Class balancing using SMOTE

🤖 Machine Learning Models

The following supervised classification algorithms were implemented and compared:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Gradient Boosting

⚙ Hyperparameter Optimization

The Random Forest classifier was optimized using GridSearchCV to determine the best combination of model parameters and improve predictive performance.

📈 Model Evaluation

Each machine learning model was evaluated using:

Accuracy
Precision
Recall (Sensitivity)
F1-Score
ROC-AUC Score
Cross Validation
Confusion Matrix
ROC Curve
Feature Importance Analysis

📁 Project Structure
Breast-Cancer-Prediction-ML/
│
├── data/
│   └── Breast_Cancer.csv
│
├── notebooks/
│   └── Breast_Cancer_Prediction.ipynb
│
├── images/
│   ├── correlation_heatmap.png
│   ├── pairplot.png
│   ├── class_distribution.png
│   ├── histograms.png
│   ├── boxplots.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── model_comparison.png
│
├── models/
│   ├── RandomForest.pkl
│   ├── LogisticRegression.pkl
│   ├── SVM.pkl
│   └── Best_Model.pkl
│
├── results/
│   ├── model_results.csv
│   ├── feature_importance.csv
│   ├── classification_report.txt
│   ├── cross_validation.csv
│   ├── best_parameters.txt
│   └── final_summary.csv
│
├── reports/
│   └── Final_Report.pdf
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
🚀 Installation

Clone the repository:

git clone https://github.com/yourusername/Breast-Cancer-Prediction-ML.git

Navigate to the project directory:

cd Breast-Cancer-Prediction-ML

Install the required packages:

pip install -r requirements.txt

Launch Jupyter Notebook:

jupyter notebook

Open:

Breast_Cancer_Prediction.ipynb

and run all cells.

📊 Results

The models were compared using several evaluation metrics to identify the best-performing classifier for breast cancer survival prediction.

Visual outputs generated by the project include:

Correlation Heatmap
Pairplot
Histograms
Boxplots
Confusion Matrix
ROC Curve
Feature Importance
Model Comparison Chart

The best-performing model is automatically saved for future inference and deployment.

💾 Output Files

The project automatically saves:

Trained machine learning models (.pkl)
Performance metrics (.csv)
Feature importance tables
Classification reports (.txt)
Cross-validation results
Hyperparameter tuning results
ROC curves
Confusion matrices
Correlation heatmaps
Pairplots
Model comparison figures

🔮 Future Improvements

Possible enhancements include:

XGBoost implementation
LightGBM and CatBoost comparison
SHAP explainability
Learning curves
Precision–Recall analysis
Model calibration
Automated PDF/Word report generation
Streamlit web application for interactive predictions
Model deployment using Docker and cloud platforms

📚 Conclusion

This project demonstrates a complete supervised machine learning workflow for predicting breast cancer patient survival. It covers the full data science lifecycle—from data preprocessing and exploratory analysis to model development, evaluation, optimization, and interpretation. The project highlights how machine learning can support healthcare analytics and provides a reproducible framework for future clinical prediction tasks.

👨‍💻 Author

Your Dr Ghada Elfeki

Data Analyst | Machine Learning Enthusiast | Python Developer

📧 Email: gh_af_elfeki2004@yahoo.com

💼 LinkedIn: https://www.linkedin.com/ghada-elfeki-b5b6692a6

🐙 GitHub: https://github.com/GhadaElfeki77 

📊 Kaggle: https://www.kaggle.com/ghadaelfeki/breast-cancer-ml-project-gh


⭐ If you found this project useful, consider giving the repository a star on GitHub!
