# 🧬 Mice Protein Expression Classification

> Internship Project | EvoAstra Ventures Pvt Ltd  
> Author: Abhishek Gupta  
> Email: abhishekgp20004@gmail.com  

---

## 📘 Project Overview

This project focuses on using **machine learning** to classify mice into experimental groups based on **protein expression levels** in their brain cortex. The goal is to understand how genetic factors, treatments, and behaviors affect protein expressions — supporting biomedical research in areas like **Down syndrome** and **Alzheimer’s disease**.

---

## 🎯 Objectives

- 🧠 Classify mice into 8 groups using protein expression data.
- 🔍 Identify the most influential proteins contributing to classification.
- 📊 Enable data-driven insights for biomedical applications.

---

## 🗂️ Dataset Details

- **Source**: `Data_Cortex.csv`  
- **Samples**: 1080 mice  
- **Features**:
  - 77 continuous protein expression levels (e.g., DYRK1A_N, BDNF_N, Tau_N)
  - 5 categorical variables (Genotype, Treatment, Behavior, MouseID, Class)
- **Target**: `class` (8 unique groups combining genotype, treatment, and behavior)

---

## 🧹 Data Preprocessing

- 🔧 Handled missing values using **mean imputation**
- 🔢 Encoded categorical features with **Label Encoding**
- 📐 Scaled numerical features using **StandardScaler**
- 🧮 Verified class balance and feature distributions

---

## 📊 Exploratory Data Analysis (EDA)

- ✅ Distribution plots for protein levels
- 📦 Boxplots to visualize variation across classes
- 🔥 Correlation heatmap to detect highly related proteins

---

## 🤖 Models Used

| Model                | Accuracy |
|---------------------|----------|
| ✅ Random Forest     | 93%      |
| SVM (RBF Kernel)     | 88%      |
| K-Nearest Neighbors  | 86%      |
| Logistic Regression  | 85%      |

> Random Forest was chosen for its accuracy and interpretability.

---

## 🌟 Key Results

- **Top proteins** influencing classification:
  - DYRK1A, Tau, BDNF, SOD1, APP
- These proteins are consistent with biological research on:
  - 🧬 Down syndrome
  - 🧠 Alzheimer’s disease
  - 🔬 Brain function and signaling

---

## 🧩 Challenges

- Handling missing values across high-dimensional features
- Managing overlapping class combinations
- Explaining model outputs to non-technical stakeholders

---

## 🔮 Future Scope

- 🧬 Dimensionality reduction with PCA, Lasso, or RFE
- 🧠 Use deep learning models (MLPs, CNNs)
- 🧪 Expand to human protein datasets for medical applications
- 📖 Biological validation using published research

---

## 💻 Tools & Libraries

- Python 🐍
- scikit-learn
- Pandas, NumPy, Seaborn, Matplotlib
- Jupyter Notebook

---

## 📁 Folder Structure

