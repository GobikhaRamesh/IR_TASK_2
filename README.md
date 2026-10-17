# Medical Text Classification Using Machine Learning

## 1. Project Overview

This project focuses on classifying medical transcriptions into different medical specialties using machine learning algorithms. It is developed as part of **Information Retrieval – Task 2: Text Classification Battle – Compare, Analyze and Defend**.

The project compares four machine learning algorithms to determine which performs best at classifying medical text.

## 2. Objectives

* To preprocess and analyze medical text data.
* To convert textual data into numerical features using TF-IDF.
* To implement four machine learning classification algorithms.
* To evaluate and compare model performance.
* To visualize results using graphs and confusion matrices.
* To identify the best-performing model using evaluation metrics.

## 3. Dataset

**Dataset:** Medical Transcriptions Dataset

The dataset contains medical transcription text and corresponding medical specialty labels.

Main columns used:

* `transcription` – Text of the medical transcription.
* `medical_specialty` – Target category representing the medical specialty.

Dataset source: [Medical Transcriptions Dataset on Kaggle](https://www.kaggle.com/datasets/tboyle10/medicaltranscriptions)

## 4. Technologies Used

* Python
* Google Colab
* Pandas and NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* TF-IDF Vectorization

## 5. Machine Learning Algorithms

### Decision Tree

Uses a tree-based structure to learn decision rules and classify medical transcriptions.

### K-Nearest Neighbors (KNN)

Classifies text based on the categories of its nearest training examples using cosine distance.

### Support Vector Machine (SVM)

Uses a linear decision boundary to distinguish between medical specialties.

### Naive Bayes

Uses word-feature probabilities to predict the most likely medical specialty.

## 6. Methodology

1. Load the medical transcription dataset.
2. Remove records with missing text or category labels.
3. Separate the text features and target labels.
4. Split the dataset into training and testing sets.
5. Convert text into numerical features using TF-IDF.
6. Train the four machine learning classifiers.
7. Generate predictions on the test set.
8. Evaluate and compare model performance.
9. Visualize
