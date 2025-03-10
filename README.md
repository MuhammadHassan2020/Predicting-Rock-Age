# 📊 Predicting Rock Age Using Data Analysis & Machine Learning

## Overview
This project focuses on analyzing geochemical data from volcanic rock samples to predict rock age using **data analysis techniques and machine learning models**. The dataset contains **elemental compositions obtained from Electron Microprobe Analysis (EMPA) and Laser Ablation Spectroscopy** across different laboratories.

## Features
- **Data Cleaning & Preprocessing** – Handling missing values, normalizing data, and structuring datasets.
- **Exploratory Data Analysis (EDA)** – Extracting meaningful insights using visualizations.
- **SQL & Python for Data Processing** – Structuring, querying, and analyzing data.
- **Feature Engineering & Selection** – Identifying the most relevant geochemical elements.
- **Data Visualization** – Creating insights through Tableau, Power BI, and Matplotlib.
- **Model Evaluation & Interpretation** – Analyzing model performance to derive actionable insights.

## 📂 Dataset Overview
The dataset contains elemental compositions of volcanic rocks analyzed in different laboratories. The dataset is divided into:

- **EMPA Elements:** (NiO, F, CaO, SiO₂, Cr₂O₃, Na₂O, TiO₂, etc.)
- **Laser Ablation Elements:** (Mg#, Li, Be, B, Sc, Ti, V, Cr, Mn, Co, Ni, etc.)

### Key Data Analyst Tasks Performed
- ✔ Identified and handled missing values in **Laser Ablation data** using KNN Imputer.
- ✔ Standardized features to ensure uniform data scaling.
- ✔ Used SQL to filter and preprocess rock element concentrations.
- ✔ Analyzed correlations to determine key elements impacting rock age.

## 📊 Exploratory Data Analysis (EDA) & Visualizations
### Visualizations Used
1. **Feature Correlation Heatmap** – Identifies the most influential chemical elements.
2. **Element Distribution Bar Chart** – Compares element compositions across different labs.
3. **Scatter Plot (MgO vs FeO)** – Shows relationships between major elements.
4. **Pie Chart** – Displays the proportion of missing values for each element.
5. **Model Accuracy Comparison** – Evaluates different machine learning models.

### 📌 Visualization Sample Code
```python
import seaborn as sns
import matplotlib.pyplot as plt

plt.figure(figsize=(12, 8))
sns.heatmap(data.corr(), cmap="coolwarm", annot=False, linewidths=0.5)
plt.title("Feature Correlation Heatmap")
plt.show()
