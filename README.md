# 🩺 Logistic Regression – Breast Cancer Classification

## 🎯 Objective
Build a **Logistic Regression** model to classify breast tumors as **malignant** or **benign** using features extracted from digitized breast mass images.  
The goal is to create an accurate and interpretable classification model suitable for medical decision support.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔍 Summary of Steps
### 1. Data Loading & Exploration
- Loaded the breast cancer dataset
- Examined data structure, feature distributions, and summary statistics

### 2. Data Cleaning
- Removed the non-informative column **`Unnamed: 32`** (contained all missing values)
- Converted target labels:
  - **Malignant (M) → 1**
  - **Benign (B) → 0**

### 3. Train-Test Split
- Split the dataset into:
  - **80% Training**
  - **20% Testing**

### 4. Feature Scaling
- Applied **StandardScaler** to standardize numerical features
- Ensured optimal convergence and performance of logistic regression

### 5. Model Building
- Trained a **Logistic Regression** classifier on the training data
- Generated predictions on the test set

### 6. Model Evaluation
- Evaluated performance using:
  - Confusion Matrix
  - Precision
  - Recall
  - ROC-AUC Score
- Plotted **ROC Curve** to visualize classification performance

### 7. Threshold Tuning
- Adjusted the classification threshold
- Observed trade-offs between precision and recall

---

## 📊 Results & Insights
- Achieved **high precision and strong ROC-AUC**
- Model effectively distinguishes malignant from benign tumors
- Threshold tuning improved precision without significantly reducing recall
- Logistic regression proved reliable and interpretable for medical classification

---

## ✅ Conclusion
The logistic regression model demonstrated **strong classification performance** in detecting breast cancer malignancy.  
Its interpretability, combined with high ROC-AUC and precision, makes it well-suited for **healthcare and diagnostic applications**, where minimizing false positives and false negatives is critical.

---

## 📁 Project Files
- `data.csv` – Breast cancer dataset  
- `Breast_Cancer_Classification.ipynb` – Data preprocessing, modeling, and evaluation  
- `README.md` – Project documentation  

---

## 🚀 Future Improvements
- Apply regularized logistic regression (L1/L2)
- Compare with other classifiers (SVM, Random Forest, XGBoost)
- Perform cross-validation for robustness
- Integrate feature importance analysis

---
