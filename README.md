# 🌸 Iris Flower Classification

This repository contains a complete machine learning pipeline to classify Iris flowers into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their petal and sepal measurements. The project is built using Python and scikit-learn, and includes data analysis, model training, evaluation, and feature importance.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository
- **Features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **Target**:
  - `species` (Setosa, Versicolor, Virginica)

---

## 📊 Exploratory Data Analysis (EDA)

- Checked for missing values and class balance
- Visualized feature relationships using **pairplots**
- Displayed correlations using **heatmap**

---

## ⚙️ Model Building

- Preprocessed labels using `LabelEncoder`
- Trained a **Random Forest Classifier**
- Split data into training and testing sets (80/20)
- Evaluated performance using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

---

## 🔍 Feature Importance

The Random Forest model outputs feature importances that help identify which measurements are most useful for classification. A bar chart is used to visualize this.

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Jupyter Notebook (for development)
- [Optional] Streamlit for dashboard

---

##📁 Project Structure
iris-flower-classification
│
├── IRIS.csv                      # Dataset
├── iris_flower_classification.py # Main Python script
├── app.py                        # (Optional) Streamlit app
├── README.md                     # Project documentation
└── requirements.txt              # List of dependencies
