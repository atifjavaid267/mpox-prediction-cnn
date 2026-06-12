# MonkeyPox Prediction using CNN
A reproducible machine learning pipeline for Mpox clinical prediction using CNN architecture.

## 1. Dataset

This project uses the Monkeypox Patients Dataset available on Kaggle:

Dataset Link:
https://www.kaggle.com/datasets/muhammad4hmed/monkeypox-patients-dataset/data

### Dataset Overview

This is a synthetic dataset generated based on the study:

Clinical features and novel presentations of human monkeypox in a central London centre during the 2022 outbreak: descriptive case series published by The BMJ.

The dataset contains records for 25,000 patients, including clinical symptoms and risk factors associated with Mpox infection. Each record includes a target variable indicating whether the patient was diagnosed with Mpox.

### Features
- Patient_ID
- Systemic Illness
- Rectal Pain
- Sore Throat
- Penile Oedema
- Oral Lesions
- Solitary Lesion
- Swollen Tonsils
- HIV Infection
- Sexually Transmitted Infection

### Target Variable
- MonkeyPox
    - Positive
    - Negative

### Dataset Characteristics
25,000 patient records
Boolean and categorical features
Binary classification problem
Synthetic data generated from published clinical observations