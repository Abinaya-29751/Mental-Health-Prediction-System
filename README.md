# Mental-Health-Prediction-System
This project implements differential privacy techniques to predict mental health treatment-seeking behavior among technology professionals while preserving individual privacy. Using the OSMI (Open Sourcing Mental Illness) Mental Health in Tech Survey dataset, we compare traditional machine learning approaches with privacy-preserving alternatives.

# Features
Privacy-Preserving ML: Implementation of three differential privacy mechanisms
Comparative Analysis: Baseline vs. privacy-preserving model performance
Interactive Prediction: User-friendly interface for mental health risk assessment
Comprehensive Evaluation: Privacy-utility trade-off analysis

# Dataset
Source: [Mental Health in Tech Survey (OSMI)](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)
Description: 2014 survey measuring attitudes towards mental health and frequency of mental health disorders in tech workplaces.
Features:
1. Demographics (age, gender)
2. Work environment (company size, remote work, benefits)
3. Mental health factors (family history, treatment history)
4. Workplace support (anonymity, leave policies, consequences)

Target Variable: Binary classification - whether individual sought mental health treatment

# Tools and Techniques used: 
Python, Scikit-learn, Differential Privacy, Machine Learning, Data Preprocessing, Statistical Analysis.

# Getting Started
1. Prerequisites
   pip install -r requirements.txt

2. Installation
  Clone the repository
    git clone https://github.com/yourusername/mental-health-privacy-prediction.git
    cd mental-health-privacy-prediction

3.Install dependencies
  pip install pandas numpy scikit-learn matplotlib seaborn ipywidgets

4. Download the dataset
    Download from Kaggle
    Place survey.csv in the data/ directory
