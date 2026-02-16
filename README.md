# Employee Attrition Prediction (Machine Learning Project)

## Business Problem

Employee attrition (employees leaving a company) is expensive for organizations.
Hiring, onboarding, and training new employees costs time and money.
The goal of this project is to **predict whether an employee is likely to leave the company** so HR teams can take preventive actions.

---

## Dataset

* IBM HR Analytics Employee Attrition Dataset
* Total Employees: 1470
* Target Variable: **Attrition (Yes / No)**

---

## Project Workflow

1. Data Cleaning

   * Handled categorical variables
   * One-hot encoding
   * Checked missing values
   * Removed data leakage columns

2. Exploratory Data Analysis (EDA)

   * Attrition distribution
   * Overtime impact
   * Job role impact
   * Business travel frequency
   * Distance from home

3. Feature Engineering

   * Converted Attrition → numerical (0/1)
   * Encoded categorical features
   * Scaled features using StandardScaler

4. Model Building

   * Logistic Regression
   * Pipeline (Scaler + Model)
   * Train/Test Split (80/20)

5. Model Evaluation

   * Confusion Matrix
   * Precision, Recall, F1 Score
   * Accuracy: **74%**
   * Attrition Recall: **62%**

---

## Key Insights

* Employees doing **Overtime** are more likely to leave
* **Laboratory Technicians & Sales roles** show higher attrition
* Higher **business travel frequency** increases attrition risk
* Longer **years since last promotion** increases attrition

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## How to Run

1. Clone this repository
2. Install requirements
3. Run `Employee_attrition_model.ipynb`

---

## Future Improvements

* Try Random Forest / XGBoost
* Hyperparameter tuning
* Deploy as a web app (Streamlit)

---

## Author

**Chinchu Sunil**
Aspiring Data Scientist | Machine Learning Enthusiast
