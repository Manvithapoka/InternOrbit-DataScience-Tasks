# 💳 Credit Card Fraud Detection – Level 2 Task 1

This project is part of the **InternOrbit Data Science Internship (Level 2 Task 1)**. It focuses on building a machine learning model to detect fraudulent credit card transactions and visualizing the model results using **Power BI**.

---

## 📌 Project Objective

To detect fraudulent transactions using supervised machine learning techniques and display the outcomes through an interactive Power BI dashboard.

---

## 📊 Dataset

- The dataset contains anonymized credit card transactions made by European cardholders in September 2013.
- Features include 28 anonymized principal components (`V1` to `V28`), `Time`, `Amount`, and `Class` (target: 1 for fraud, 0 for genuine).

---

## 🧠 Steps Involved

### 🧪 Model Building (Python):
- Preprocessed the dataset and handled class imbalance using oversampling
- Trained classification models like:
  - Logistic Regression
  - Random Forest
- Evaluated performance using:
  - Confusion Matrix
  - Accuracy
  - Precision, Recall, F1-score

### 📈 Visualization (Power BI):
- Imported final model predictions into Power BI
- Created an interactive dashboard with:
  - Donut chart (Fraud vs Genuine)
  - Column chart (Correct vs Wrong Predictions)
  - Stacked chart (Actual vs Predicted)
  - Slicers for Result filtering
  - Table with conditional formatting

---

## 🛠️ Tools Used

- Python (Jupyter Notebook)
- Scikit-learn, Pandas, Numpy, Matplotlib
- Power BI

---

## 📌 Outcome

A machine learning pipeline capable of detecting fraud and a business-ready dashboard to present predictions in a clean, interactive format.
