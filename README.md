# Loan Approval Prediction 📊

This project demonstrates a machine learning workflow to predict loan approval based on applicant information.  

---

## 📁 Dataset
The dataset used is the **Loan Approval Prediction Dataset** from Kaggle.  
It contains various applicant-related features along with their loan approval status.

---

## ⚙️ Workflow
The following steps were performed:

1. **Data Loading** ⬇️  
   - Downloaded dataset from Kaggle and loaded into a pandas DataFrame.  

2. **Data Exploration** 🤔  
   - Explored dataset structure, data types, and checked for missing values.  

3. **Label Encoding** 🔄  
   - Converted categorical features (`education`, `self_employed`, and `loan_status`) into numeric form.  

4. **Feature Scaling** 📏  
   - Standardized numerical features using **StandardScaler**.  

5. **Data Balancing** ⚖️  
   - Applied **RandomOverSampler** to handle class imbalance in the target variable.  

6. **Data Splitting** ✂️  
   - Split dataset into **training** and **testing** sets.  

7. **Model Training**  
   - **Logistic Regression** 📈  
   - **Decision Tree Classifier** 🌳  

8. **Model Evaluation** ✅  
   - Evaluated using confusion matrices and classification metrics:  
     Accuracy, Precision, Recall, and F1-Score.  

---

## ✨ Results
Both models achieved perfect scores on the test set:  

- **Logistic Regression**:  
  - Accuracy: **1.0000**  
  - Precision: **1.0000**  
  - Recall: **1.0000**  
  - F1-Score: **1.0000**  

- **Decision Tree**:  
  - Accuracy: **1.0000**  
  - Precision: **1.0000**  
  - Recall: **1.0000**  
  - F1-Score: **1.0000**  

⚠️ The perfect performance suggests possible **data leakage** or overfitting. More robust validation is needed to confirm generalization.

---

## 🚀 Further Steps
- Investigate preprocessing steps for potential **data leakage** 🔎  
- Implement **cross-validation** for reliable performance estimation 📊  
- Explore additional **classification algorithms** 🤖  
- Perform **hyperparameter tuning** for optimization 🔧  
- Analyze **feature importance** (especially for Decision Tree) 🌱  

---
