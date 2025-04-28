# 🚗 Sales Prediction Model

---

## 📋 Project Objective

The goal is to build a machine learning model that predicts car purchase amounts based on customer information like age, gender, annual salary, credit card debt, and net worth.

This project focuses on:
- *Accurately predicting purchase amounts* 📈
- *Handling missing values and outliers* 🧹
- *Evaluating multiple models (Linear Regression, Random Forest, XGBoost)* 🧠
- *Analyzing feature importance* 🔥
- *Providing clear business insights* 📊

---

## 🛠️ How to Run This Project

1. *Clone the Repository*

bash
git clone https://github.com/your_username/car_purchase_prediction.git
cd car_purchase_prediction


2. *Install Required Libraries*

bash
pip install -r requirements.txt


3. *Prepare Your Dataset*
- Place your car_purchasing.csv file inside the project folder.

4. *Run the Project*

bash
python car_purchase_prediction.py


✅ The script will automatically:
- Preprocess the data
- Train multiple models
- Evaluate performance
- Plot feature importances
- Print business insights

---

## 📂 Project Structure


car_purchase_prediction/
├── README.md
├── requirements.txt
├── car_purchase_prediction.py
├── car_purchasing.csv


- *car_purchase_prediction.py* → Full code (Data Cleaning, EDA, Modeling, Evaluation, Insights)
- *car_purchasing.csv* → Input dataset
- *requirements.txt* → List of necessary libraries
- *README.md* → Project documentation

---

## ⚙️ Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

You can install them with:

bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost


---

## 📊 Business Insights

After running the project, the following insights were observed:

- *Annual Salary* and *Net Worth* are the most influential factors affecting car purchase amounts.
- Customers with higher *Credit Card Debt* tend to purchase cheaper cars, indicating potential financial stress.
- *Age* also plays a significant role — middle-aged customers tend to spend more than younger customers.
- Gender differences were minimal, suggesting purchase amount is more income-driven than gender-driven.
- The best-performing model was *XGBoost, achieving the highest **R² Score* among all models.

---

✅ Everything is written in a *single Python file* for easy running and understanding!
