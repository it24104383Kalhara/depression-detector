# Depression Detection using Logistic Regression

## 📌 Project Summary
A machine learning model that detects depression patterns using Logistic Regression algorithm. Developed as part of University AIML module coursework.

## 🎯 What I Built
- **Data Preprocessing**: Cleaned and balanced the student depression dataset
- **Logistic Regression Model**: Implemented from scratch for classification
- **Model Evaluation**: Comprehensive performance analysis with metrics
- **Visualizations**: Created charts for data patterns and results

## 🔍 Features Used for Prediction
- **Demographic**: Gender, Age
- **Academic**: Academic Pressure, CGPA, Study Satisfaction, Degree, Study Hours
- **Lifestyle**: Sleep Duration, Dietary Habits
- **Mental Health**: Suicidal Thoughts, Family History of Mental Illness
- **Financial**: Financial Stress

## ⚡ Techniques for Accuracy Improvement
- **Data Balancing**: Applied SMOTE/oversampling to handle class imbalance
- **Feature Engineering**: Selected most relevant features through correlation analysis
- **Hyperparameter Tuning**: Optimized regularization parameters
- **Cross-Validation**: Used k-fold cross-validation for robust evaluation
- **Feature Scaling**: Applied standardization for better convergence

## 📊 Key Result
**Final Model Accuracy: 84.3190%**

![Accuracy Visualization](images/model%20training/Screenshot%202025-11-13%20135811.png)

## 🚀 Quick Start
```bash
# Run the Jupyter notebook
jupyter notebooks/IT24104383_LogisticRegression.ipynb


## 📁 Project Structure
depression-detector/
├── notebooks/
│   └── IT24104383_LogisticRegression.ipynb
├── data/
│   ├── student_depression_dataset.csv
│   └── balanced_dataset.csv
├── images/
│   ├── preprocessing/     # Data analysis charts
│   └── model training/    # Model performance results
└── README.md


## 👨‍💻 Developer
Vinod - IT24104383 - University AIML Module
