# 🧠 Facial Emotion Recognition — Comparative Analysis

## 📌 Overview
Comparative study of CNN and SVM models for facial emotion recognition
across two real-world datasets (CK+ and RAF-DB). Includes full data 
preprocessing pipeline, model training, and performance evaluation.
Research published in Springer, 2024.

## 📦 Datasets Used
- **CK+** — Extended Cohn-Kanade Dataset
- **RAF-DB** — Real-world Affective Faces Database

## 🛠️ Tech Stack
Python | TensorFlow/Keras | Scikit-learn | Pandas | NumPy | Matplotlib

## 📊 Key Results

| Dataset | Model | Accuracy |
|---------|-------|----------|
| CK+     | CNN   | 96%      |
| CK+     | SVM   | 97%      |
| RAF-DB  | CNN   | 85%      |
| RAF-DB  | SVM   | 77%      |

CNN outperformed SVM on the more complex RAF-DB dataset,
