# 🧠 Predicting Stroke Risk from Lifestyle and Health Factors

## 📌 Project Overview

This project explores the use of a neural network to predict stroke risk based on easily monitored health and lifestyle indicators. The dataset includes features such as BMI, average glucose level, history of heart disease, hypertension, smoking status, and work/residence type.

The goal is to build a predictive model that can help identify individuals at higher risk of stroke using accessible clinical and demographic information — potentially supporting early screening and preventive interventions.

---

## 🎯 Problem Statement

Stroke is a leading cause of death and disability worldwide. Early identification of individuals at risk is crucial for timely intervention. In this project, we aim to develop a predictive model using factors that are:
- Easy to monitor or self-report
- Widely available in primary care or public health settings

---

## 🛠️ Methods

We use a **feedforward neural network** with one hidden layer to perform binary classification (stroke vs no stroke). 

To support data exploration and preprocessing, we also incorporate:
- **SQL (SQLite)** for data inspection, validation, and filtering
- **Quarto/R** for exploratory data analysis and visualization
- **Jupyter Notebooks** for model development and evaluation

We additionally use **permutation feature importance** to interpret which variables most strongly influence stroke risk predictions.

---

## 📂 Project Components

| File/Folder         | Description |
|---------------------|-------------|
| `notebooks/`        | Jupyter notebooks for model training and evaluation |
| `sql/`              | SQL scripts used to inspect and clean the data |
| `report/`           | Quarto or R Markdown documents summarizing findings |
| `data/`             | Raw and cleaned versions of the stroke dataset |
| `models/`           | (Optional) Saved neural network model files |
| `README.md`         | Project overview and navigation |
| `requirements.txt`  | Python dependencies used in modeling |

---

## 📈 Expected Outputs

- A Jupyter notebook demonstrating neural network training and model evaluation
- SQL queries for initial data validation and cleaning
- R/Quarto documents conducting exploratory data analysis and visualization
- A list of key features most associated with increased or reduced stroke risk
- Model evaluation metrics: **precision**, **recall**, **F1 score**, **ROC AUC**, and **PR AUC**

---

## 📊 Dataset

The dataset includes demographic and clinical information for 5,110 individuals:
- Age, Gender
- BMI, Average Glucose Level
- Hypertension, Heart Disease
- Smoking Status, Marital Status, Work Type
- Stroke (binary outcome variable)

*Source: Confidential educational dataset (use for academic purposes only).*

---

## ✅ Project Status

- [ ] Data inspection and SQL queries
- [ ] Data cleaning and preprocessing
- [ ] Exploratory data analysis (R/Quarto)
- [ ] Neural network training and testing
- [ ] Final report write-up

---

## 👥 Team

- **[Your Name]** — Data Cleaning, Building the Github repo, EDA, Documentation
- **[Partner's Name]** — Model Building (Neural Network), Evaluation

---

