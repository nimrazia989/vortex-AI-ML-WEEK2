# 🚢 VortexTech AI & ML Internship – Week 2: Build a Classification Model

## 📌 Project Overview

This project was completed as part of the **VortexTech AI & ML Internship 2026 (Week 2)**.

The objective was to build a **Machine Learning Classification Model** capable of predicting whether a passenger survived the Titanic disaster using the **Titanic Dataset**. The project follows a complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and comparison.

---

## 🎯 Objectives

* Load a cleaned dataset
* Perform data preprocessing
* Encode categorical features
* Split the dataset into training and testing sets
* Train a Logistic Regression model
* Train a Decision Tree model
* Evaluate both models using standard classification metrics
* Compare model performance

---

## 📂 Dataset

**Dataset:** Titanic Dataset

Target Variable:

* **Survived**

  * 0 = Did Not Survive
  * 1 = Survived

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Joblib

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Handle Missing Values
3. Remove Unnecessary Columns
4. Encode Categorical Variables
5. Split Data (80% Training, 20% Testing)
6. Train Logistic Regression Model
7. Train Decision Tree Model
8. Evaluate Performance
9. Compare Results
10. Save the Trained Model

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## 🤖 Models Used

### Logistic Regression

A linear classification algorithm suitable for binary classification problems.

### Decision Tree Classifier

A tree-based machine learning algorithm used for comparison with Logistic Regression.

---

## 📁 Project Structure

```text
vortextech-aiml-week2/
│
├── data/
│   └── Titanic-Dataset.csv
│
├── notebooks/
│   └── Week2_Classification.ipynb
│
├── images/
│   ├── confusion_matrix.png
│   └── feature_importance.png
│
├── models/
│   └── classification_model.pkl
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ▶️ How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run **Week2_Classification.ipynb**.

---

## 📌 Results

The Logistic Regression model achieved good performance for predicting passenger survival.

The Decision Tree model was also trained and compared to evaluate whether a tree-based approach improved prediction accuracy.

Performance was measured using Accuracy, Precision, Recall, F1 Score, and the Confusion Matrix.

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature engineering
* Cross-validation
* Random Forest Classifier
* Gradient Boosting (XGBoost)
* Support Vector Machine (SVM)

---

## 👩‍💻 Author

**Nimra Zia**

BS Artificial Intelligence

University of Engineering & Technology (UET) Peshawar

VortexTech AI & ML Internship – 2026

---

## ⭐ Acknowledgements

Special thanks to **VortexTech** for providing this internship assignment and the opportunity to strengthen practical Machine Learning skills.
