# K-Nearest Neighbors From Scratch 🧠📊

This repository contains **two machine learning projects implemented fully from scratch using Python**, with **zero ML libraries** for model building. The focus is on understanding how **K-Nearest Neighbors (KNN)** actually works under the hood—no shortcuts, no magic.

---

## 🚀 Projects Overview

### 1️⃣ Binary Classification – Breast Cancer Detection

A binary classification task where tumors are classified as:

* **Malignant (1)**
* **Benign (0)**

**Highlights**

* Custom KNN implementation (no `sklearn`)
* Feature scaling using **Min–Max normalization**
* Multiple distance metrics tested
* Performance analysis using accuracy, confusion matrix, precision & recall

📂 Files:

* `Breast_cancer_knn_binary_detection.ipynb`
* `Breast_cancer_knn_binary_report.pdf` 

---

### 2️⃣ Multi-Class Classification – CIFAR-10 Image Dataset

A classic **10-class image classification** problem using the CIFAR-10 dataset.

**Classes**
Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

**Highlights**

* Images flattened manually (32×32×3 → 3072 features)
* Pixel normalization to `[0,1]`
* Distance-based classification from scratch
* Evaluation using accuracy, confusion matrix, precision & recall

📂 Files:

* `Cifar-10_classification.ipynb`
* `Cifar-10_classification_report.pdf` 

---

## 📐 Distance Metrics Implemented

* **Euclidean Distance**
* **Manhattan Distance**
* **Minkowski Distance (p = 3)**
* **Cosine Distance**
* **Hamming Distance**

Each metric is implemented manually and evaluated across different values of **K**.

---

## 🧪 Experimental Setup

* Train/Test split: **80/20**
* Multiple values of **K**
* Accuracy vs K plots
* Comparative analysis of distance metrics

---

## 🛠 Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib

> No `scikit-learn`. Everything is built from the ground up.

---

## 📊 Key Takeaways

* Euclidean and Manhattan distances dominate for numerical data
* Cosine distance performs well for image data
* Hamming distance struggles with continuous features
* Small K → noisy but sharp
* Large K → smooth but biased

---

## 📌 Why This Repo?

If you actually want to **understand KNN instead of just importing it**, this repo is for you. Solid for:

* ML fundamentals
* Academic assignments
* Interview prep
* Conceptual clarity

---

## 🧠 Author

**Bhargav**
Student | Machine Learning & Numerical Methods

---

## ⭐ Final Note

If you found this useful, **drop a star**.
If you’re studying ML seriously—this is baseline knowledge. No excuses.

Stay curious. Stay dangerous. 🔥
