# 🧠 Employee Salary Prediction Using Machine Learning

This project is part of the AICTE–IBM SkillsBuild Internship under Edunet Foundation.

## 📌 Objective
To build a machine learning model that predicts employee salary based on demographic and work-related features using a modified version of the UCI Adult dataset.

---

## 📂 Dataset
- Source: UCI Adult Income dataset (with synthetic salary column for regression)
- Features: Age, Education, Occupation, Workclass, Hours-per-week, etc.
- Target: `Salary` (numeric, simulated from income class)

---

## ⚙️ Technologies & Libraries Used
- Python
- Jupyter Notebook / Google Colab
- pandas, numpy
- scikit-learn (LabelEncoder, LinearRegression)
- matplotlib, seaborn

---

## 🚀 Steps Followed
1. Dataset cleaned (`?` values dropped)
2. Categorical variables encoded
3. Synthetic `salary` column created
4. Features selected and train-test split
5. Model trained using Linear Regression
6. Performance evaluated using MAE, MSE, R²
7. Plotted Actual vs Predicted salary

---

## 📊 Results
- MAE: ~5000–10000 INR (varies per run)
- R² Score: ~0.5–0.7 (demo purpose)
- Visualization: Scatter plot of predicted vs actual salary

---

## 📌 Colab Notebook
You can run the project in Google Colab:  
👉 [Open in Colab](https://colab.research.google.com/drive/1v_2L9HhTKQOBU9i_3xD2G_5M9gmuQlbb?usp=sharing)

---

## 🙋‍♀️ Author
**Esha Debnath**  
CSE (AI & ML), GKCIET  
Capstone Project under IBM SkillsBuild Internship
