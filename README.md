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
<img width="1919" height="1092" alt="Screenshot 2025-12-13 232600" src="https://github.com/user-attachments/assets/13dfed53-1b03-467a-a461-e81e582c8442" />

<img width="1919" height="1083" alt="Screenshot 2025-12-13 233033" src="https://github.com/user-attachments/assets/2f1a403b-e8eb-45fa-9de8-13a17f29dd48" />

<img width="1919" height="1088" alt="Screenshot 2025-12-13 233209" src="https://github.com/user-attachments/assets/264b4dec-de05-47cf-bcf9-084415b4c0ed" />

<img width="1919" height="1086" alt="Screenshot 2025-12-13 233911" src="https://github.com/user-attachments/assets/88c415c0-ccb2-47bc-943b-d0f90b039681" />


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
