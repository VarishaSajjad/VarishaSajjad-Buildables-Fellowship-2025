# 📘 Buildables Fellowship – Assignment 1  

This repository contains solutions to **Assignment 1** of the Buildables Fellowship, covering fundamental and advanced topics in **Machine Learning** such as SVM, Random Forest, KNN, Confusion Matrix, ROC Curves, and Bayesian Belief Networks.  

All tasks are implemented and explained in a single Jupyter Notebook / Python file for ease of reference.  

---

## 📑 Assignment Tasks  

### 1️⃣ Support Vector Machines (SVM) – Decision Boundaries  
- Explained how SVM can find an optimal decision boundary even when classes are not linearly separable.  
- Discussed the **Kernel Trick** (Linear, Polynomial, RBF) and their performance on high-dimensional data.  
- **Bonus Task**: Implemented SVM with different kernels and compared accuracies.  

---

### 2️⃣ Random Forest – Overfitting vs. Generalization  
- Explained how **Random Forest** reduces overfitting compared to a single Decision Tree.  
- Discussed the role of **Bootstrapping** and **Feature Selection** in improving model performance.  
- **Practical Task**: Trained a Random Forest on the dataset and analyzed **feature importance** (which features most affect loan approval).  

---

### 3️⃣ Confusion Matrix & ROC Curve – Model Evaluation  
- Given confusion matrix:  

  | Predicted ↓ / Actual → | Default (1) | No Default (0) |  
  |-------------------------|-------------|----------------|  
  | **Default (1)**         | 50          | 30             |  
  | **No Default (0)**      | 10          | 110            |  

- Calculated:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
  - **F1-Score**  
- Plotted **ROC Curve** using probability scores.  
- Discussed trade-offs between Precision vs. Recall and how adjusting the threshold affects false positives.  

---

### 4️⃣ K-Nearest Neighbors (KNN) – Choosing Optimal K  
- Explained the effect of **small K vs. large K** on bias-variance tradeoff.  
- Implemented KNN with cross-validation to determine the **optimal K**.  
- Analyzed how accuracy varies with different values of K.  

---

### 5️⃣ Bayesian Belief Networks (BBN) – Probabilistic Decision Making  
- Explained how **Conditional Independence** simplifies probability calculations in Bayesian Networks.  
- Built a simple Bayesian Network with nodes:  
  - **Loan Approval**  
  - **Income Level**  
  - **Credit Score**  
- **Implementation**: Used `pgmpy` in Python to model the Bayesian Network and computed the probability of approval given **high income but low credit score**.  

---

### ⭐ Bonus Challenge  
- Compared **SVM, Random Forest, and KNN** models on the dataset.  
- Evaluated in terms of:  
  - **Accuracy**  
  - **Precision**  
  - **Recall**  
- Concluded which model is the most **robust** for predicting loan approval and why.  

---

## 🛠️ Technologies Used  
- **Python 3.x**  
- **Libraries**:  
  - scikit-learn (SVM, Random Forest, KNN, evaluation metrics)  
  - matplotlib & seaborn (visualization)  
  - numpy, pandas (data handling)  
  - pgmpy (Bayesian Belief Networks)  

---

## 🚀 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/VarishaSajjad/Buildables-Assignment1.git
   cd Buildables-Assignment1
