# Diabetes Prediction Using Machine Learning on Clinical Data

## 📌 Project Overview
This project is an academic solo work focused on predicting diabetes using the **PIMA Indians Diabetes Dataset** (768 records, 8 clinical features, and 1 target).  
The main objective is to build an end-to-end machine learning pipeline that performs exploratory analysis, preprocessing, model training, and evaluation to identify effective methods for early diabetes prediction.

---

## 🔎 Methodology
The workflow implemented includes:

1. **Exploratory Data Analysis (EDA)**
   - Distribution analysis and summary statistics  
   - Outlier detection  
   - Correlation heatmap  

2. **Data Preprocessing**
   - Handling zero-values using median imputation  
   - Feature scaling with `StandardScaler`  

3. **Feature Selection**
   - Correlation analysis  
   - ANOVA F-test  
   - Random Forest feature importance  

4. **Model Training**
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  

5. **Validation & Tuning**
   - 5-fold cross-validation  
   - Hyperparameter tuning with `GridSearchCV`  
   - Model validation using confusion matrices and performance metrics (accuracy, precision, recall, F1-score)

---

## 📊 Key Insights
- Identified strong correlations between features such as Glucose and Outcome.  
- Handling missing/zero values improved model performance.  
- Random Forest achieved the best balance between accuracy and robustness.  
- GridSearchCV-based tuning significantly improved Decision Tree and Random Forest results.  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries/Frameworks:** scikit-learn, pandas, NumPy, matplotlib, seaborn  
- **Tools:** Jupyter Notebook, GridSearchCV, StratifiedKFold  
- **Version Control:** Git, GitHub  
- **Editor:** Google Colab  

---

## ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Dimuthu21/Diabetes-Prediction-Using-Machine-Learning-on-Clinical-Data.git
   cd Diabetes-Prediction-Using-Machine-Learning-on-Clinical-Data
