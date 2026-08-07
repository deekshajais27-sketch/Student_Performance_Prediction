# 🎓 AI-Driven Student Performance Prediction System

## 📌 Overview

The **AI-Driven Student Performance Prediction System** is a Machine Learning project that predicts a student's **final grade (G3)** based on various academic, personal, and social factors.

The project demonstrates a complete Machine Learning workflow including:

* Data loading and exploration
* Data preprocessing
* Categorical data encoding
* Data visualization
* Model training
* Student performance prediction
* Model evaluation
* Actual vs. predicted grade comparison

## 🎯 Objectives

* Predict the final grade of students using Machine Learning.
* Analyze factors that may affect student academic performance.
* Explore and preprocess the student performance dataset.
* Train and evaluate a Linear Regression model.
* Compare actual grades with predicted grades.

## 📊 Dataset

**Dataset:** Student Performance Dataset
**Source:** UCI Machine Learning Repository
**File Used:** `student-por.csv`
**Target Variable:** `G3` (Final Grade)

The dataset contains **649 student records and 33 columns**. It includes information related to students' demographics, family background, study habits, academic performance, health, absences, and other factors.

Some important features include:

* Age
* Gender
* Study Time
* Previous Failures
* Absences
* Family Relationship
* Health
* G1 – First Period Grade
* G2 – Second Period Grade
* G3 – Final Grade

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Cleaning & Preprocessing
   ↓
Label Encoding
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Visualization
```

## ⚙️ Data Preprocessing

The categorical features in the dataset are converted into numerical values using **Label Encoding**.

The target variable `G3` is separated from the input features, and the dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

The model uses `random_state=42` for reproducibility.

## 🤖 Machine Learning Model

### Linear Regression

A **Linear Regression** model is used to predict the final student grade (`G3`).

The model is trained using the training dataset and then evaluated on unseen test data.

## 📈 Model Performance

The model achieved the following results:

| Metric   |  Score |
| -------- | -----: |
| MAE      | 0.7554 |
| MSE      | 1.4371 |
| R² Score | 0.8526 |

An **R² Score of approximately 0.85** indicates that the model explains a substantial portion of the variation in the final grades.

## 📊 Visualization

The project includes visual analysis such as:

* Actual vs. Predicted Grades
* Student performance analysis
* Graphical comparison of model predictions

The Actual vs. Predicted Grades visualization helps evaluate how closely the model's predictions match the actual student grades.

## 💡 Key Result

The trained Linear Regression model successfully predicts student final grades using the available academic and personal features.

The comparison between actual and predicted grades shows that the model can provide reasonably accurate predictions for student performance.

## 📁 Project Structure

```text
Student-Performance-Prediction/
│
├── Student_Performance_Prediction.ipynb
├── student-por.csv
└── README.md
```

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Student-Performance-Prediction.git
```

### 2. Open the project

Open the notebook:

```text
Student_Performance_Prediction.ipynb
```

You can run it using **Jupyter Notebook** or **Google Colab**.

### 3. Dataset Path

Make sure the dataset file is available and update the CSV path in the notebook if required.

## 🔮 Future Improvements

The project can be improved by:

* Trying advanced regression algorithms.
* Comparing multiple Machine Learning models.
* Using feature selection techniques.
* Applying hyperparameter tuning.
* Deploying the model as a web application.
* Adding an interactive student performance prediction interface.

## 👩‍💻 Author

**Deeksha Jaiswal**


