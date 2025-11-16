# Quantum-Enhanced-Anomaly-Detection-for-Credit-Card-Fraud-Detection
This project implements a quantum-enhanced machine learning system for credit card fraud detection, combining quantum circuit simulation using Qiskit with classical ML models like Logistic Regression, SVM, and Random Forest to improve anomaly detection accuracy via quantum feature extraction.

## Overview
This project demonstrates a hybrid quantum-classical machine learning system for credit card fraud detection. It leverages quantum circuit simulations using Qiskit combined with classical models (Logistic Regression, SVM, Random Forest) to extract quantum features for enhanced anomaly detection accuracy.

## Features
- Quantum variational circuits with 6 qubits for feature encoding
- Ensemble classical classifiers trained on quantum-extracted features
- PCA-based dimensionality reduction and quantum angle encoding
- Balanced dataset sampling with 0.17% fraud ratio representation
- Comprehensive evaluation with accuracy, precision, recall, and F1-score

## Installation

### Clone the repository
git clone https://github.com/InfantShervin/Quantum-Fraud-Detection.git
cd quantum-fraud-detection

### Set up virtual environment and install dependencies  
python -m venv venv
source venv/bin/activate # On Windows: venv\Scripts\activate
pip install -r requirements.txt

## Dataset  
Utilizes Kaggle's Credit Card Fraud Detection dataset (284,807 transactions; 0.17% fraud rate).  
Features include PCA components, amount, and time.  
Preprocessing involves scaling and PCA-based quantum feature reduction.

## Usage  
Run the Jupyter notebook:  
jupyter notebook notebooks/QC-TEMPLATE-1.ipynb
