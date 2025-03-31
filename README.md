# Predicting Heart Disease Using Machine Learning

This repository contains a machine learning project that aims to predict heart disease based on patient clinical attributes. The project is developed as part of a structured Udemy course and uses Python, Jupyter Notebook, and various data science libraries.

## Project Overview

The goal of this project is to build and evaluate a machine learning model capable of predicting whether or not a patient has heart disease. The project walks through the entire process from problem definition to data exploration, model building, and experimentation.

## Table of Contents

- [Problem Definition](#problem-definition)
- [Data](#data)
- [Evaluation](#evaluation)
- [Features](#features)
- [Approach](#approach)
- [Usage](#usage)
- [Course Information](#course-information)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Problem Definition

Given clinical parameters about a patient, the objective is to predict whether the patient has heart disease. The project is structured into the following phases:
1. Problem Definition
2. Data Exploration
3. Evaluation
4. Feature Engineering
5. Model Building
6. Experimentation

## Data

The dataset used for this project is based on the Cleveland Heart Disease dataset from the CU Machine Learning Repository, with the specific version obtained from Kaggle.

- **Original dataset:** [CU Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Kaggle version:** [Kaggle Dataset](https://www.kaggle.com/c/heart-disease-uci/data)

## Evaluation

The project will be considered a success if the predictive model reaches at least **95% accuracy** during the proof-of-concept phase.

## Features

The dataset contains the following attributes:

- **age:** Age of the patient.
- **sex:** Gender of the patient (1 = male, 0 = female).
- **cp:** Type of chest pain (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic).
- **trestbps:** Resting blood pressure (in mmHg).
- **chol:** Serum cholesterol (in mg/dl).
- **fbs:** Fasting blood sugar (1 = >120 mg/dl, 0 = otherwise).
- **restecg:** Resting ECG results (0 = normal, 1 = ST-T wave abnormality, 2 = left ventricular hypertrophy).
- **thalach:** Maximum heart rate achieved.
- **exang:** Exercise-induced angina (1 = yes, 0 = no).
- **oldpeak:** ST depression induced by exercise relative to rest.
- **slope:** Slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping).
- **ca:** Number of major vessels (0–3) colored by fluoroscopy.
- **thal:** Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect).
- **num:** Diagnosis of heart disease (0 = absence, 1, 2, 3, 4 = presence).

## Approach

This project follows a systematic approach:

1. **Problem Definition:** Understand and outline the problem.
2. **Data Exploration:** Load and visualize the dataset.
3. **Evaluation:** Define success metrics (targeting 95% accuracy).
4. **Feature Engineering:** Analyze and prepare the dataset's features.
5. **Model Building:** Apply various machine learning algorithms.
6. **Experimentation:** Tune and assess model performance.

## Usage

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nechanie/UdemyAIML-Supervised-Learning-Classification-Project.git
   ```
2. **Navigate to the project directory:**
    ```bash
    cd your-repo-name
    ```
3. **(Optional) Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    # On Windows:
    venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```
4. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5. **Launch the Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

## Course Information

This project is part of the **Complete A.I. & Machine Learning, Data Science Bootcamp** on Udemy.  
Learn Data Science, Data Analysis, Machine Learning (Artificial Intelligence), and Python with TensorFlow, Pandas, and more!

Created by **Andrei Neagoie** and **Daniel Bourke**.

## License

This project is licensed under the MIT License.

See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- **Dataset Providers:** Thanks to the creators of the Cleveland Heart Disease dataset and the Kaggle community.
- **Course Instructors:** Appreciation for Andrei Neagoie and Daniel Bourke for their guidance and instructional content.