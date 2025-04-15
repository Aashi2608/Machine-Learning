# 🍷 Wine Quality Prediction using Machine Learning

Welcome to the **Wine Quality Prediction** project — a machine learning application that predicts the quality of wine based on its chemical composition. By leveraging data preprocessing, exploratory analysis, and robust model training, we evaluate and compare multiple algorithms to determine the best predictor of wine quality.


## 📌 Project Overview

**Objective:**  
To predict wine quality using various machine learning algorithms and compare their performance to identify the most effective model.

**Why Wine?**  
Wine quality prediction is a unique and tasteful challenge involving real-world data. It allows us to explore the intersection of chemistry and machine learning, and the complexity of quality assessment makes it an exciting problem to solve.

## 📊 Tools & Technologies

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib  
- **Algorithms:**  
  - Random Forest Classifier  
  - Support Vector Machine (SVM)  
  - K-Nearest Neighbors (KNN)  


## 🔬 Methodology

1. **Data Analysis:**  
   Explored critical parameters such as fixed acidity, citric acid, pH, etc.

2. **Preprocessing:**  
   - Handled missing values and outliers  
   - Normalized the dataset  
   - Converted categorical features (if any)

3. **Model Training:**  
   - Trained models using Random Forest, SVM, and KNN  
   - Chose Random Forest for its robustness and superior performance  
   - Used test datasets for model evaluation

4. **Evaluation Metrics:**  
   - Accuracy  
   - Precision, Recall, F1 Score  
   - Confusion Matrix

## 📈 Results & Analysis

### 🔹 Random Forest Classifier  
- **Accuracy:** 93% ✅  
- **Strengths:**  
  - High accuracy & robustness  
  - Handles complex data well  
  - Provides feature importance insights  
- **Weaknesses:**  
  - Less interpretable than simpler models  

### 🔹 Support Vector Machine (SVM)  
- **Accuracy:** 60.35%  
- **Strengths:**  
  - Effective in high-dimensional data  
  - Flexible via kernel functions  
- **Weaknesses:**  
  - Lower accuracy  
  - Sensitive to hyperparameters  

### 🔹 K-Nearest Neighbors (KNN)  
- **Accuracy:** 61.6%  
- **Strengths:**  
  - Easy to understand and implement  
  - Non-parametric, no assumption on data distribution  
- **Weaknesses:**  
  - Lower accuracy  
  - Computationally expensive for large datasets  

## **Conclusion:**  
Random Forest outperforms both SVM and KNN in predictive accuracy, making it the most suitable algorithm for this task. However, model choice depends on the balance between interpretability, speed, and accuracy.


