# 🌍 GHG Emission Prediction using Machine Learning

This project focuses on predicting **Supply Chain Emission Factors with Margins** using Data Quality (DQ) metrics and other supply chain parameters. It includes a complete pipeline from **data preprocessing and model training to deployment via a Streamlit web application**.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that predicts supply chain greenhouse gas (GHG) emissions more accurately by considering:

- DQ reliability
- Temporal correlation
- Geographical and technological alignment
- Margin impacts on emission factors

---

## ⚙️ Technologies Used

- **Python**
- **pandas**, **NumPy**, **scikit-learn**
- **Matplotlib**, **Seaborn** (EDA & visualization)
- **Joblib** (for model saving/loading)
- **Streamlit** (for web app deployment)

---

## 📁 Project Structure

GHG_Emission_Prediction/
│
├── app.py # Streamlit web app
├── models/
│ └── LR_model.pkl # Trained Linear Regression model
│ └── scaler.pkl # StandardScaler object
├── utils/
│ └── preprocessor.py # Preprocessing functions
├── data/
│ └── emissions_data.xlsx # Input data file (not included due to size/privacy)
├── GHG_Emissions_Prediction.ipynb # Jupyter notebook (EDA, training, evaluation)
└── README.md


---

## 🧠 Machine Learning Model

- **Model Used**: Linear Regression
- **Target**: Supply Chain Emission Factor with Margin
- **Features**:
  - Substance, Unit, Source
  - Emission Factor without Margin
  - Margin
  - DQ Metrics: Reliability, Temporal, Geographical, Technological, Data Collection

---

## 🚀 Web App

The project includes a **Streamlit-based web interface** where users can:

- Select substance and source
- Input emission factors and DQ scores
- Get real-time predictions

📷 *Screenshot of the app:*

![App Screenshot](./screenshots/app.png)

---

## 📊 Results

- Model Evaluation:
  - **RMSE**: *~0.04*  
  - **R² Score**: *~0.89*  
- The model provides reliable predictions and is ready for further improvement or integration.

---

## 🔧 How to Run

1. Clone this repository  
2. Install required packages:  


