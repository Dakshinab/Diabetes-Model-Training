# Diabetes-Model-Training
Predict diabetes risk: A machine learning application with interactive visualizations and real-time analysis.
# Diabetes Prediction App with Streamlit

![Streamlit App](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

A machine learning application that predicts diabetes risk based on patient health metrics, deployed using Streamlit.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Training](#model-training)
- [Deployment](#deployment)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project demonstrates a complete machine learning pipeline from data exploration to model deployment. It includes:
- Exploratory data analysis of the Diabetes dataset
- Training and evaluation of multiple machine learning models
- An interactive Streamlit web application
- Deployment to Streamlit Cloud

## Dataset
The Pima Indians Diabetes Dataset contains health metrics for 768 patients and whether they developed diabetes within five years.

**Features:**
1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skin fold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age in years
9. Outcome: Class variable (0 or 1)

Source: [Kaggle Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## Features
- **Data Exploration**: View dataset statistics and raw data
- **Visualizations**: Interactive charts showing feature distributions and correlations
- **Model Prediction**: Input form for making diabetes risk predictions
- **Model Evaluation**: Performance metrics and confusion matrix
- **Responsive Design**: Works on both desktop and mobile devices

## Installation
To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction
