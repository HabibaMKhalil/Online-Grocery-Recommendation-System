# Online Grocery Recommendation System

This project focuses on building a machine learning-based recommendation system for online grocery shopping. 
The system predicts whether a user will reorder a specific product based on their past purchase history. 
Three models—K-Nearest Neighbors (KNN), Decision Tree, and Logistic Regression—were evaluated, with Logistic Regression emerging as the top performer.
The project includes data preprocessing, feature engineering, model training, and performance evaluation using metrics like accuracy, precision, recall, and AUC-ROC. 
The goal is to enhance user experience by providing personalized grocery recommendations.

## 🚀 Project Overview

![ROC](https://github.com/user-attachments/assets/092697d2-afc7-45b6-aaba-bda3fa846e9c)

A machine learning system that predicts whether customers will reorder grocery items based on their purchase history. Built for the Instacart Market Basket Analysis challenge, this project compares three classification models to deliver personalized recommendations.

## 📊 Key Features

- **Data Processing**: Cleaned and engineered features from user order history
- **Model Comparison**: Evaluated KNN, Decision Tree, and Logistic Regression
- **Performance Metrics**: Accuracy, Precision, Recall, and AUC-ROC analysis
- **Optimal Model**: Logistic Regression achieved best balance (AUC-ROC: 0.70)

## 🏆 Results Summary
![Accuracy of Models](https://github.com/user-attachments/assets/f8d18b73-3232-46bb-8871-0c1f2250ed5a)

| Model            | Accuracy | Precision | Recall | AUC-ROC |
|------------------|----------|-----------|--------|---------|
| KNN              | 0.66     | 0.70      | 0.76   | 0.69    |
| Decision Tree    | 0.66     | 0.71      | 0.71   | 0.65    |
| Logistic Regression | 0.66  | 0.70      | 0.75   | 0.70    |

## 🛠️ Technical Implementation

**Dataset**: Instacart Market Basket Analysis (Kaggle)  
**Core Features**:
- User behavior metrics (total orders, reorder ratio)
- Product statistics (total orders, reorder frequency)
- Temporal features (order day/time, days since last order)

**Tech Stack**:
- Python 3
- Scikit-learn
- Pandas/Numpy
- Matplotlib/Seaborn

## 📂 Repository Structure

├── data/ # Processed datasets                                                                       
├── notebooks/ # Jupyter notebooks                                                                    
│ ├── 1_data_cleaning.ipynb                                                   
│ ├── 2_feature_engineering.ipynb                                                             
│ └── 3_model_training.ipynb                                                    
├── models/ # Saved models                                     
├── reports/ # Final report                                                             
└── README.md                                                   


## 💻 Getting Started

1. Clone repo:
  ```bash
  git clone https://github.com/your-username/Online-Grocery-Recommendation-System.git
  ```
2.Install requirements:
  ```bash
  pip install -r requirements.txt
  ```
3. Download dataset to /data


## 📈 Future Improvements

- Implement XGBoost for better performance
- Add real-time API deployment
- Incorporate NLP for product descriptions
