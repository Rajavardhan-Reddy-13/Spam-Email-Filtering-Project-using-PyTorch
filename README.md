# Spam-Email-Filtering-Project-using-PyTorch

This project implements a **binary classification system** that detects whether an email is **spam or not spam** using the [UCI Spambase dataset](https://archive.ics.uci.edu/ml/datasets/spambase). The classifier is trained using **Logistic Regression** in both **PyTorch** and **Scikit-learn** to compare performance.

## ✨ Project Highlights

- Implements logistic regression from scratch using **PyTorch**
- Compares accuracy with **Scikit-learn**’s logistic regression
- Performs **z-score normalization** for feature scaling
- Uses **custom PyTorch Dataset and DataLoader** for mini-batch training
- Plots training loss, test loss, and accuracy over epochs
- Visualizes spam vs legitimate prediction probabilities

---

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository – Spambase Dataset](https://archive.ics.uci.edu/ml/datasets/spambase)
- **Features**: 57 real-valued features per email
- **Label**: 1 = spam, 0 = non-spam

---

## 🛠️ Technologies Used

| Tool           | Purpose                          |
|----------------|----------------------------------|
| Python         | Programming language             |
| PyTorch        | Custom logistic regression model |
| Scikit-learn   | Benchmark logistic regression    |
| Matplotlib     | Visualization                    |
| NumPy, Pandas  | Data manipulation and loading    |

---
