# 🏦 Loan Approval Prediction using Logistic Regression

This project uses machine learning to predict whether a loan application will be approved or not, based on applicant information. The model is trained using **Logistic Regression**, and includes full preprocessing, data balancing, and performance evaluation with visualization.

---

## 📁 Dataset

The dataset contains real-world loan application data with features like:

- Gender
- Marital Status
- Income
- Loan Amount
- Credit History
- ...and more

> 📂 File used: `loan_approval_dataset.csv`

---

## 🔧 Steps Performed

1. **Data Cleaning**  
   - Removed missing values  
   - Stripped extra whitespaces  
   - Dropped unneeded columns (like `loan_id`)

2. **Label Encoding**  
   - Converted categorical variables into numerical format

3. **Balancing Classes with SMOTE**  
   - Resampled minority class to solve imbalance

4. **Train-Test Split**  
   - Used 80% for training, 20% for testing

5. **Model Building**  
   - Logistic Regression with scikit-learn

6. **Evaluation**  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-score  
   - Confusion Matrix  
   - ROC Curve

---

## 📊 Visualizations

- ✅ Confusion Matrix Heatmap  
- 📊 Bar Chart of Evaluation Metrics  
- 📈 ROC Curve for classification performance

---

## 📦 Libraries Used

```bash
pandas
numpy
scikit-learn
imblearn
seaborn
matplotlib
# loan-Approval
