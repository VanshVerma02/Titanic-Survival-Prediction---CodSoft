# 🚢 Titanic Survival Prediction

This project uses machine learning to predict whether a passenger survived the Titanic disaster based on features like age, gender, class, and fare. It walks through a complete data science pipeline — from data cleaning to model evaluation — using the Titanic dataset.

---

## 📂 Dataset Overview

The dataset includes details about each passenger:

* **Target**: `Survived` (0 = No, 1 = Yes)
* **Features**: `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`, etc.

Missing values were handled, categorical variables were encoded, and irrelevant columns like `Name`, `Cabin`, and `Ticket` were removed.

---

## 🛠️ Tools & Libraries Used

* **Python**
* **Pandas**, **NumPy** – Data handling
* **Seaborn**, **Matplotlib** – Visualization
* **Scikit-learn** – Machine learning models and evaluation
* **Jupyter Notebook** – Development environment

---

## 📊 Workflow Summary

1. **Data Cleaning**

   * Handled missing values (e.g., `Age`, `Embarked`)
   * Dropped columns with excessive nulls (`Cabin`)

2. **Feature Encoding**

   * Converted `Sex` and `Embarked` to numerical format

3. **Model Building**

   * Used **Random Forest Classifier**
   * Trained on 80% of the data and tested on 20%

4. **Evaluation Metrics**

   * Accuracy Score: **0.81**
   * Classification Report:

     * Precision (Class 0): 0.83 | (Class 1): 0.79
     * Recall (Class 0): 0.86 | (Class 1): 0.74
     * F1-Score Avg: **0.80**

5. **Feature Importance (Optional)**

   * Visualized which features contributed most to predictions.

---

## ✅ Key Results

* Achieved **81% accuracy** on unseen data.
* Most important features: **Sex**, **Pclass**, **Fare**, and **Age**.
* Females and higher-class passengers had a better chance of survival.

---

## 📌 Conclusion

This beginner-friendly ML project demonstrates the real-world application of classification algorithms, EDA, and feature engineering using the Titanic dataset.

---

## 👤 Author

**Vansh Verma**
*Machine Learning & Data Science Enthusiast*

