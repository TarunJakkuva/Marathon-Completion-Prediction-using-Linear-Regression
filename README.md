# Marathon-Completion-Prediction-using-Linear-Regression
Linear Regression model analyzing the relationship between weekly training and marathon completion using synthetic data. Includes model evaluation with accuracy metrics and confusion matrix.
This project explores whether **weekly training frequency** influences the likelihood of **successfully completing a marathon**, using a simple supervised machine learning approach.

A **Linear Regression model** is trained on synthetic data to understand the relationship between training consistency and marathon completion outcomes.

---

## 📌 Problem Statement

Does increasing weekly training improve the probability of completing a marathon?

This project models that relationship using numerical features and evaluates performance on unseen test data.

---

## 📊 Dataset

- The dataset used in this project is **synthetic**
- Data was sourced from publicly available examples on the web
- It is used **strictly for learning and demonstration purposes**
- No real athlete or personal data is involved

---

## ⚙️ Methodology

- **Model Used:** Linear Regression
- **Train-Test Split:**
  - 60% Training data
  - 20% Testing data
- The model predicts binary outcomes:
  - `1` → Marathon completed
  - `0` → Marathon not completed

---

## 📈 Model Evaluation

The model is evaluated on test data using:

- Accuracy score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

### Sample Results

- **Accuracy:** ~90%
- The model shows strong performance, especially for the positive completion class
- Minor misclassifications are present, expected due to small dataset size

---

## 🧠 Key Learnings

- Regular weekly training shows a strong positive association with marathon completion
- Learned how to:
  - Split data into train and test sets
  - Fit a regression model
  - Interpret confusion matrices and classification reports
  - Evaluate model performance beyond accuracy alone

---

## ⚠️ Limitations

- Dataset is synthetic and limited in size
- Linear regression is a simple baseline model
- Results should not be interpreted as real-world athletic or medical advice

---

## 🚀 Future Improvements

- Generate custom synthetic data programmatically
- Try Logistic Regression for binary classification
- Add ROC curve and AUC score analysis
- Increase dataset size for more robust evaluation

---

## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn
