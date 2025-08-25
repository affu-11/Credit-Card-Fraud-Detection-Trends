# Credit-Card-Fraud-Detection-Trends
This project focuses on detecting fraudulent credit card transactions using the Kaggle Credit Card Fraud Dataset, which consists of 284,807 transactions made by European cardholders in 2013. The dataset is highly imbalanced, with only 492 fraud cases (0.17%), making fraud detection a challenging task.

##  Project Overview
This project focuses on detecting fraudulent credit card transactions using the **Kaggle Credit Card Fraud Dataset**.  
The dataset contains **284,807 transactions** with only **492 fraud cases (0.17%)**, making it a highly imbalanced dataset.  
The goal of this project is to explore fraud transaction patterns, visualize class imbalance, and build a machine learning model that can identify fraud effectively.  

##  Objectives
- Perform **Exploratory Data Analysis (EDA)** on credit card transaction data.  
- Visualize **class imbalance** between fraud and non-fraud cases.  
- Compare transaction **amounts** for fraud vs. normal transactions.  
- Train a **Random Forest Classifier** to detect fraud.  
- Evaluate model performance using **ROC-AUC, Precision, Recall, and F1-score**.  
- Plot **confusion matrix** and **precision-recall curve** for better understanding.  

## Dataset
 **Source:** [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)  
 **Rows:** 284,807  
 **Fraud Cases:** 492 (~0.17%)  
 **Features:**  
    `Time`, `Amount`, 28 anonymized PCA features (`V1`–`V28`)  
    Class` (Target: 0 = Normal, 1 = Fraud)  

## Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, scikit-learn  

##  Steps in the Project
1. Load and explore the dataset.  
2. Perform EDA:
   - Check class imbalance.  
   - Compare transaction amounts.  
   - Plot histograms and distributions.  
3. Split dataset into train and test sets.  
4. Train a **Random Forest Classifier** with `class_weight='balanced'`.  
5. Make predictions on the test set.  
6. Evaluate using:
   - ROC-AUC score  
   - Classification Report  
   - Confusion Matrix  
   - Precision-Recall Curve  
7. Analyze feature importance.  

##  Results
- Fraud cases are extremely rare compared to normal cases.  
- Fraud transaction amounts show different spending patterns.  
- Random Forest achieved good **Recall** on fraud class, meaning it was able to catch many frauds.  
- Trade-off exists between **Precision and Recall**, which is expected in fraud detection.  


## ✅ Conclusion
This project demonstrates how **machine learning** can be used to detect fraud in highly imbalanced datasets.  
Random Forest provided a good balance between recall and precision, making it a suitable choice for **financial fraud detection*

