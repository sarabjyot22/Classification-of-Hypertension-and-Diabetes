# 📌 Classification of Hypertension and Diabetes

## 📖 Overview
This project focuses on classifying hypertension and diabetes based on various health and lifestyle factors. The dataset includes demographic information, lifestyle habits, and medical history to train machine learning models for predictive analysis.

## 📊 Dataset Description

The dataset contains the following key features:

**Age** – 13-level age category (_AGEG5YR)

**Sex** – 0 = Female, 1 = Male

**HighChol** – 0 = No high cholesterol, 1 = High cholesterol

**CholCheck** – 0 = No cholesterol check in 5 years, 1 = Yes cholesterol check in 5 years

**BMI** – Body Mass Index

**Smoker** – 0 = No, 1 = Yes

**HeartDisease** – 0 = No, 1 = Yes

**PhysActivity** – 0 = No, 1 = Yes

**Fruits** – 0 = No, 1 = Yes

**Veggies** – 0 = No, 1 = Yes

**HvyAlcoholConsumption** – 0 = No, 1 = Yes

**GenHlth** – Self-reported health status (1-5 scale)

**Diabetes** – 0 = No, 1 = Diabetes

**Hypertension** – 0 = No, 1 = Hypertension

## ⚙️ Installation

To install the required dependencies, run:
```sh
pip install -r requirements.txt
```
## 🚀 Usage

- 1️⃣ Load the dataset – Ensure the dataset is available in the data/ directory.
- 2️⃣ Run the Jupyter Notebook – Open and execute:
```sh
jupyter notebook Classification-of-hypertension-and-diabetes.ipynb
```
- 3️⃣ Train Models – The notebook trains machine learning models for classification.
- 4️⃣ Evaluate Results – Model performance is assessed using accuracy, precision, recall, and F1-score.

## 🛠 Project Structure

📁 Classification Project
- ├── 📜 Classification-of-hypertension-and-diabetes.ipynb  # Jupyter Notebook
- ├── 📊 data.csv                                           # Dataset
- ├── 📦 requirements.txt                                   # Dependencies
- ├── 📘 README.md                                         # Project Documentation


## 📌 Notes

- 📌 The dataset is preprocessed to handle missing values and categorical variables.
- 📌 Models include Logistic Regression, Decision Trees, and Random Forest.
- 📌 Feature importance is analyzed to understand key health indicators.

## 🤝 Contributing

Contributions are welcome to improve model performance and data analysis! 🚀
