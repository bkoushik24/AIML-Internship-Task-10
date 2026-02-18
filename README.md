# AIML-Internship-Task-10
K-Nearest Neighbors (KNN) implementation for handwritten digit classification using the Sklearn Digits dataset, including hyperparameter tuning, confusion matrix analysis, and accuracy comparison.
✍️ Handwritten Digit Classification using KNN
📌 Project Overview

This project implements a K-Nearest Neighbors (KNN) classifier to recognize handwritten digits (0–9) using the Sklearn Digits dataset. The objective is to classify grayscale 8x8 pixel digit images into their respective numerical labels.

The project demonstrates how distance-based learning works and how selecting the correct value of K impacts model performance.

📊 Dataset Information

Dataset: Sklearn Digits Dataset

Total Samples: 1797

Features: 64 (8x8 pixel flattened image)

Target Classes: 10 (Digits 0–9)

Each image is:

8x8 grayscale

Converted into 64 numerical pixel values

⚙️ Technologies Used

Python

NumPy

Matplotlib

Scikit-learn

🔄 Project Workflow

1️⃣ Load dataset using load_digits()
2️⃣ Explore dataset shape and structure
3️⃣ Visualize sample digit images
4️⃣ Split dataset into training and testing sets
5️⃣ Apply feature scaling using StandardScaler
6️⃣ Train KNN model with K=3
7️⃣ Experiment with multiple K values (3, 5, 7, 9)
8️⃣ Plot Accuracy vs K graph
9️⃣ Generate confusion matrix
🔟 Display predicted test images

📈 Model Optimization

Different values of K were tested:

K = 3

K = 5

K = 7

K = 9

An Accuracy vs K graph was plotted to select the best-performing value.

🎯 Key Learnings

Importance of feature scaling in distance-based models

Effect of K value on bias-variance tradeoff

How KNN performs multi-class classification

Interpreting confusion matrix for misclassified digits

Visualizing image classification results
