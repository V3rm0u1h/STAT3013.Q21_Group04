# Statistical and Machine Learning Analysis of Consumer Responses to Promotions and Discounts
## STAT3013.Q21 - Group 04

---

### 🔗 Project Resources
* **Presentation Video:** https://drive.google.com/drive/folders/12iACTTKJFjdqZ5FNYHfS39apPBIVNQb1
*  **dataset 1:** “Marketing Insights for E-Commerce Company.” Accessed: Apr. 28, 2026. [Online]. Available: 
https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company
* **dataset 2:** “Ecommerce Customer Churn Analysis and Prediction.” Accessed: Apr. 28, 2026. [Online]. 
Available: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction

---

### 📖 Project Overview
The goals of the study can be formulated as follows:
- Measuring the efficiency of coupons: Understanding the link between coupons and such loyalty
related characteristics as frequency of purchases and cashback.
- Modeling the churn risk: Building a machine learning model that will reveal the correlation between 
extensive coupon usage and increased churn after the end of the promotion period.
-  Analyzing the impact of satisfaction: Revealing the influence of satisfaction on the impact of coupons 
on customer loyalty
---
## Structure
```
STAT3013.Q21_Group04/
├── report/ # full report, IEEE report, AI-generation Check Screenshot, AI Use Explanation
├── assets/                  
│   └── images/  
├── data/
│   ├── cleaned_data
│   ├── processed
│   └── raw                                    
├── data_engineering/ # preprocessing and imputation
├── descriptive & RFM/ # RFM, enrich feature and EDA
├── DPmeans/
├── Lasso_algorithm/
├── lightgbm&cataboost/                 
├── .gitignore             
├── requirements.txt       
└── README.md
```

## Setup & Installation

1. Requirements
- Python 3.8+
- Cython
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- scikit-learn
- xgboost
- lightgbm
- catboost
- optuna
- shap
2. Install Dependencies
It is recommended to use a virtual environment. 

```python -m venv .venv```

Windows:
```
.venv\Scripts\activate
```

Mac/Linux:
```
source .venv/bin/activate
```
3. Install the required Python libraries using pip:

`pip install -r requirements.txt`

3. How to Run
The analysis is organized into Jupyter Notebooks for a step-by-step workflow. To view and run the code:

Launch Jupyter Notebook, JupyterLab, or open the project in VS Code.

Navigate to the Notebooks/ directory (or your specific analysis folders like clustering/, inferential/, etc.).

Open the desired .ipynb file and run the cells sequentially to see the data processing, statistical tests, and machine learning results.

