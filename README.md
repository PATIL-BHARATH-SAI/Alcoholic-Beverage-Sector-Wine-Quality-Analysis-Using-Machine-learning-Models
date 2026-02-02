#  🍷 Alcoholic-Beverage-Sector-Wine-Quality-Analysis-Using-Machine-learning-Models

A data science and machine learning project focused on analyzing and predicting wine quality using physicochemical properties. This project helps wineries improve production consistency, quality control, and business performance through data-driven insights.

---

## 📌 Project Overview

The wine industry is highly competitive, where quality is a major differentiator. This project applies exploratory data analysis and machine learning techniques to predict wine quality based on chemical attributes.

By leveraging predictive modeling, wineries can:
- Improve product consistency
- Reduce low-quality batches
- Optimize production processes
- Enhance brand reputation

---

## 🚀 Getting Started
---

## 🎯 Project Objectives

- Perform Exploratory Data Analysis (EDA)
- Identify important quality-influencing features
- Clean and preprocess the dataset
- Build and evaluate ML models
- Select the best-performing model
- Provide business recommendations

---

## 📊 Dataset Information

**Source:** Wine Quality Dataset  
**Domain:** Alcoholic Beverage Sector

### Dataset Details
- Total Rows: 6,498
- After Cleaning: 5,320
- Columns: 14
- Format: CSV

### Input Features
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  
- Color (Red/White)  
- Good (Binary)

### Target Variable
- Quality score (0–10)
- Converted into classification categories

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

---

## 📁 Project Structure
wine-quality-prediction:

  data:
    - winequality.csv

  notebooks:
    - eda.ipynb
    - modeling.ipynb

  presentation:
    - Wine_Quality_Analysis_Presentation.pptx

  report:
    - Case Study - Alcoholic Beverage Sector.docx

  files:
    - requirements.txt
    - README.md




---

## 🔍 Sprint 1: Exploratory Data Analysis (EDA)

### Tasks
- Feature distribution analysis
- Outlier detection
- Correlation analysis
- Pattern discovery
- Business insight generation

### Key Findings
- Alcohol has strong positive correlation with quality
- Volatile acidity negatively impacts quality
- Sulphates and citric acid improve ratings
- Feature scaling is necessary

---

## 🤖 Sprint 2: Model Building

### Machine Learning Task
- Type: Classification
- Target: Wine Quality Category
- Metric: Accuracy

### Data Preprocessing
- Removed duplicate rows
- Label encoded categorical features
- Standardized numerical features
- Handled class imbalance using oversampling

### Train-Test Split
- Training: 75%
- Testing: 25%
- Stratified sampling
- Random state: 42

---

## 📈 Models Implemented

| Model               | Description             |
|---------------------|-------------------------|
| KNN                 | Instance-based learning |
| Logistic Regression | Linear classifier       |
| SVM                 | Kernel-based classifier |
| Decision Tree       | Tree-based model        |
| Random Forest       | Ensemble method         |

---

## 🏆 Best Model Performance

**Random Forest Classifier**

- Accuracy: ~85%
- Tuned using GridSearchCV
- Balanced class weights
- Reduced overfitting

### Final Parameters
- n_estimators: 400
- max_depth: 25
- class_weight: balanced

---

## 📌 Business Insights

### Production Optimization
- Control volatile acidity
- Optimize alcohol content
- Balance sulphates and citric acid

### Quality Control
- Early defect detection
- Reduced waste
- Consistent premium output

### Business Impact
- Improved brand reputation
- Higher customer satisfaction
- Increased profitability

---

## 📜 Conclusion

This project successfully demonstrates the application of machine learning in wine quality prediction. By analyzing physicochemical properties and building robust models, wineries can make informed production decisions.

Key achievements:
- Cleaned and prepared high-quality dataset
- Compared multiple ML models
- Achieved strong predictive performance
- Delivered actionable business insights


---
