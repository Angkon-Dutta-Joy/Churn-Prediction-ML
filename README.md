# Customer Churn Prediction using Machine Learning

This repository contains a machine learning project aimed at predicting customer churn using various ML models. The project involves data preprocessing, model training, evaluation, and visualization of churn trends.

## 📌 Features
- Data preprocessing and feature engineering (handling missing values, label encoding, feature scaling, etc.)
- Training multiple ML models for churn prediction
- Model evaluation using accuracy, confusion matrix, and classification report
- Exploratory Data Analysis (EDA) with visualizations
- Addressing class imbalance using class weighting
- Hyperparameter tuning using RandomizedSearchCV

## 📂 Project Structure
```
- `notebooks/` → Jupyter notebooks for model training and evaluation  
- `data/` → Dataset (WA_Fn-UseC_-Telco-Customer-Churn.csv)  
- `models/` → Trained models stored using Pickle  
- `requirements.txt` → Dependencies  
- `README.md` → Project documentation  
```

## 📊 Models Used
- Logistic Regression
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes

## 🔧 Installation & Usage
1. Clone this repository:  
   ```sh
   git clone https://github.com/Angkon-Dutta-Joy/Churn-Prediction-ML.git
   ```
2. Open the notebook and execute the cells to train and evaluate models.

## 📈 Results
- Dataset: 7,043 rows and 21 columns, including 17 categorical and 4 numerical features.
- Model performance comparison:
  - **Logistic Regression**: 80.45% accuracy (Best-performing model)
  - **Random Forest**: 79.70% accuracy
  - **SVM**: 79.27% accuracy
  - **Decision Tree**: 78.18% accuracy
  - **KNN**: 77.99% accuracy
  - **Naive Bayes**: 74.78% accuracy
- Key factors influencing churn: Tenure, contract type, and monthly charges.
- Class imbalance handled using class weighting.
- StandardScaler used for feature scaling.

## 🚀 Future Enhancements
- Implement ensemble models for better performance.
- Explore customer sentiment data for better predictions.
- Optimize hyperparameters further for improved accuracy.

## 🤝 Contributing
Feel free to contribute by forking the repository and submitting pull requests.

## 📜 License
This project is licensed under the MIT License.

