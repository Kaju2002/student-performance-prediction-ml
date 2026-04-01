# 🎓 Student Dropout Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict **student dropout in online education** using Machine Learning techniques.

Early prediction of at-risk students helps institutions provide timely support, improving student success and reducing dropout rates.

---

## 📊 Dataset

We used the **Open University Learning Analytics Dataset (OULAD)**.

🔗 Dataset Link:
https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset

### 📁 Dataset Components

- 👤 **studentInfo** – student demographics & final results
- 📝 **studentAssessment** – assessment scores
- 💻 **studentVle** – online learning activity
- 📅 **studentRegistration** – registration & withdrawal info

---

## ⚙️ Data Preprocessing

A complete preprocessing pipeline was developed:

- ✔ Data cleaning (fixing data types, handling missing values)
- ✔ Feature engineering (scores, clicks, activity, submissions)
- ✔ Merging multiple datasets into one
- ✔ Encoding categorical variables
- ✔ Feature selection using correlation analysis
- ✔ Train-test split (80/20 with stratification)
- ✔ Feature scaling (for KNN model)
- ✔ SMOTE applied **only on training data** (to avoid data leakage)

---

## 🤖 Machine Learning Models

Four supervised learning algorithms were implemented:

1. 🌳 Decision Tree
2. 🌲 Random Forest
3. ⚡ XGBoost
4. 📍 K-Nearest Neighbors (KNN)

---

## 📈 Model Performance

| Model            | Accuracy   | Precision  | Recall     | F1 Score   | ROC-AUC    |
| ---------------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| ⚡ XGBoost       | **89.52%** | 91.77%     | **88.06%** | **89.87%** | **96.72%** |
| 🌲 Random Forest | 89.32%     | 92.12%     | 87.25%     | 89.62%     | 96.43%     |
| 📍 KNN           | 88.85%     | **93.22%** | 85.07%     | 88.96%     | 95.81%     |
| 🌳 Decision Tree | 88.39%     | 90.74%     | 86.87%     | 88.76%     | 93.83%     |

---

## 🏆 Key Findings

- ⚡ **XGBoost achieved the best overall performance**
- 🌲 Random Forest showed strong and stable results
- 📍 KNN achieved the highest precision (most reliable predictions)
- 📉 Decision Tree had lower performance but is easier to interpret

---

## 🔍 Insights

- 📊 Academic performance (scores) is the strongest predictor
- 💻 Student engagement (clicks, activity) is critical
- 🚨 Early withdrawal is a key indicator of dropout

---

## 🧠 Technologies Used

- Python 🐍
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn

## 📁 Project Structure

```
student-performance-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_decision_tree.ipynb
│   ├── 03_knn.ipynb
│   ├── 04_xgboost.ipynb
│   └── 05_random_forest.ipynb
│
├── report/
│   ├── images/
│   └── report.pdf
│
├── docs/ (optional)
├── README.md
├── requirements.txt
└── .gitignore
```

## 👥 Team Members

- IT22224002 – U Kajanthan
- IT22251664 – H.M.N.T. Bandara
- IT22267740 – K.T. Olivea
- IT22211750 – W.N.N. de Silva

---

## 🎥 Project Demo

🔗 (Add your YouTube video link here)

---

## 🚀 Conclusion

This project demonstrates that Machine Learning can effectively predict student dropout using real-world educational data.

Ensemble methods such as **XGBoost and Random Forest** provide the best performance and can support early intervention strategies in online learning environments.

---

## ⭐ Highlights

- ✔ Complete preprocessing pipeline
- ✔ No data leakage (SMOTE applied correctly)
- ✔ Multiple model comparison
- ✔ Strong evaluation using multiple metrics

---

### 🙌 Thank You!
