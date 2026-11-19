# Automatic-Diagnosis-of-the-12-Lead-ECG-Using-Machine-Learning-
Machine Learning-based ECG classification using 12-lead signals from the PTB-XL dataset to detect six cardiac conditions with a Multi-Output Random Forest model and statistical feature extraction.
# ECG-Based Cardiac Abnormality Detection Using Machine Learning

## Project Overview

This project focuses on detecting six cardiac conditions from 12-lead ECG signals using Machine Learning techniques. The PTB-XL dataset is used to train and evaluate a Multi-Output Random Forest classifier.

Statistical features are extracted from ECG recordings and used to identify the presence of different cardiac abnormalities.

## Dataset

- **Dataset:** PTB-XL
- **Number of ECG recordings:** 21,799
- **Sampling Frequency:** 500 Hz
- **Recording Duration:** 10 seconds
- **ECG Leads:** 12

## Conditions Detected

1. First-Degree AV Block (1dAVb)
2. Right Bundle Branch Block (RBBB)
3. Left Bundle Branch Block (LBBB)
4. Sinus Bradycardia (SB)
5. Atrial Fibrillation (AF)
6. Sinus Tachycardia (ST)

## Methodology

1. ECG data collection and preprocessing.
2. Extraction of 10 statistical features from each of the 12 ECG leads.
3. Formation of a 120-feature input vector for each ECG recording.
4. Training using a Multi-Output Random Forest classifier.
5. Individual classification threshold optimization using validation data.
6. Model evaluation using precision, recall, F1-score, specificity, ROC-AUC and bootstrap analysis.

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Repository Contents

- `ECG_Cardiac_Classification.ipynb` – Project implementation and model training.
- `results.csv` – Model evaluation results.
- `Project_Presentation.pdf` – Project presentation.
- `Evaluation/` – Confusion matrices and evaluation plots.

## Objective

The objective of this project is to explore the application of Machine Learning in automated cardiac abnormality detection using 12-lead ECG signals.

## Disclaimer

This project is developed for academic purposes only and is not intended for clinical diagnosis or medical decision-making.
