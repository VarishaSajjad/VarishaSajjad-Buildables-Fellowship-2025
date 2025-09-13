

## 📘 Week 1 — Assignment 1 (Machine Learning Foundations)  

This week focused on core ML algorithms and evaluation techniques.  

### ✅ Tasks Implemented  
1. **Support Vector Machines (SVM)**  
   - Role of the Kernel Trick (Linear, Polynomial, RBF).  
   - Implemented SVM with different kernels and compared accuracies.  

2. **Random Forest — Overfitting vs. Generalization**  
   - Explained why Random Forests generalize better than a single Decision Tree.  
   - Trained a Random Forest and analyzed **feature importance** for loan approval.  

3. **Confusion Matrix & ROC Curve**  
   - Calculated Accuracy, Precision, Recall, and F1-score from a given matrix.  
   - Plotted ROC Curve and discussed Precision–Recall trade-offs.  

4. **K-Nearest Neighbors (KNN)**  
   - Effect of choosing small vs. large K on bias/variance.  
   - Implemented KNN with cross-validation to find optimal K.  

5. **Bayesian Belief Networks (BBN)**  
   - Modeled a network with **Loan Approval, Income, Credit Score** using `pgmpy`.  
   - Computed probability of approval given high income + low credit score.  

**⭐ Bonus:** Compared **SVM, Random Forest, KNN** on accuracy, precision, and recall — concluded most robust model.  

---

## 🧹 Week 2 — Data Preprocessing & Feature Transformation  

This week emphasized how clean data impacts model performance.  

### ✅ Topics Covered  
- Handling **missing values** (mean/median imputation, advanced imputers).  
- Detecting and handling **outliers** (IQR, Z-score).  
- **Scaling & normalization** (Min-Max, Standardization).  
- **Data transformations** (Log, Box-Cox).  
- **Encoding categorical variables** (One-Hot, Label, Target Encoding).  
- **Balancing data** with SMOTE/undersampling.  
- **Feature engineering** and selection basics.  

### 🧠 Implementation  
- Applied **Logistic Regression** on the Assignment 1 dataset:  
  - Without preprocessing.  
  - With preprocessing (scaling, encoding, imputations).  
- Compared **ROC Curve** and evaluation metrics.  

### 📊 Result  
- Preprocessing improved ROC AUC, stability, and generalization significantly.  

---

## 🏗️ Week 3 — Feature Selection & Dimensionality Reduction (Iris)  

This week explored feature selection and dimensionality reduction on the **Iris dataset**.  

### ✅ Techniques Used  
- **Feature Selection:** RFE, Decision Tree importances, Mutual Information, Forward/Backward/Stepwise selection, Lasso, Chi-Square, ANOVA, Boruta.  
- **Dimensionality Reduction:** PCA, LDA, t-SNE, Autoencoder, ICA, Factor Analysis.  

### 🧠 Implementation  
- Trained models (Logistic Regression, SVM, Random Forest) on:  
  - Full dataset.  
  - Selected features.  
  - Reduced dimensions.  

### 📊 Results  
- Petal length & petal width = most important features.  
- LDA best for class separation.  
- PCA useful for variance preservation.  
- t-SNE revealed clear clustering for visualization.  

---

## 🛠️ Tech Stack  

- **Python 3.x**  
- **Libraries:** scikit-learn, matplotlib, seaborn, numpy, pandas, pgmpy, imbalanced-learn  

---

## 🚀 How to Run  

1. Clone the repo:  
   ```bash
   git clone https://github.com/VarishaSajjad/VarishaSajjad-Buildables-Fellowship-2025.git
   cd VarishaSajjad-Buildables-Fellowship-2025
