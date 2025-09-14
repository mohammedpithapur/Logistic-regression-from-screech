---

# Logistic Regression from Scratch

This repository implements **Logistic Regression** from scratch in Python using only **NumPy**.
The project demonstrates how to build a binary classifier step by step without relying on libraries like `scikit-learn`.

---

## 📌 Features

* Implements:

  * Sigmoid function
  * Cost function with L2 regularization
  * Gradient computation
  * Gradient Descent optimizer
* Trains on the **Breast Cancer dataset**
* Includes data preprocessing (normalization, train-test split)
* Plots learning progress (cost vs. iterations)
* Compares predictions with true labels

---

## 📂 Project Structure

```
├── logistic_regression_from_screech.ipynb   # Jupyter Notebook with implementation
├── breast-cancer.csv                        # Data Set
├── README.md                                # Project documentation
```

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/logistic-regression-scratch.git
cd logistic-regression-scratch
pip install -r requirements.txt
```

**Requirements:**

* Python 3.8+
* NumPy
* pandas
* matplotlib
* scikit-learn

---

## 📊 Dataset

We use the **Breast Cancer dataset**.
It contains 30 features and a binary target:

* `M` → Malignant (1)
* `B` → Benign (0)

---

## 🚀 Usage

Open the notebook and run all cells:

```bash
jupyter notebook logistic_regression_from_screech.ipynb
```

---

## 📈 Results

* The model learns to separate malignant vs benign samples.
* Default decision boundary = **0.5** threshold on predicted probability.
* Achieves high accuracy on test data.

Example training output:

```
Iteration    0: Cost 20.45
Iteration  100: Cost  0.59
Iteration  200: Cost  0.42
...
```

---

## 🔮 Next Steps

* Add ROC/PR curve evaluation
* Try different learning rates & regularization strengths
* Extend to **multiclass logistic regression (softmax)**

---

## 📜 License

This project is licensed under the MIT License.

---

