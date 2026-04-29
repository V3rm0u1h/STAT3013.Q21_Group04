# Statistical and Machine Learning Analysis of Consumer Responses to Promotions and Discounts
## STAT3013.Q21 - Group 04

---

### 🔗 Project Resources
* **Presentation Video:** [(https://drive.google.com/drive/folders/12iACTTKJFjdqZ5FNYHfS39apPBIVNQb1)]

---

### 📖 Project Overview
Dự án tập trung vào việc phân tích hành vi người tiêu dùng đối với các chương trình khuyến mãi thông qua các kỹ thuật thống kê và học máy. Dự án sử dụng mô hình RFM (Recency, Frequency, Monetary) kết hợp với thuật toán phân cụm **DP-Means** để phân loại khách hàng, từ đó đưa ra các chiến lược marketing phù hợp.

---
## Structure
```
STAT3013.Q21_Group04/
├── report/ # final report
├── assets/                  
│   └── images/  
├── data/                                      
├── data_engineering/
│   ├── data_cleaning.ipynb
│   └── outlier_detection.ipynb
│
├── descriptive & RFM/
│   ├── rfm_calculation.ipynb
│   ├── coupon_tenure.ipynb
│   └── eda.ipynb
│
├── inferential/
│   ├── ttest_anova.ipynb
│   └── chi_square.ipynb
│
├── clustering/
│   ├── kmeans.ipynb
│   ├── dpmeans.ipynb
│   └── validation.ipynb
│
├── regression/
│   └── lasso_regression.ipynb
│
├── machine_learning/                 
├── .gitignore             
├── requirements.txt       
└── README.md
```

##Setup & Installation

1. Environment Requirements
Python version 3.9 or higher is required.

Main Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy.

2. Install Dependencies
It is recommended to use a virtual environment. Install the required Python libraries using pip:

Bash

pip install -r requirements.txt

3. How to Run
The analysis is organized into Jupyter Notebooks for a step-by-step workflow. To view and run the code:

Launch Jupyter Notebook, JupyterLab, or open the project in VS Code.

Navigate to the Notebooks/ directory (or your specific analysis folders like clustering/, inferential/, etc.).

Open the desired .ipynb file and run the cells sequentially to see the data processing, statistical tests, and machine learning results.
```
