# NLP Disaster Tweets Classification using RNN

This project focuses on building a Recurrent Neural Network (RNN) model to classify tweets as disaster-related or non-disaster-related. The objective is to apply Natural Language Processing (NLP) techniques along with deep learning to solve a real-world text classification problem.

---

## 🚀 Project Overview

Social media platforms like Twitter are often used to report real-time disasters. However, not all tweets containing disaster-related keywords actually refer to real emergencies. This project aims to build a robust classification model to distinguish between real disaster tweets and unrelated content.

The workflow covers the complete NLP pipeline:
- Data preprocessing and cleaning
- Text tokenization and padding
- Exploratory Data Analysis (EDA)
- Model building using RNN
- Model evaluation and performance analysis

---

## 🧠 Model Architecture

The deep learning model includes:
- Embedding Layer
- Simple RNN Layer
- Dense Layers for classification
- Sigmoid activation for binary output

The model is trained using binary cross-entropy loss and optimized using Adam optimizer.

---

## 📊 Evaluation Metrics

Performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special attention is given to recall and F1-score since disaster detection is a sensitive classification task where false negatives can be costly.

---

## 🛠️ Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib / Seaborn
- TensorFlow / Keras
- Scikit-learn

---

## 📂 Repository Structure
