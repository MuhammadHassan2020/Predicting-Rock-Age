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
### **Feature Distribution**
The following plot represents the **distribution of geochemical features** in the dataset. This visualization helps in understanding data variability and detecting potential outliers.

![Feature Distribution](visualizations/Data_distribution_graph.png)

### **EMPA Correlation Matrix**
This heatmap shows the **correlation between different EMPA elements**, allowing us to identify highly correlated features that may impact model performance.

![EMPA Correlation Matrix](visualizations/empa_correlation_matrix.png)

### **Laser Ablation Correlation Matrix**
Similar to EMPA, this correlation matrix highlights relationships between Laser Ablation elements. High correlations indicate dependencies that can be considered during feature selection.

![Laser Ablation Correlation Matrix](visualizations/laser_ablation_correlation_matrix.png)

## 📈 Machine Learning & Data Analysis Models
### Models Tested
| **Model**                | **Accuracy** |
|-------------------------|------------|
| Random Forest           | **92%**    |
| Logistic Regression     | **78%**    |
| XGBoost                | **95%**    |
| Deep Learning (CNN)     | **97%**    |

### **Feature Importance - EMPA**
This bar chart showcases the **most important EMPA features** contributing to the prediction model.

![Feature Importance - EMPA](visualizations/feature_importance_empa.png)

### **Feature Importance - Laser Ablation**
This plot highlights the **top contributing features** from the Laser Ablation dataset used in model training.

![Feature Importance - Laser Ablation](visualizations/feature_importance_laser_ablation.png)

## 📌 Key Insights & Business Impact
- 🔹 **Laser Ablation data provides deeper insights** but introduces variability due to missing values.
- 🔹 **Feature selection improves predictive accuracy**, allowing better classification of rock age.
- 🔹 **Data visualization helps in trend identification**, which is crucial for geochemical studies.
- 🔹 **Machine learning models can enhance geological research**, improving efficiency in geochemical age classification.

## 📁 Project Structure



## 📌 Key Insights & Business Impact
- 🔹 **Laser Ablation data provides deeper insights** but introduces variability due to missing values.
- 🔹 **Feature selection improves predictive accuracy**, allowing better classification of rock age.
- 🔹 **Data visualization helps in trend identification**, which is crucial for geochemical studies.
- 🔹 **Machine learning models can enhance geological research**, improving efficiency in geochemical age classification.


## 📁 Project Structure
```bash
📂 Predict_Rock_Age
 ┣ 📜 README.md   # Project documentation
 ┣ 📂 data
 ┃ ┣ 📄 rock_geochemistry.csv  # Processed dataset
 ┣ 📂 notebooks
 ┃ ┣ 📄 analysis_notebook.ipynb  # Main Jupyter Notebook
 ┣ 📂 visualizations
 ┃ ┣ 📄 correlation_heatmap.png
 ┃ ┣ 📄 element_distribution_chart.png
 ┃ ┣ 📄 model_accuracy_chart.png
 ┣ 📂 models
 ┃ ┣ 📄 best_model.pkl  # Saved ML model

## 📎 How to Run This Project
1️⃣ **Clone the repository:**
```bash
git clone https://github.com/yourusername/Predict_Rock_Age.git

pip install -r requirements.txt

jupyter notebook analysis_notebook.ipynb 


##🔗 **Connect With Me**
💡 If you find this project useful, feel free to connect!
📩 Email: mhassan.abid2024@gmail.com
🔗 LinkedIn: [www.linkedin.com/in/m-hassan-abid]
