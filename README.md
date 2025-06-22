# 🪨 Rock vs Mine Classification using Logistic Regression

This project predicts whether an object is a **Rock** or a **Mine** based on sonar signal data using a **Logistic Regression** model.

## 📊 Objective

To classify sonar signals as either coming from a **rock** or a **mine**, based on their numerical features.

---

## 📂 Dataset

- **Source**: Kaggle – [Sonar Rock vs Mine Dataset](https://www.kaggle.com/datasets/nehaprabhavalkar/sonar-data)
- **Rows:** 208  
- **Columns:** 61  
- **Features:** 60 numerical sonar readings  
- **Target Variable:**  
  - `R` = Rock  
  - `M` = Mine

---

## 🧪 Tools & Libraries Used

- Python  
- pandas  
- numpy  
- scikit-learn (LogisticRegression, train_test_split, accuracy_score)

---

## ⚙️ Steps Performed

1. **Data Loading and Exploration**
   - Loaded CSV using pandas
   - Checked shape, nulls, basic info

2. **Data Preprocessing**
   - Label encoded target (`R` → 0, `M` → 1)
   - Split data into training and test sets (80/20)

3. **Model Training**
   - Trained a Logistic Regression model

4. **Model Evaluation**
   - Evaluated using `accuracy_score` on test data

---

## ✅ Results

- **Model Used**: Logistic Regression  
- **Test Accuracy**: **83**

---

## 🧠 What I Learned

- Basics of classification using Logistic Regression  
- How to prepare and split data for ML  
- Evaluating model performance with accuracy

---




## 📌 Future Ideas

- Try other models like SVM, Random Forest  
- Add confusion matrix, precision, recall  
- Deploy using Streamlit

---

## 🤝 Connect with Me

- GitHub: [github.com/yourusername](https://github.com/Athar-cell)  


---

> ✨ Made with ❤️ while learning ML
