# SCM 
**Supply Chain Analytics & Late Delivery Risk Prediction Dashboard**

A comprehensive **Supply Chain Management (SCM) analytics application** built using **Streamlit** and **Machine Learning**, designed to analyze supply chain performance and predict **late delivery risks** for single and multiple products through an interactive dashboard and AI-powered chatbot.

---

## Overview

This project applies **data analytics and predictive modeling** to real-world supply chain problems. It enables users to explore operational data, evaluate multiple machine learning models, and make informed logistics decisions using predictive insights.

Suitable for:
- Academic projects  
- Data science portfolios  
- Applied machine learning demonstrations  
- Supply chain analytics use cases  

---

## Features

### Dashboard & Analytics
- Single Product Analysis with feature importance
- Multi Product Correlation Analysis
- Interactive visualizations
- Model performance comparison

### Machine Learning Models
- Logistic Regression  
- Random Forest  
- Decision Tree  
- XGBoost  

### Prediction System
- Late delivery risk prediction
- Supports:
  - Single product prediction
  - Multi-product, multi-department prediction
- Dynamic input mapping using JSON dictionaries
- Real-time inference with accuracy reporting

### SCM Chatbot (Jarvis)
- Integrated conversational assistant
- Helps users query supply chain–related information

---
<img width="975" height="553" alt="image" src="https://github.com/user-attachments/assets/fe231709-a9ce-45a8-84f8-f5aadae3d7ff" />

<img width="975" height="550" alt="image" src="https://github.com/user-attachments/assets/4972d62b-1058-4be0-b0ca-fbff960f3760" />

<img width="975" height="552" alt="image" src="https://github.com/user-attachments/assets/124e0d1e-df55-4f17-b680-edd57cb58ed9" />




## Tech Stack

- **Language:** Python 3.8+
- **Framework:** Streamlit
- **Data Processing:** Pandas, NumPy
- **Visualization:** Plotly
- **Machine Learning:** Scikit-learn, XGBoost

---

## Project Structure

```
SCM-Demo/
│
├── Data/
│   ├── cleaned_data.csv
│   ├── Dataset.csv
│   ├── dictionary.json
│   ├── dictionary1.json
│   └── dictionary2.json
│
├── Developement/
│   ├── Main.py
│   └── SBMBOT/
│       └── queries_page.py
│
├── Analysis/
│   └── (EDA and experimentation notebooks)
│
├── requirements.txt
└── README.md
```

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone <your-repository-url>
cd SCM-Demo
```

### 2. Create a Virtual Environment (Recommended)
```bash
python -m venv venv
source venv/bin/activate
# Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
cd Developement
streamlit run Main.py
```

The application will be available at:
```
http://localhost:8501
```

---

## Application Modules

### Home
- Landing page with SCM-themed UI

### Dashboard
- **Single Product**
  - Feature importance
  - Classification report
- **Multi Product**
  - Correlation heatmap
  - Model accuracy comparison

### Prediction
- Predicts `Late_delivery_risk`
- Uses real-world SCM inputs:
  - Shipping mode
  - Order status
  - Product price & quantity
  - Scheduling delays
- Displays prediction results clearly

### Jarvis (SCM Bot)
- Interactive chatbot for SCM-related queries

---

## Machine Learning Objective

**Target Variable:**  
`Late_delivery_risk`

**Goal:**  
Classify whether an order is likely to experience delayed delivery based on logistics and operational attributes.

---

## Use Cases

- Supply chain risk analysis
- Logistics performance monitoring
- Academic ML projects
- Data science portfolio showcase

---

## Future Enhancements

- Model persistence (joblib / pickle)
- Cloud deployment (AWS / Azure)
- Real-time data ingestion
- Role-based access control
- Advanced NLP chatbot capabilities

---


Machine Learning | Analytics | Streamlit Applications  
