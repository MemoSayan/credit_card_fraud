# Credit Card Fraud Detection

This project aims to develop a predictive model to identify fraudulent credit card transactions. Detecting fraud is critical for financial institutions and customers, as it minimizes financial losses and enhances user experience by preventing incorrect charges.

---

## 🏆 **Main Objective**
Build a predictive model capable of accurately identifying fraudulent credit card transactions.

---

## 🎯 **Specific Objectives**
- Implement oversampling techniques like **SMOTE** to address class imbalance.
- Train and compare multiple models, including:
  - Logistic Regression
  - Random Forest
  - Neural Networks
- Select the optimal model based on a variety of evaluation metrics:
  - **AUC-ROC (Area Under the ROC Curve):** Assess overall classifier performance.
  - **Recall (Sensitivity):** Measure the proportion of frauds correctly identified.
  - **Precision:** Evaluate the accuracy of transactions flagged as fraudulent.

---

## ✅ **Success Criteria**
1. **AUC-ROC ≥ 0.85**  
   - Indicates the model effectively distinguishes between fraudulent and legitimate transactions across thresholds.
2. **Recall ≥ 80%**  
   - Ensures at least 8 out of 10 fraudulent transactions are correctly identified, minimizing false negatives.
3. **Precision ≥ 50%**  
   - Balances the trade-off between false positives and false negatives to reduce customer impact and maintain operational efficiency.

---

## 🗂 **Dataset Overview**
The dataset contains **284,807 transactions** recorded over two days in September 2013, of which **492 (0.173%) are fraudulent**. This extreme imbalance highlights the importance of appropriate data preprocessing.  

### **Key Features:**
- **Time:** Time elapsed (in seconds) since the first transaction.  
- **Amount:** The transaction value.  
- **Class:** Indicates authenticity:  
  - `0`: Legitimate transaction  
  - `1`: Fraudulent transaction  

---

## 🔧 **Technologies and Tools**
- **Programming Language:** Python  
- **Libraries:**  
  - Data Processing: `pandas`, `numpy`  
  - Visualization: `matplotlib`, `seaborn`  
  - Modeling: `sklearn`, `imblearn` (for SMOTE), `tensorflow`  

---

## 🔬 **Project Workflow**
1. **Exploratory Data Analysis (EDA):**  
   - Analyzed dataset distribution, identified class imbalance, and visualized key trends.
2. **Data Preprocessing:**  
   - Applied oversampling (SMOTE) to balance the dataset.
   - Scaled numerical features for model compatibility.
3. **Model Training:**  
   - Trained and evaluated Logistic Regression, Random Forest, and Neural Networks.
4. **Model Optimization:**  
   - Used techniques like GridSearchCV to optimize hyperparameters.
5. **Evaluation:**  
   - Compared models based on AUC-ROC, Recall, and Precision.  

---

## 📊 **Results Summary**
The project successfully implemented a Random Forest model with the following performance:  
- **AUC-ROC:** Achieved a score ≥ 0.85, indicating robust classifier performance.  
- **Recall:** ≥ 80%, ensuring the majority of fraud cases were detected.  
- **Precision:** ≥ 50%, minimizing false positives for customer satisfaction.  

---

