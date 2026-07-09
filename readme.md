# Financial Risk Intelligence Platform (FRIP)
![FRIP Banner](images/banner_frip.svg)

## Overview

Financial Risk Intelligence Platform (FRIP) is an end-to-end Data Analytics and Machine Learning project focused on credit risk assessment.

The goal is to simulate how a modern financial institution can leverage data to support credit approval decisions, reduce default risk, and generate business insights.

This project is being developed as a production-oriented portfolio, following software engineering and data science best practices.

---

## Objectives

- Predict customer default risk  
- Analyze customer profiles  
- Generate business insights  
- Build explainable machine learning models  
- Create interactive dashboards  
- Simulate a real financial analytics project  
- Follow a real-world ML pipeline from raw data to explainability  

---

## Tech Stack

### **Languages & Libraries**
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- SHAP  
- Matplotlib / Seaborn  

### **Machine Learning**
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- HistGradientBoosting (LightGBM alternative)  

### **Data & Storage**
- PostgreSQL (planned)  

### **Deployment & Tools**
- Streamlit (planned dashboard)  
- Docker (planned containerization)  
- Git & GitHub  

---

## Project Status

- [x] Project Initialization  
- [x] Data Collection  
- [x] Exploratory Data Analysis  
- [x] Feature Engineering  
- [x] Machine Learning  
- [x] Explainable AI (SHAP)  
- [ ] Business Understanding Document  
- [ ] Dashboard  
- [ ] Deployment  
- [ ] Executive Report (Notebook 06)  

---

## Repository Structure

data/
raw/            # Original datasets (ignored by Git)
processed/      # Cleaned and feature-engineered datasets

docs/               # Documentation, business notes, diagrams
images/             # Project images, banners, plots
notebooks/          # Jupyter notebooks (1 to 5 completed)
reports/            # Executive summaries, SHAP insights
src/                # Python modules (ETL, modeling, utils)
tests/              # Unit tests (future)
dashboard/          # Streamlit app (future)

Code

---

## Notebooks Overview

### **01 — Data Ingestion**
Loading raw data, initial checks, schema validation.

### **02 — Exploratory Data Analysis**
Distribution analysis, correlations, financial behavior insights.

### **03 — Feature Engineering**
Creation of credit risk features:
- Financial ratios  
- Employment stability  
- Social circle risk  
- Household structure  
- Document flags  

### **04 — Modeling**
Baseline and advanced models:
- Logistic Regression  
- Random Forest  
- Gradient Boosting  
- HistGradientBoosting  

Metrics:
- AUC  
- ROC Curve  

### **05 — Explainability**
SHAP global and local explanations:
- Summary plot  
- Feature importance  
- Waterfall plot for individual customers  

---

## Roadmap

- Add business KPIs (approval rate, loss rate, risk buckets)  
- Build Streamlit dashboard  
- Add FastAPI endpoint for model scoring  
- Create Docker image  
- Write executive report (Notebook 06)  
- Deploy dashboard online  

---

## Author

**Paulo Henrique Tamboril**  
Data Analytics | Financial Analytics | Machine Learning

---