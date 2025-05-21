# 💳 Credit Score Classification using Machine Learning

## 📄 Overview / Abstract

This project focuses on building a classification model to predict a customer's credit score category—**Poor**, **Standard**, or **Good**—using various financial and demographic features. The project leverages classical machine learning algorithms and is based on the [Credit Score Classification dataset](https://www.kaggle.com/datasets/parisrohan/credit-score-classification) available on Kaggle.

---

## 📊 Dataset Description

The dataset contains customer-level data including:

- Numerical and categorical features like `Age`, `Annual Income`, `NumBankAccounts`, `CreditMix`, `Payment of Minimum Amount`, etc.
- The target variable: `Credit Score` with 3 classes: **Poor**, **Standard**, and **Good**

Dataset source: [Kaggle - Credit Score Classification](https://www.kaggle.com/datasets/parisrohan/credit-score-classification)

---

## 🧱 Model Architecture

The notebook evaluates multiple classical machine learning models including:
Preprocessing steps include:

- Handling missing values
- Encoding categorical features
- Feature scaling using StandardScaler

---

## 🏋️ Training Details

- **Model**: Deep Neural Network 
- **Architecture**:
  - `Dense(128, activation='relu', input_shape=(num_features,))`
  - `Dense(64, activation='relu')`
  - `Dense(32, activation='relu')`
  - `Dense(3, activation='softmax')` — for multi-class classification (Poor, Standard, Good)
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy
---

## 📈 Results & Evaluation

- **Test Accuracy**: Approximately **75%**
- **Evaluation Techniques**:
  - Accuracy metric on test set
  - Classification report (Precision, Recall, F1-score)
  - Confusion matrix visualization
- The model performs well across all three credit score categories and shows strong generalization.




