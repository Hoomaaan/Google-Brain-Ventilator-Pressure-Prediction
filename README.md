# Google Brain Ventilator Pressure Prediction

**Overview**

This repository contains code and resources for a project focused on improving mechanical ventilator control using machine learning algorithms. The project aims to optimize ventilator settings based on patient lung characteristics, ultimately enhancing patient outcomes and reducing clinician burden.

**Motivation**

Respiratory failure is a critical condition often requiring mechanical ventilation to support breathing. However, manual adjustment of ventilator settings can be challenging and time-consuming for healthcare providers. By leveraging machine learning techniques, we seek to automate and optimize ventilator control, leading to more personalized and efficient care for patients.

**Features**

Data Preprocessing: Code for preprocessing the dataset, including data cleaning, feature engineering, and splitting into training and test sets.
Model Training: Implementation of various machine learning models, including Decision Tree, Random Forest, Support Vector Machine, Polynomial Regression, and K-Nearest Neighbors, using scikit-learn.
Model Evaluation: Evaluation of model performance using Mean Absolute Error (MAE) as the primary metric.
Results Analysis: Analysis of model results, comparison of performance, and identification of the most effective algorithms for ventilator control.

**Results**

Based on our analysis, Random Forest emerged as the top-performing model for ventilator control, demonstrating superior accuracy on test data. However, K-Nearest Neighbors also showed promise with competitive performance and fast training times. Future research will focus on further validating these findings and integrating the models into clinical practice.

![image](https://github.com/Hoomaaan/Google-Brain-Ventilator-Pressure-Prediction/assets/33916130/3d05221b-72b5-4b40-8595-ffdd2371909d)


main_small.ipynb: Jupyter notebook containing the main code for the project.
Enhancing Patient Care with Machine Learning-nontechnical.pdf: Non-technical report providing an overview of the project, its objectives, and the potential impact on patient care.
Leveraging Machine Learning for Optimal Ventilator Control-technical.pdf: Technical report detailing the methodology, results, and analysis of the project.

