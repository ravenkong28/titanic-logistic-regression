# 🚢 Titanic Classification using Logistic Regression

This project is part of a **Machine Learning** course assignment during my **Master's Degree in Information Technology**, submitted on **March 24, 2025**. The goal was to predict the survival of Titanic passengers using **Logistic Regression**, with implementations in both **RapidMiner** and **Python (scikit-learn)** for performance comparison.

---

## 📌 Overview
This project evaluates the effectiveness of **Logistic Regression** in classifying Titanic passenger survival. The workflow involved preprocessing, feature engineering, training the model, and visualizing performance metrics using two platforms: GUI-based **RapidMiner** and code-based **Python**.

---

## 🎯 Objective
To compare model performance and flexibility between a GUI-based platform (**RapidMiner**) and code-based tools (**Python**).

---

## 📊 Dataset
- **Total Samples**: 1309 passengers
- **Target**: `Survived` (Yes/No)
- **Features**: Passenger class, age, sex, fare, family members, embarkation port, etc.

---

## 🛠️ Tools & Libraries
- **RapidMiner**
- **Python**, **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**

---

## 🔄 Preprocessing & Workflow

In **RapidMiner**, the workflow was visually designed to clean, engineer, and split the data before training the model. Below is a snapshot of the complete pipeline:

![RapidMiner Workflow](/images/Gambar1.png)

---

## 📈 Model Results (RapidMiner)

The performance of the Logistic Regression model in RapidMiner is summarized below:
- **Overall Accuracy**: 81.3%

![RapidMiner Performance Metrics](/images/Gambar2.png)

---

## 🧪 Model Results (Python)

Using **scikit-learn** in Python, the Logistic Regression model achieved slightly better performance. Here's the **confusion matrix** and **accuracy score**:

![Python Confusion Matrix](/images/Gambar3.png)
![Python Accuracy](/images/Gambar5.png)

Here's the **classificatin report** :
![Classification Report](/images/Gambar4.png)

---

## 📊 Feature Importance

The feature weights from Logistic Regression by Python helped in understanding which variables were most influential in predicting survival:

![Feature Importance](/images/Gambar6.png)

---

## 📊 Correlation Heatmap Matrix

The feature weights from Logistic Regression by Python can also be helped in understanding which pair variables were most influential in predicting survival by using correlation heatmap:

![Feature Importance](/images/Gambar7.png)

---


## 📌 Comparison

| Platform     | Accuracy |
|--------------|----------|
| RapidMiner   | 81.30%   |
| Python       | 82.44%   |

- Python provided **better model control and interpretability**.
- RapidMiner is ideal for **quick visual modeling and education**.
- Python was more flexible for **custom preprocessing and evaluation.**

---

## 🔍 Insights
- Preprocessing (missing values, feature engineering) played a **critical role** in model accuracy.
- GUI platforms like RapidMiner are excellent for beginners or quick iteration.
- Python remains essential for scalable, reproducible, and in-depth modeling.

---

## 🏁 Conclusion

This project demonstrated how the same model can yield slightly different results across platforms. It was a valuable learning experience in balancing visual tools and code-based environments for machine learning.

