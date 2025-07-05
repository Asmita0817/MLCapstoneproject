# 📊 Salary Prediction using Machine Learning (Capstone Project)

This project is a complete machine learning pipeline that predicts the **Expected Salary (CTC)** of a candidate based on features like experience, education, department, and more.

---

## 📂 Dataset
- CSV file containing candidate profiles and expected salaries
- Features include:
  - Total Experience
  - Department, Role, Industry
  - Current CTC
  - Education, Certifications, Publications
  - Designation, Appraisal, Graduation/PG details

---

## 🔧 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (RandomForestRegressor)
- Seaborn, Matplotlib

---

## 🧼 Data Preprocessing
- Dropped high-NaN PhD columns
- Filled missing text with `"Unknown"`
- Filled missing years with `median`
- Label Encoding for categorical features

---

## 📈 Model & Metrics
- **Model used**: Random Forest Regressor
- **Evaluation**:
  - RMSE: ~₹31,000
  - R² Score: ~0.82
- **Custom Prediction**:
  - Model predicts salary for new candidates based on input features

---

## 📌 Sample Output

```python
💰 Predicted Expected CTC: ₹666,092


---


---

## 🧪✨ Custom Prediction — Try It Yourself!

> ✅ **Test your own candidate profile inside the notebook!**

This project supports **manual custom predictions** — just scroll to the 🔮 `Try Custom Prediction` section in the notebook and enter a profile like:

'UG_Specialization': 'Computer Science'
'PG_Specialization': 'None'
'Skills': 'Python, SQL, Excel'
'Experience': 2
'Current_Location': 'Bangalore'
'UG_University': 'Tier 2'
'PG_University': 'None'
'Graduation_Year': 2023

➡️ 💥 The model will instantly return a **personalized Expected CTC** like:
🎯 Predicted CTC: ₹6.72 Lakhs

This makes the model **interactive**, **practical**, and shows how it can be used in **real-world hiring scenarios** 🔍

---

## 🙋‍♀️ Created By

**Asmita Mahajan**  
🎓 BTech, Computer Engineering — Thapar University (2nd Year)  
💻 Machine Learning Enthusiast | Beginner Data Scientist | Problem Solver

📬 **Connect with me:**  
🔗 [LinkedIn](https://www.linkedin.com/in/asmita-mahajan-590081356/)  
🔗 [GitHub](https://github.com/Asmita0817)

---





