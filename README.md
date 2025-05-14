# Choronic Kidney Disease Classification

This project aims to develop a machine learning model to classify the presence of Chronic Kidney Disease (CKD) based on clinical and biological features. The model leverages a Random Forest classifier for robust and accurate predictions. The project includes the following steps:

1- **Data Collection:** The CKD dataset contains 25 clinical features such as age, blood pressure, specific gravity, albumin, sugar, red blood cells, and more.

2- **Data Visualization:** Various data visualization techniques are applied to understand feature distribution and relationships. This includes pie charts for class distribution, histograms for feature analysis, correlation heatmaps to observe inter-feature relationships, and violin plots for class-wise distribution comparisons.

3- **Data Preprocessing:** Categorical features are encoded using Label Encoding. The dataset is then split into training and testing sets to enable effective model evaluation.

4- **Model Building and Training:** A Random Forest Classifier is used for the classification task. The model is trained on the training set, learning patterns that distinguish between CKD and non-CKD cases.

5- **Model Evaluation:** The model's performance is assessed using precision, recall, and F1-score to ensure both the accuracy and robustness of predictions, especially given the medical importance of false negatives and positives.


