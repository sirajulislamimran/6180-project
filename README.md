# 📊 Customer Churn Prediction (INSE 6180)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

This project predicts customer churn using classical machine learning models and a hybrid ensemble approach. It compares Decision Tree, k-Nearest Neighbours (kNN), and Naïve Bayes, and combines them using a soft voting model.

The main focus is to handle **imbalanced data correctly** and evaluate models using meaningful metrics like F1-score and ROC-AUC instead of relying only on accuracy.

---

## 📌 Project Overview

This project includes:

- Data cleaning and preprocessing pipeline  
- Feature encoding and scaling  
- Model training (Decision Tree, kNN, Naïve Bayes)  
- Hyperparameter tuning using GridSearchCV  
- Hybrid Soft Voting Ensemble model  
- Evaluation using stratified cross-validation  
- Visualizations (confusion matrices and ROC curve)  

---

## 📂 Repository Structure
├── 6180.ipynb # Main notebook (RUN THIS)
├── Telco-Customer-Churn.csv # Dataset (upload manually when prompted)
├── Telco_customer_churn.xlsx # Original dataset (not required for execution)
├── images/ # Saved plots (optional)
├── README.md # Project documentation


---

## ⚙️ How to Run the Project

### Step 1: Open the Notebook

Use one of the following:

- Google Colab (recommended)
- Jupyter Notebook (local)

---

### Step 2: Run Initial Cells

Run the first few cells to:

- Import required libraries  
- Set up environment  

---

### Step 3: Upload Dataset (IMPORTANT)

In the **second code block**, you will be prompted to upload a file.

Upload:
Telco-Customer-Churn.csv

⚠️ Important:
- Upload the `.csv` file (NOT `.xlsx`)
- Do not rename the file

---

### Step 4: Run All Cells

After uploading the dataset:

- Run all remaining cells sequentially

This will:

- Clean and preprocess data  
- Train and tune models  
- Evaluate performance  
- Generate visualizations  

---

## 📊 Output

After execution, the notebook will generate:

- 📋 Model performance table  
- 🔢 Confusion matrices (all models)  
- 📈 ROC curve comparison  
- 🤝 Hybrid model results  

---

## 🧠 Models Used

- Decision Tree (rule-based)
- k-Nearest Neighbours (distance-based)
- Naïve Bayes (probabilistic)
- Hybrid Soft Voting Ensemble

---

## 📈 Evaluation Metrics

Since the dataset is imbalanced, the following metrics are used:

- Precision  
- Recall (MOST IMPORTANT)  
- F1-score (PRIMARY METRIC)  
- ROC-AUC  
- Accuracy (for reference only)  

---

## ⚠️ Key Insight

Accuracy alone is misleading for imbalanced data.

The hybrid model achieves:

- Best F1-score  
- Best ROC-AUC  
- Strong balance between precision and recall  

Even though it does not have the highest accuracy.

---

## 📷 Example Outputs

### Confusion Matrices
![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve
![ROC Curve](images/roc_curve.png)

*(If images are not visible, run the notebook to generate them)*

---

## 🔁 Reproducibility

To reproduce results:

1. Open notebook  
2. Upload dataset  
3. Run all cells  

No additional setup required.

---

## 📚 Dataset

- IBM Telco Customer Churn Dataset  
- Available on:
  - Kaggle  
  - OpenML  

---

## 👤 Author

**Sirajul Islam Imran**  
INSE 6180 — Concordia University - 40330338

---

## ⭐ Final Note

This project demonstrates:

- Proper handling of imbalanced datasets  
- Fair model comparison  
- Practical use of ensemble learning  

The key takeaway is simple:

> The best model is not the one with highest accuracy, but the one that best balances detecting churn customers while controlling false predictions.

---
