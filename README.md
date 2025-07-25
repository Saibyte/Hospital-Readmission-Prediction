# 🏥 Hospital Readmission Risk Prediction

A Machine Learning project to predict the risk of hospital readmission for patients with chronic conditions. This project uses real-world-style patient data, applies data preprocessing, trains multiple classification models, evaluates them, and provides visual analysis and insights.

---

## 👥 Team Members(**TEAM(SC2)3_5**)

- **Sai Sandipanee Mohpatra**: 23CSE483 , 23cse483.saisandipaneemohapatra@giet.edu
- **Rohit Kumar Samal**: 23CSE312 , 23cse312.rohitkumarsamal@giet.edu
- **Pitendra Kumar Sahoo**: 23CSE357 , 23cse357.pitendrakumarsahoo@giet.edu
- **Binayak Sahu**: 23BCA023 , 23bca023.ronybinayak@giet.edu 

---

## 📁 Project Structure


---

## 🔍 Problem Statement

To build a system that can predict whether a patient with a chronic condition is at risk of being readmitted to the hospital, based on historical data like demographics, medical condition, medication, admission type, and test results.

---

## 🧹 Part 1: Data Preprocessing

- Loaded dataset using Pandas
- Handled missing values (none found)
- Encoded categorical variables using LabelEncoder & OneHotEncoder
- Scaled numerical features using MinMaxScaler
- Split data into training and testing sets (80/20)


---

## 🤖 Part 2: Model Building & Evaluation

- Models used:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluated using:
  - Accuracy
  - Precision, Recall, F1 Score
  - Confusion Matrix
- Selected best model using GridSearchCV


---

## 📊 Part 3: Visualization & Report

- Created graphs for:
  - Age distribution
  - Gender distribution
  - Billing amounts
  - Top medications
- Generated HTML report with visual insights



---

## ✅ Requirements

To run notebooks:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
