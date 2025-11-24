# Machine_Learning_DataOrbit
Machine Learning Project 2 (DataOrbit_HealthCare Provider Fraud Detection)
# Healthcare Provider Fraud Detection Project

## Team Members
- Ayten Aaser 
- Yasmin Farag
- Abdallah Emad
- Fatma Shaheen

## Project Overview
Machine learning project to detect fraudulent healthcare providers for Medicare as part of Machine Learning Course Project 2 with Data Orbit. Healthcare fraud costs the U.S. healthcare system over $68 billion annually, and this project aims to build an intelligent fraud detection system.

## Business Problem
Medicare needs to identify fraudulent healthcare providers who engage in activities such as:
- Billing for services never rendered
- Upcoding (billing for higher-cost procedures)
- Unbundling (billing separately for combined procedures)
- Submitting claims for deceased patients
  
## Dataset
**Download from:** https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis

### Files Required:
- `Train_Beneficiarydata.csv` - Patient demographics and chronic conditions
- `Train_Inpatientdata.csv` - Hospital admission claims
- `Train_Outpatientdata.csv` - Outpatient claim data
- `Train_labels.csv` - Provider fraud labels (Yes/No)
  
## Repository Structure
- `data/` - Dataset storage
- `notebooks/` - Jupyter notebooks for analysis
- `reports/` - Final deliverables

## Analysis Pipeline
1. `01_data_exploration_and_feature_engineering.ipynb` - Data exploration
2. `02_modeling.ipynb` - Model training
3. `03_evaluation.ipynb` - Evaluation & error analysis

   ## Setup Instructions
1. Clone this repository: `git clone https://github.com/aytenaaser/Machine_Learning_DataOrbit.git`
2. Download datasets from Kaggle link above
3. Place all CSV files in the `data/` folder
4. Run notebooks in numerical order: 01 → 02 → 03

   ## Repository Structure
Machine_Learning_DataOrbit/
├── data/ # Dataset storage
├── notebooks/ # Jupyter notebooks
│ ├── 01_data_exploration_and_feature_engineering.ipynb
│ ├── 02_modeling.ipynb
│ └── 03_evaluation.ipynb
├── reports/ # Final deliverables
│ ├── technical_report.pdf
│ └── presentation.pptx
└── README.md

## Analysis Pipeline
1. **Data Exploration & Feature Engineering** - Understand data, handle missing values, create provider-level features
2. **Modeling** - Address class imbalance, train multiple algorithms, hyperparameter tuning
3. **Evaluation** - Model comparison, error analysis, business impact assessment

## Installation & Dependencies
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
