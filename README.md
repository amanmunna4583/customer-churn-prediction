# 📉 Customer Churn Prediction Platform

Predict customer attrition before it happens using Machine Learning and interactive analytics.

## 🌟 Overview

Customer retention is significantly more cost-effective than customer acquisition. This project leverages Machine Learning to identify customers who are likely to discontinue a service, enabling businesses to take proactive retention measures.

Built with **XGBoost** and deployed through **Streamlit**, the application provides real-time churn predictions, risk assessment, and probability-based insights through an intuitive web interface.

### 🔗 Live Application

https://customer-churn-prediction17.streamlit.app

---

## 🎯 Problem Statement

Customer churn directly impacts revenue growth and customer lifetime value. Traditional methods often fail to detect churn risks early enough for effective intervention.

This project addresses that challenge by:

* Analyzing customer demographics and service usage patterns
* Predicting churn probability in real time
* Classifying customers into actionable risk categories
* Providing data-driven support for retention strategies

---

## 🚀 Key Features

### Intelligent Churn Prediction

* Real-time customer churn forecasting
* Probability-based predictions
* Risk-level categorization

### Interactive Analytics

* Dynamic prediction dashboard
* Visual probability distributions
* User-friendly input forms

### Production-Ready Design

* Lightweight deployment with Streamlit
* Fast inference performance
* Clean and responsive interface

---

## 🧠 Machine Learning Pipeline

### Model Architecture

* Algorithm: XGBoost Classifier
* Problem Type: Binary Classification
* Target Variable: Customer Churn (Yes / No)

### Data Processing

* Missing value handling
* Feature encoding
* Feature scaling
* SMOTE-based class balancing

### Model Performance

| Metric              | Score  |
| ------------------- | ------ |
| Accuracy            | ~77%   |
| Classification Type | Binary |
| Customer Records    | 7,000+ |
| Features Used       | 19     |

---

## 📊 Most Influential Features

The model identified the following variables as the strongest churn indicators:

1. Contract Type
2. Customer Tenure
3. Monthly Charges
4. Internet Service Type
5. Payment Method

These insights can help organizations focus retention efforts on high-risk customer segments.

---

## 🛠 Technology Stack

### Machine Learning

* XGBoost
* Scikit-Learn
* Imbalanced-Learn (SMOTE)

### Data Processing

* Pandas
* NumPy

### Visualization

* Plotly

### Deployment

* Streamlit

### Model Management

* Joblib

---

## ⚙️ Local Installation

### Clone Repository

```bash
git clone https://github.com/Sparkydev007/customer-churn-prediction.git
cd customer-churn-prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Application

```bash
streamlit run churn_app.py
```

Application will be available at:

```text
http://localhost:8501
```

---

## 📁 Project Structure

```text
customer-churn-prediction/
│
├── churn_app.py
├── customer_churn_model.pkl
├── churn_encoders.pkl
├── requirements.txt
├── screenshots/
└── README.md
```

---

## 💼 Business Applications

### Customer Retention

Identify at-risk customers before they leave.

### Marketing Optimization

Target retention campaigns toward high-value customers.

### Revenue Protection

Reduce customer attrition and increase lifetime value.

### Strategic Decision Making

Support business decisions using predictive analytics.

---

## 📈 Future Enhancements

* SHAP-based model explainability
* Feature importance dashboard
* Multi-model comparison framework
* Customer segmentation analysis
* Database integration
* User authentication and role management
* Automated prediction logging
* Real-time monitoring dashboard

---



Developed as a Machine Learning and Data Analytics project demonstrating practical implementation of predictive modeling, class imbalance handling, model deployment, and business-focused analytics.
