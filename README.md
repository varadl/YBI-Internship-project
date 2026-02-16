# Student Performance Prediction Using Machine Learning  
*(YBI Foundation – 1 Month Internship Project)*

---

## 📌 Project Overview
This project was completed as part of the **1-Month Internship Program at YBI Foundation**.  
The objective of the project is to build a **Machine Learning regression model** that predicts a student’s final academic performance based on multiple academic and behavioral factors.

The project demonstrates the complete **machine learning workflow**, including data preparation, feature scaling, model training, evaluation, and prediction.

---

## 🎯 Objective of the Project
To design and implement a **Linear Regression model** that estimates a student’s final performance score using relevant academic indicators such as study hours, attendance, previous scores, and assignment performance.

---

## 🧠 Machine Learning Approach
- **Learning Type:** Supervised Learning  
- **Problem Type:** Regression  
- **Algorithm Used:** Linear Regression  

Linear Regression was selected due to its simplicity, interpretability, and suitability for predicting continuous values.

---

## 📊 Dataset Description
The dataset contains student-related academic and behavioral attributes.

### Features Used:
| Feature | Description |
|------|-----------|
| Study_Hours | Average daily study hours |
| Attendance | Attendance percentage |
| Previous_Score | Score obtained in previous exams |
| Assignments | Assignment completion score |
| Internet_Access | Internet availability (0 = No, 1 = Yes) |
| Final_Score | Target variable (student performance score) |

> Note: The dataset used in this project is **synthetically created for academic and training purposes**.

---

## ⚙️ Project Workflow
1. Import required Python libraries  
2. Load and prepare the dataset  
3. Perform feature selection  
4. Split the dataset into training and testing sets  
5. Apply feature scaling using StandardScaler  
6. Train the Linear Regression model  
7. Evaluate the model using R² Score and Mean Squared Error  
8. Perform prediction on new student data  

---

## 🧩 Project Implementation
The complete implementation of this project is provided using a **Python script (.py file)**.

- **File Name:** `student_performance_prediction.py`  
- The script includes:
  - Dataset creation  
  - Feature scaling  
  - Model training  
  - Model evaluation  
  - Sample prediction  

> Note: The project is submitted using the `.py` file to ensure smooth execution and avoid notebook rendering issues on GitHub.

---

## 📈 Model Evaluation Metrics
- **R² Score** – Measures how well the model explains variance in the target variable  
- **Mean Squared Error (MSE)** – Measures prediction error  

The model achieved **good accuracy**, indicating reliable predictive performance for academic evaluation.

---

## 🛠 Tools & Technologies Used
- Python  
- Google Colab  
- Pandas  
- NumPy  
- Scikit-learn  
- GitHub  

---

## ⚠️ Challenges Faced & Solutions
| Challenge | Solution |
|--------|--------|
| Different feature scales | Applied StandardScaler |
| Overfitting risk | Used train-test split |
| Limited dataset size | Used simple and interpretable model |

---

## ▶️ How to Run the Project
```bash
pip install pandas numpy scikit-learn
python student_performance_prediction.py
