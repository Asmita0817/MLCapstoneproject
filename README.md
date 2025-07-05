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

## 🧪 Custom Prediction Support

Want to test the model on a new candidate profile?

✅ This project supports **manual custom prediction** inside the notebook itself.

Just scroll to the **"Custom Prediction"** section and fill in details like:

- Age: 25  
- Gender: Female  
- UG Specialization: Computer Science  
- UG University: Tier 2  
- Skills: Python, SQL, Excel  
- Experience: 2 years  
- Location: Bangalore  
- etc.

🎯 The notebook will return a personalized **Expected CTC (Salary)** in ₹ lakhs.

This feature demonstrates the model’s flexibility and real-world usability.


