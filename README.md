# Loan Status Classification using Logistic Regression and Decision Trees  

## 📌 Project Overview  
This project focuses on predicting the **loan status of applicants** based on demographic, financial, and credit-related factors.  
Since the dataset was highly **imbalanced**, we applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the classes before training models.  

The models implemented are:  
- **Logistic Regression (Logit model)**  
- **Decision Tree Classifier**  

The goal is to identify **significant factors contributing to loan status** and evaluate which model performs better in predicting loan approvals.  

---

## 📊 Dataset  
- Source: [Add dataset source here, e.g., Kaggle link or provided dataset]  
- Key features: Applicant income, education, employment status, credit history, loan amount, etc.  
- Target variable: Loan Status (Approved / Not Approved)  
- Challenge: Dataset was **imbalanced**, requiring oversampling using SMOTE.  

---

## ⚙️ Methodology  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Train-test split  

2. **Balancing the Dataset**  
   - Applied **SMOTE** to handle imbalance  

3. **Modeling**  
   - Logistic Regression  
   - Decision Tree Classifier  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  
   - ROC-AUC Curve  

---

## 📈 Results Summary  
- Logistic Regression provided good interpretability with significant features highlighted.  
- Decision Tree captured non-linear patterns but required tuning to avoid overfitting.  
- [Add a short comparison of final metrics here, e.g., Logistic Regression performed better in recall, while Decision Tree achieved higher accuracy.]  

---

## 🚀 How to Run the Project  
1. Clone/download this repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Open and run the Jupyter Notebook:  
   ```bash
   jupyter notebook Pragya_Gupta_RBA55_Assignment_3.ipynb
   ```  

---

## 📦 Dependencies  
- Python 3.9+  
- pandas  
- numpy  
- scikit-learn  
- imbalanced-learn  
- matplotlib  
- seaborn  

(Exact versions available in `requirements.txt`)  

---

## ✨ Author  
**Pragya Gupta**  
MBA (Business Analytics) | Data Analytics Enthusiast  
