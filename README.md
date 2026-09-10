# Customer Churn Prediction

A machine learning project focused on predicting customer churn using Python and the Random Forest classification algorithm.

## 📌 Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave their services. In this project, customer data is cleaned, analyzed, preprocessed, and used to build a machine learning model for churn prediction.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Machine Learning

## 🔄 Project Workflow

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Handling missing values
4. Categorical feature encoding
5. Feature scaling
6. Train-test split
7. Random Forest model training
8. Model evaluation
9. Feature importance analysis

## 🤖 Model Used

**Random Forest Classifier**

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📊 Results

The initial model achieved approximately **80.48% accuracy**.

To improve the detection of customers likely to churn, class weighting was applied. This increased the churn-class recall to approximately **83%**, helping the model identify more potential churn customers.

## 🔍 Key Features

The analysis identified several important factors related to churn, including:

* Total Charges
* Monthly Charges
* Tenure
* Contract
* Payment Method

## 💡 Key Insight

Applying class weighting improved the model's ability to identify churn customers, although it resulted in lower overall accuracy. This highlights the importance of considering recall and business objectives rather than accuracy alone when dealing with imbalanced datasets.

## ▶️ How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open `churn_analysis.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells sequentially.

## 📁 Files

churn_analysis.ipynb` — Data analysis, preprocessing, model building, and evaluation
Churn.cvs.csv` — Customer churn dataset
README.md` — Project documentation
