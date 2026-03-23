# Machine Learning & Data Mining: Sleep Health Prediction

## Objective
This project implements an end-to-end machine learning pipeline using **Julia** on the Kaggle 'Sleep Health and Lifestyle' dataset. The primary goal is to predict the presence of sleep disorders (Insomnia and Sleep Apnea) based solely on daily lifestyle data, eliminating the immediate need for clinical medical tests.

## Tools & Technologies
* **Language:** Julia
* **Supervised Learning (Classification):** Simple Linear Regression, Multiple/Logistic Regression, K-Nearest Neighbors (KNN), Decision Trees, Random Forest
* **Unsupervised Learning (Clustering):** K-Means, K-Medoids, DBSCAN
* **Evaluation Metrics:** Confusion Matrices, Accuracy, F1 Scores, RMSD

## Methodology
1. **Predictive Modeling:** Trained multiple classification models to detect sleep disorders. Addressed potential overfitting risks by rigorously evaluating models using Confusion Matrices and RMSD scores.
2. **Outlier Detection & Clustering:** Applied unsupervised clustering algorithms (K-Means and K-Medoids) to find natural groupings in patient data. Implemented the density-based **DBSCAN** algorithm specifically to identify and manage noisy data and outliers within the dataset.

## Results
* Successfully developed predictive models capable of classifying sleep disorders based on lifestyle factors.
* Effectively mapped the underlying structure of the dataset and isolated outliers through density-based clustering, ensuring the robustness of the classification models.
