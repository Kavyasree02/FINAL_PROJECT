# 📅 Healthcare Appointment No-Show Prediction

##  Project Objective
This project aims to predict whether patients will miss their healthcare appointments using machine learning. By identifying patterns in no-shows, we can optimize hospital scheduling and reduce resource wastage.

## Dataset
 **Source**: Kaggle - Medical Appointment No Shows

## Tools & Technologies
 **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
 **Jupyter Notebook** for exploration and modeling
 **Power BI** for interactive dashboards
 **FPDF / nbconvert** for PDF reports

##  Steps Followed

1. **Data Cleaning**
   - Fixed data types (e.g., dates, strings)
   - Engineered new features:
     - `waiting_days` (gap between scheduling and appointment)
     - `day_of_week` from appointment date

2. **Exploratory Data Analysis (EDA)**
   - Investigated impact of:
     - Age, gender
     - SMS reminders
     - Days of the week
     - Health conditions (e.g., alcoholism, hypertension)
     - Neighborhood

3. **Model Training**
   - Used **DecisionTreeClassifier** from Scikit-learn
   - Evaluated with:
     - Confusion matrix
     - Classification report


