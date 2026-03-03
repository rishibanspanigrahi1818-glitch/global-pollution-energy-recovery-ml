# 🌍 Global Pollution Analysis and Energy Recovery using Machine Learning

## 📌 Project Overview

Environmental pollution is one of the most critical global challenges in modern society.  
This project applies **Machine Learning classification techniques** to categorize countries into:

- **Low Pollution**
- **Medium Pollution**
- **High Pollution**

The objective is to analyze environmental indicators and generate **data-driven insights** that can support pollution control policies and energy recovery strategies.

---

## 🎯 Project Objectives

- Perform data preprocessing and cleaning
- Engineer meaningful environmental features
- Classify pollution severity using ML algorithms
- Compare model performances
- Generate actionable environmental insights

---

## 📊 Dataset Description

The dataset includes the following features:

- Air Pollution Index  
- Water Pollution Index  
- Soil Pollution Index  
- Industrial Waste (in tons)  
- CO₂ Emissions (in MT)  
- Renewable Energy (%)  
- Energy Recovered (in GWh)  
- Energy Consumption per Capita (in MWh)  
- Population (in millions)  
- GDP per Capita (in USD)  

A combined **Pollution Score** is calculated to derive pollution severity categories.

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing
- Missing value handling
- Feature scaling using StandardScaler
- Label encoding of categorical variables
- Creation of Pollution Severity target variable

### 2️⃣ Feature Engineering
- Combined Pollution Score
- Energy Efficiency metric

### 3️⃣ Machine Learning Models
The following classifiers were implemented:

- **Naive Bayes**
- **K-Nearest Neighbors (KNN)** (with hyperparameter tuning)
- **Decision Tree** (with hyperparameter tuning)

### 4️⃣ Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📈 Visualizations Included

- Pollution index distributions
- Correlation heatmap
- Pollution level distribution
- Energy recovery vs pollution analysis
- Model performance comparison graph
- Confusion matrices
- Feature importance (Decision Tree)

---

## 📊 Model Performance Comparison

Performance metrics were compared across all models to determine the most reliable classifier.

Rather than relying only on accuracy, a full performance evaluation was conducted using precision, recall, and F1-score to ensure balanced model assessment.

---

## 🧠 Key Insights

- Higher CO₂ emissions and industrial waste strongly correlate with high pollution levels.
- Renewable energy percentage shows a negative correlation with pollution severity.
- Decision Tree and KNN models performed competitively after hyperparameter tuning.
- Data-driven classification can assist policymakers in prioritizing environmental interventions.

---

## 🚀 How to Run the Project

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/Global-Pollution-Analysis-ML.git
cd Global-Pollution-Analysis-ML
