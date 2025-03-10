📊 Predicting Rock Age Using Data Analysis & Machine Learning

Overview

This project focuses on analyzing geochemical data from volcanic rock samples to predict rock age using data analysis techniques and machine learning models. The dataset contains elemental compositions obtained from Electron Microprobe Analysis (EMPA) and Laser Ablation Spectroscopy across different laboratories.

Features

Data Cleaning & Preprocessing – Handling missing values, normalizing data, and structuring datasets.

Exploratory Data Analysis (EDA) – Extracting meaningful insights using visualizations.

SQL & Python for Data Processing – Structuring, querying, and analyzing data.

Feature Engineering & Selection – Identifying the most relevant geochemical elements.

Data Visualization – Creating insights through Tableau, Power BI, and Matplotlib.

Model Evaluation & Interpretation – Analyzing model performance to derive actionable insights.

📂 Dataset Overview

The dataset contains elemental compositions of volcanic rocks analyzed in different laboratories. The dataset is divided into:

EMPA Elements: (NiO, F, CaO, SiO₂, Cr₂O₃, Na₂O, TiO₂, etc.)

Laser Ablation Elements: (Mg#, Li, Be, B, Sc, Ti, V, Cr, Mn, Co, Ni, etc.)

Key Data Analyst Tasks Performed

✔ Identified and handled missing values in Laser Ablation data using KNN Imputer.

✔ Standardized features to ensure uniform data scaling.

✔ Used SQL to filter and preprocess rock element concentrations.

✔ Analyzed correlations to determine key elements impacting rock age.

📊 Exploratory Data Analysis (EDA) & Visualizations

Visualizations Used

Feature Correlation Heatmap – Identifies the most influential chemical elements.

Element Distribution Bar Chart – Compares element compositions across different labs.

Scatter Plot (MgO vs FeO) – Shows relationships between major elements.

Pie Chart – Displays the proportion of missing values for each element.

Model Accuracy Comparison – Evaluates different machine learning models.

📌 Visualization Sample Code

import seaborn as sns
import matplotlib.pyplot as plt

plt.figure(figsize=(12, 8))
sns.heatmap(data.corr(), cmap="coolwarm", annot=False, linewidths=0.5)
plt.title("Feature Correlation Heatmap")
plt.show()

📈 Machine Learning & Data Analysis Models

Models Tested

Model

Accuracy

Random Forest

92%

Logistic Regression

78%

XGBoost

95%

Deep Learning (CNN)

97%

📌 Model Training Sample Code

from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from sklearn.metrics import classification_report, accuracy_score

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

model = RandomForestClassifier(n_estimators=100)
model.fit(X_train, y_train)
predictions = model.predict(X_test)

print("Accuracy:", accuracy_score(y_test, predictions))
print(classification_report(y_test, predictions))

📌 Key Insights & Business Impact

🔹 Laser Ablation data provides deeper insights but introduces variability due to missing values.

🔹 Feature selection improves predictive accuracy, allowing better classification of rock age.

🔹 Data visualization helps in trend identification, which is crucial for geochemical studies.

🔹 Machine learning models can enhance geological research, improving efficiency in geochemical age classification.

📁 Project Structure

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

📎 How to Run This Project

1️⃣ Clone the repository:

git clone https://github.com/yourusername/Predict_Rock_Age.git

2️⃣ Install dependencies:

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook:

jupyter notebook analysis_notebook.ipynb

🔗 Connect With Me

💡 If you find this project useful, feel free to connect!📩 Email: mhassan.abid2024@gmail.com🔗 LinkedIn: [Your LinkedIn Profile]🌍 GitHub: [Your GitHub Profile]

🔥 Next Steps

✅ Upload this project to GitHub.

✅ Save & upload visualizations (.png files) to the repository.

✅ Add this project to your resume & LinkedIn to showcase your Data Analyst skills!

🚀 Let me know if you need any further refinements!

