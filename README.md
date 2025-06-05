linkdin 
https://www.linkedin.com/posts/satyam-chaurasiya-ai-python-665983360_machinelearning-logisticregression-python-activity-7336042293121961986-oAs2?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFnYS-0B-obxGctJ6FA-JSnnF6uqv3e_lLU&utm_campaign=copy_link

# 📘 Pass/Fail Prediction using Logistic Regression

This project is part of my machine learning practice where I built a simple model to predict whether a student will **pass or fail** based on the number of hours they studied.

---

## 📌 Project Overview

- Used Logistic Regression to classify pass/fail
- Dataset contains 10 students with:
  - Name
  - Study Hours
  - Result (0 = Fail, 1 = Pass)
- Visualized data using **Seaborn**
- Trained the model using `train_test_split` from Scikit-Learn
- Predicted the outcome for test data and compared with actual values

---

## 🛠️ Technologies Used

- Python
- Pandas
- Seaborn
- Matplotlib
- Scikit-Learn

---

## 📊 Sample Data

| Name  | Hours | Pass |
|-------|-------|------|
| Ram   |   1   |  0   |
| Radha |   6   |  1   |
| Anita |  10   |  1   |

> Result = 1 means Pass  
> Result = 0 means Fail

---

## 🎯 Key Learning

- How logistic regression works in binary classification
- Importance of data visualization
- How much study is needed to get a passing chance
- Found that students studying **6+ hours** have a better chance of passing (over 50%)

---

## 📈 Output Example

```python
Student studied 3 hrs → Predicted: Fail | Actual: Fail  
Student studied 8 hrs → Predicted: Pass | Actual: Pass
