# ⚡ SVM Classifier From Scratch

A complete implementation of a **Support Vector Machine (SVM)** classifier from scratch using Python without relying on Scikit-Learn's SVC for the core algorithm.

This project demonstrates the mathematical foundations of SVM, including hyperplane optimization, margin maximization, and classification using support vectors.

---

## 📌 Project Overview

Support Vector Machine (SVM) is one of the most powerful supervised machine learning algorithms used for classification problems.

Instead of using pre-built machine learning libraries, this project implements the core SVM algorithm manually to understand:

- Margin Maximization
- Hyperplane Formation
- Support Vectors
- Binary Classification
- Optimization Process

The goal is to classify data points into different categories while maximizing the separation margin between classes.

---

## 🎯 Features

✅ SVM implemented from scratch

✅ Binary classification support

✅ Hyperplane optimization

✅ Support vector identification

✅ Decision boundary visualization

✅ Educational implementation for understanding SVM internals

✅ No dependency on pre-built SVM models

---

## 🧠 How SVM Works

SVM tries to find an optimal hyperplane that maximizes the distance between two classes.

### Objective Function

Minimize:

```
1/2 ||w||²
```

Subject to:

```
yi(w·xi + b) ≥ 1
```

Where:

- `w` = Weight Vector
- `b` = Bias
- `xi` = Input Feature Vector
- `yi` = Class Label

The data points closest to the decision boundary are called **Support Vectors**.

---

## 📊 Workflow

```text
Dataset
   │
   ▼
Data Preparation
   │
   ▼
Feature Extraction
   │
   ▼
SVM Training
   │
   ▼
Hyperplane Optimization
   │
   ▼
Support Vector Selection
   │
   ▼
Prediction
   │
   ▼
Evaluation
```

---

## 🛠️ Tech Stack

### Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib

### Environment

- Jupyter Notebook

---

## 📂 Project Structure

```text
SVM-classifier-from-scratch/
│
├── svm_classifier.ipynb
├── dataset.csv
├── README.md
│
├── outputs/
│   ├── decision_boundary.png
│   ├── support_vectors.png
│   └── evaluation_results.png
│
└── requirements.txt
```

---

## 📈 Visualization

### Training Data

The classifier learns to separate two classes using a maximum-margin hyperplane.

```text
Class A ● ● ● ●
---------------- Hyperplane
Class B ○ ○ ○ ○
```

### Decision Boundary

The model identifies:

- Optimal Hyperplane
- Positive Margin
- Negative Margin
- Support Vectors

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/anshulnangru/SVM-classifier-from-scratch.git
```

Move into project directory:

```bash
cd SVM-classifier-from-scratch
```

Install dependencies:

```bash
pip install numpy pandas matplotlib
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 💻 Example Usage

```python
svm = SVM()

svm.fit(X_train, y_train)

predictions = svm.predict(X_test)
```

Output:

```text
Class 1
```

---

## 📊 Evaluation Metrics

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🎓 Learning Outcomes

Through this project I learned:

- Mathematics behind SVM
- Convex Optimization Concepts
- Hyperplane Formation
- Support Vector Selection
- Machine Learning Model Development
- Data Visualization

---

## 🔥 Why Build SVM From Scratch?

Most machine learning projects directly use Scikit-Learn.

Building SVM manually provides a deeper understanding of:

- How optimization works
- Why support vectors matter
- How margins affect classification
- Internal working of ML algorithms

This project focuses on learning the algorithm rather than simply using a library.

---

## 🔮 Future Improvements

- Soft Margin SVM
- Kernel SVM
- Polynomial Kernel
- RBF Kernel
- Multi-Class Classification
- Streamlit Deployment
- Performance Optimization

---

## 👨‍💻 Author

**Anshul Nangru**

BCA Student | Machine Learning Enthusiast

GitHub:
https://github.com/anshulnangru

LinkedIn:
https://linkedin.com/in/anshulnangru

---

## ⭐ Show Your Support

If you found this project useful, consider giving it a star ⭐ on GitHub.
