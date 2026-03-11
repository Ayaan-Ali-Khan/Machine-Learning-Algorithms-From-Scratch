# Machine Learning Algorithms From Scratch

A hands-on repository for **implementing core Machine Learning algorithms from first principles using Python and NumPy**.

This project focuses on understanding the **mathematics, optimization, and intuition behind machine learning algorithms** by building them **without high-level ML libraries such as scikit-learn or TensorFlow**.

Instead of treating algorithms as black boxes, the goal is to **open them up and understand every step of how they work.**

---

# Why Build Machine Learning Algorithms From Scratch?

Most modern ML workflows rely on powerful libraries like `scikit-learn`, `PyTorch`, or `TensorFlow`. While these tools are essential for real-world systems, they often hide the inner mechanics of algorithms.

Implementing algorithms from scratch helps you:

- Understand **how optimization actually works**
- Develop strong intuition about **gradients, loss functions, and convergence**
- Learn the **mathematical structure behind ML models**
- Debug models more effectively in real projects
- Prepare for **machine learning interviews and research**

When you implement algorithms yourself, concepts like **gradient descent, margins, regularization, and decision boundaries** become much clearer.

---

# Repository Contents

This repository currently contains implementations of foundational machine learning algorithms written using **only NumPy and core Python**.

## 1. Linear Regression From Scratch

![](/assets/linear_reg.png)

Implementation of the classical regression algorithm using **gradient descent optimization**.

**Concepts Covered**

- Hypothesis function
- Mean Squared Error (MSE)
- Gradient Descent
- Cost function minimization
- Model convergence

**What you will learn**

- How regression models learn parameters
- How gradients update model weights
- Why learning rate matters

---

## 2. Logistic Regression From Scratch

![](/assets/logistic_reg.png)

A full implementation of **binary classification using logistic regression**. See how the model fits the sigmoid.

**Concepts Covered**

- Sigmoid activation
- Log Loss / Binary Cross Entropy
- Gradient Descent
- Decision boundaries
- Probability interpretation of outputs

**What you will learn**

- How classification models estimate probabilities
- Why logistic regression works for classification
- How loss functions differ between regression and classification

---

## 3. Support Vector Machine (SVM) From Scratch

![](/assets/svm_cls.png)

Implementation of **maximum-margin classification** using Support Vector Machines.

**Concepts Covered**

- Margin maximization
- Hinge loss
- Hard vs Soft margin
- Regularization
- Decision boundary optimization

**What you will learn**

- Why SVM focuses on **support vectors**
- How margins improve generalization
- The intuition behind hinge loss optimization

---

# Key Characteristics of This Repository

- Implemented using **NumPy only**
- Step-by-step algorithm construction
- Clear notebook explanations
- Mathematical intuition included
- Visualization of decision boundaries

This repository is designed for:

- Machine Learning students
- Beginners learning ML fundamentals
- Anyone preparing for **ML interviews**
- Developers wanting deeper understanding of ML algorithms

---

# Algorithms Planned Next

This repository will continue expanding with more classical ML algorithms implemented from scratch.

Planned implementations include:

- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Trees
- Random Forests
- Gradient Boosting
- Kernel SVM
- Principal Component Analysis (PCA)

---


# Who Is This Repository For?

This repository is ideal if you want to:

- Learn **machine learning deeply**
- Understand **how algorithms actually work internally**
- Move beyond simply calling `.fit()` and `.predict()`
- Build strong foundations for **Deep Learning and advanced ML**

---

# If You Find This Useful

If this repository helps you understand machine learning better:

⭐ Star the repository  
🍴 Fork it to experiment with your own implementations  
📢 Share it with other ML learners

---

***Learning machine learning is not just about using libraries.  
It is about understanding the ideas behind them.***