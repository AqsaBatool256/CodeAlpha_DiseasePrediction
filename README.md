# 🩺 Disease Prediction using Machine Learning

A machine learning classification project that uses **Logistic Regression** to classify breast cancer cases using the Breast Cancer Wisconsin dataset available through Scikit-learn.

## 📌 Project Overview

This project demonstrates a complete beginner-friendly machine learning workflow, including:

* Dataset loading and exploration
* Data preprocessing
* Train-test splitting
* Logistic Regression model training
* Model evaluation
* Confusion matrix analysis
* ROC-AUC evaluation

The project was originally developed as part of my **CodeAlpha Machine Learning internship**.

## 📂 Dataset

The project uses the built-in **Breast Cancer Wisconsin Diagnostic dataset** from Scikit-learn.

* **Samples:** 569
* **Features:** 30
* **Target:** Binary classification
* **Missing values:** None

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 🤖 Machine Learning Model

### Logistic Regression

The dataset was divided into:

* **Training set:** 455 samples
* **Testing set:** 114 samples

The Logistic Regression model was trained with `max_iter=10000`.

## 📊 Model Performance

The model achieved:

| Metric   |     Result |
| -------- | ---------: |
| Accuracy | **95.61%** |
| ROC-AUC  | **0.9977** |

### Classification Report

| Class | Precision | Recall | F1-Score |
| ----- | --------: | -----: | -------: |
| 0     |      0.97 |   0.91 |     0.94 |
| 1     |      0.95 |   0.99 |     0.97 |

### Confusion Matrix

```text
[[39  4]
 [ 1 70]]
```

These results are from the notebook run performed locally using the project environment.

## 🔄 Project Workflow

```text
Load Dataset
     ↓
Explore Dataset
     ↓
Check Missing Values
     ↓
Prepare Features & Target
     ↓
Train-Test Split
     ↓
Train Logistic Regression
     ↓
Generate Predictions
     ↓
Evaluate Model
     ↓
Accuracy + Classification Report
     ↓
Confusion Matrix + ROC-AUC
```

## 📁 Project Files

* `disease_prediction_code_alpha.ipynb` — Complete Jupyter Notebook
* `README.md` — Project documentation
* `.gitignore` — Git ignored files and environment configuration

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/AqsaBatool256/CodeAlpha_DiseasePrediction.git
```

### 2. Open the project

```bash
cd CodeAlpha_DiseasePrediction
```

### 3. Install the required libraries

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### 4. Open the notebook

```bash
jupyter notebook disease_prediction_code_alpha.ipynb
```

You can also open the notebook directly using **VS Code** with the Jupyter extension.

## 🎯 Learning Outcomes

Through this project, I practiced:

* Data exploration with Pandas
* Numerical data processing with NumPy
* Machine learning classification
* Logistic Regression
* Model evaluation
* Classification metrics
* Confusion matrix interpretation
* ROC-AUC analysis
* Working with Jupyter Notebooks
* Managing projects with Git and GitHub

## 👩‍💻 Author

**Aqsa Batool Saqib**

BS Computer Science Student | AI & Machine Learning Enthusiast | Python Developer | Cloud Computing Learner

* 💼 [LinkedIn](https://www.linkedin.com/in/aqsabatoolsaqib/)
* 🌐 [Portfolio](https://aqsabatool256.github.io/)
* 💻 [GitHub](https://github.com/AqsaBatool256)

---

⭐ If you find this project useful, feel free to explore the repository and connect with me.
