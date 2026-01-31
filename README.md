# Business Data Science & Machine Learning Portfolio

**Institution:** ESSEC Business School  
**Focus:** Machine Learning Algorithms, Data Engineering, and Business Applications  
**Tools:** Python, NumPy, Pandas, Scikit-Learn, Matplotlib/Seaborn

---

## 🚀 Overview

This repository contains a collection of Machine Learning projects and algorithmic implementations developed during the **Business Data Science** course. 

The goal of this portfolio is to bridge the gap between **mathematical theory** (building algorithms from scratch) and **practical business application** (end-to-end prediction pipelines). It moves from understanding the core mechanics of optimization to deploying robust models on real-world datasets.

## 📂 Repository Contents

### 1. End-to-End Prediction: Adult Census Income
**File:** `Adult_Income_Prediction.ipynb`
A complete Data Science pipeline applied to the UCI Adult Dataset to predict individuals earning >$50K/year.
* **Techniques:** Data Cleaning, Exploratory Data Analysis (EDA), Feature Engineering (One-Hot Encoding), Standard Scaling.
* **Model:** Logistic Regression with Scikit-Learn pipelines.
* **Outcome:** Achieved ~85% Accuracy with detailed evaluation metrics (ROC-AUC, Confusion Matrix).

### 2. Algorithmic Optimization: Gradient Descent & Vectorization
**File:** `Logistic_Regression_Optimization.ipynb`
A "deep dive" into the mathematics of optimization. This notebook implements Logistic Regression **from scratch** (without Scikit-Learn) to demonstrate:
* **Mathematics:** Manual implementation of the Sigmoid activation and Cost Function.
* **Engineering:** Comparison between iterative loops and **Vectorized Linear Algebra** (NumPy).
* **Performance:** Proved that vectorization yields a **~500x speedup** in training time compared to standard loops.

### 3. Bias-Variance Tradeoff: Regularization (L2)
**File:** `Regularization_and_Overfitting.ipynb`
A visual study of model complexity and generalization.
* **Experiment:** Simulating non-linear data (microchip QA testing) and fitting High-Degree Polynomials.
* **Concept:** Visualizing the decision boundary of an Overfitted model vs. a Regularized model.
* **Key Takeaway:** Demonstrating how L2 Regularization (Ridge) penalizes weights to prevent overfitting and create robust decision boundaries.

---

## 📚 Course Scope & Theoretical Background

Beyond these implementations, the curriculum covered the intersection of Engineering and Business Strategy:

* **Supervised Learning:** Linear/Multiple Regression, Classification, Model Evaluation (Precision/Recall/F1).
* **Recommender Systems:** Analysis of Collaborative Filtering and Content-Based Filtering algorithms (Netflix, Amazon, Spotify use cases).
* **Large Language Models (LLMs):** Introduction to Generative AI and its business implications.
* **Data Visualization:** Communicating insights effectively using Python libraries.

---

## 🛠 Installation & Usage

To run these notebooks locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/Ketketm/Machine-Learning-Portfolio.git](https://github.com/Ketketm/Machine-Learning-Portfolio.git)
