# Heart Disease Prediction Using Logistic Regression

## Overview

This project uses a logistic regression model to predict the presence of heart disease in patients based on several medical attributes. The goal is to build a predictive model that can help identify individuals at risk of heart disease.

## Dataset

The dataset used in this project is the **Heart Disease Data** from the UCI Machine Learning Repository. It contains 303 entries with 14 attributes, which are:

- **age**: Age of the patient
- **sex**: Sex of the patient (1 = male, 0 = female)
- **cp**: Chest pain type (0-3)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0-2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- **target**: Diagnosis of heart disease (1 = disease, 0 = no disease)

## Project Structure

- `heart_disease_data.csv`: The dataset file containing all the observations and attributes.
- `heart_disease_prediction.ipynb`: The Jupyter Notebook file with the data preprocessing, model training, and prediction logic.
- `README.md`: This file providing an overview of the project.

## Acknowledgments
UCI Machine Learning Repository for providing the Heart Disease dataset.
The developers of the libraries used in this project.

## Getting Started

### Prerequisites

Ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`

You can install them using pip if they are not already installed:

```bash
pip install pandas numpy scikit-learn

