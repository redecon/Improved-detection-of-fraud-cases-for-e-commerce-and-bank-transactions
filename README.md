# Improved Detection of Fraud Cases for E-Commerce and Bank Transactions

##  Project Description
This project focuses on building robust pipelines to detect fraudulent transactions in e-commerce and banking datasets. It integrates geolocation, time-based feature engineering, and class imbalance handling to improve fraud detection accuracy.

##  Business Context
Fraudulent transactions cause significant financial losses and erode customer trust. By leveraging machine learning and advanced data preprocessing, this project aims to provide scalable solutions for fraud detection.

## ⚙️ Setup Instructions
```bash
git clone https://github.com/redecon/Improved-detection-of-fraud-cases-for-e-commerce-and-bank-transactions.git
cd Improved-detection-of-fraud-cases-for-e-commerce-and-bank-transactions
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

##  Repository Structure
fraud-detection/
│
├── data/
│   ├── raw/              # Original datasets (excluded via .gitignore)
│   ├── processed/        # Engineered datasets (excluded via .gitignore)
│
├── notebooks/            # Jupyter notebooks for exploration
│   ├── 01_data_cleaning.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_modeling.ipynb
│
├── src/                  # Source code
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── pipelines.py
│   └── imbalance.py
│
├── tests/                # Unit tests
│
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE
