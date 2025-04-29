# Classification-with-logistic-Regression
## Objective:
In this task, I built a **binary classifier** using **logistic regression** to classify breast cancer data as malignant or benign. The task involved evaluating the model using metrics like **confusion matrix**, **precision**, **recall**, and **ROC-AUC**. Additionally, I explored the **sigmoid function** and adjusted the decision threshold to observe its impact on model performance.

---## Tools and Libraries:
- **Python**
- **Scikit-learn**: For building and evaluating the logistic regression model.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For visualizing the results.
- **StandardScaler**: For feature standardization.

---
## Dataset:
The dataset used is the **Breast Cancer Wisconsin dataset**. It contains various features such as `radius`, `texture`, `smoothness`, etc., with a target variable indicating whether the tumor is **malignant (1)** or **benign (0)**.

---

## Key Steps:
1. **Data Preprocessing**:
   - Loaded and preprocessed the dataset.
   - Standardized the features.
   - Split the data into training and testing sets.

2. **Model Building**:
   - Used **logistic regression** for binary classification.

3. **Model Evaluation**:
   - Evaluated using **confusion matrix**, **precision**, **recall**, and **ROC-AUC**.

4. **Threshold Tuning**:
   - Adjusted the decision threshold to observe its effect on precision and recall.

---

## Interview Questions Answered:
1. **How does logistic regression differ from linear regression?**
   - Logistic regression is used for binary classification, predicting probabilities, whereas linear regression predicts continuous values.

2. **What is the sigmoid function?**
   - The sigmoid function maps values to a range between 0 and 1, making it suitable for binary classification.

3. **What is precision vs recall?**
   - Precision is the accuracy of positive predictions, while recall is the ability to identify all positive instances.

4. **What is the ROC-AUC curve?**
   - It plots the true positive rate against the false positive rate. The AUC is a measure of how well the model distinguishes between the classes.

5. **What is the confusion matrix?**
   - It shows the actual vs predicted classifications, providing insights into false positives and false negatives.

6. **What happens if classes are imbalanced?**
   - The model may be biased towards the majority class, leading to poor performance in predicting the minority class.

7. **How do you choose the threshold?**
   - The threshold is chosen based on the trade-off between precision and recall, often adjusted for business requirements.

8. **Can logistic regression be used for multi-class problems?**
   - Yes, using techniques like **one-vs-rest** (OvR) or **softmax** regression.

---

## How to Run the Code:
1. Clone or download the repository.
2. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
