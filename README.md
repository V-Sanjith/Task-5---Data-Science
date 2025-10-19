# 🧠 Task 5 – Data Science Example  
**Project Title:** Consumer Complaint Text Classification  
**Author:** V. Sanjith  
**Date:** October 2025  

---

## 📘 Overview
This repository is part of the **Kaiburr Assessment 2025 – Task 5: Data Science Example**.  
The goal is to perform **text classification** on the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database) published by the U.S. Government.

Each complaint is classified into one of the following four categories:

| Label | Category |
|:--:|:--|
| 0 | Credit reporting, repair, or other |
| 1 | Debt collection |
| 2 | Consumer Loan |
| 3 | Mortgage |

---

## 🧩 Steps Implemented

### 1. Exploratory Data Analysis (EDA)
- Loaded and inspected the dataset.  
- Checked for missing values and class distribution.  
- Visualized most frequent words and top categories.  

### 2. Text Pre-Processing
- Converted text to lowercase.  
- Removed stop words, punctuation, and special symbols.  
- Tokenized and lemmatized text.  

### 3. Feature Engineering
- Used **TF-IDF Vectorization** to numerically represent complaint text.  
- Limited feature dimensions to optimize training time.  

### 4. Model Selection
Trained and compared multiple models:
- Logistic Regression  
- Naive Bayes  
- Random Forest  
- Support Vector Machine (SVM)  

### 5. Model Evaluation
- Compared accuracy, precision, recall and F1-score.  
- Visualized confusion matrices.  
- Selected the best performing model.  

### 6. Prediction
- Tested on unseen complaints.  
- Displayed predictions with class probabilities.  

---

## ⚙️ How to Run

### Option 1 – Local (Jupyter Notebook)

1. git clone https://github.com/V-Sanjith/Task-5---Data-Science.git

### Option 2 – Google Colab

1. Open `Task-5.ipynb` in Google Colab.  
2. Upload or connect the dataset.  
3. Run all cells from top to bottom.  

---

## 🖼️ Screenshots 
<img width="1919" height="1023" alt="image" src="https://github.com/user-attachments/assets/6a17d1fb-7523-4281-8995-7a443aed94e4" />

<img width="1222" height="753" alt="image" src="https://github.com/user-attachments/assets/675a33a3-63c9-42bd-ac0c-c815bdc39c69" />
<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/e3988ba5-03d3-41a1-9102-d8152a274e06" />
<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/dda182e1-2e03-4fb6-b58b-8b4e5a376438" />
<img width="1919" height="1067" alt="image" src="https://github.com/user-attachments/assets/4d79db40-09f7-4324-a58c-c6b312ced75b" />


---

## 🧾 Results Summary

| Model | Accuracy | F1-Score |
|--------|-----------|----------|
| Logistic Regression | ≈ 0.87 | ≈ 0.86 |
| Naive Bayes | ≈ 0.83 | ≈ 0.82 |
| Random Forest | ≈ 0.85 | ≈ 0.84 |
| SVM | ≈ 0.88 | ≈ 0.87 |

**Best Model:** Support Vector Machine (SVM)

---

## 📊 Conclusion

- Built a complete text processing and classification pipeline.  
- Compared multiple models for multi-class text classification.  
- Evaluated accuracy and performance metrics with clear visuals.  


---

## 📧 Contact

**Author:** V. Sanjith  
**GitHub:** [V-Sanjith](https://github.com/V-Sanjith)

