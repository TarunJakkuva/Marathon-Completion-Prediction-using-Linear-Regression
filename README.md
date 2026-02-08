# Marathon Completion Prediction using Logistic Regression

This project uses **Logistic Regression** to analyze whether **weekly training frequency** increases the probability of **successfully completing a marathon**.

The goal is to demonstrate a complete machine learning workflow — from data splitting to model evaluation — using a simple, interpretable classification model.

---

## 📌 Problem Statement

Does increasing weekly training improve the likelihood of completing a marathon?

This project frames the question as a **binary classification problem** and evaluates how well a Logistic Regression model can predict marathon completion.

---

## 📊 Dataset

- The dataset used is **synthetic**
- It was sourced from publicly available examples on the web
- Used strictly for **learning and demonstration**
- No real athlete or personal data is involved

**Target Variable:**
- `1` → Marathon completed  
- `0` → Marathon not completed  

---

## ⚙️ Methodology

- **Model Used:** Logistic Regression
- **Train-Test Split:**
  - 60% Training data
  - 20% Testing data
- Model trained to estimate the **probability of completion** based on training frequency

---

## 📈 Model Evaluation

The trained model is evaluated on unseen test data using:

- Accuracy score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### Results Summary

- **Accuracy:** ~90%
- Strong performance for the positive class (marathon completion)
- Minor misclassifications observed, expected due to small dataset size

---

## 🧠 Key Learnings

- Logistic Regression is effective for simple binary outcome prediction
- Weekly training frequency shows a strong positive association with marathon completion
- Learned how to:
  - Apply Logistic Regression for classification
  - Interpret precision, recall, and F1-score
  - Use confusion matrices for deeper evaluation than accuracy alone

---

## ⚠️ Limitations

- Dataset is synthetic and limited in size
- Model assumes a linear decision boundary
- Results are illustrative and not meant for real-world athletic decision-making

---

## 🚀 Future Improvements

- Generate synthetic data programmatically
- Add ROC curve and AUC analysis
- Compare with other classifiers (Decision Tree, Random Forest)
- Include probability threshold tuning

---

## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn
