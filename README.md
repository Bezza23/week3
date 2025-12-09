# End-to-End Insurance Risk Analytics & Predictive Modeling
## Project Summary

This repository contains the analysis and predictive modeling pipeline for AlphaCare Insurance Solutions (ACIS), focusing on car insurance planning and marketing in South Africa.

The primary objective is to leverage historical claims data (Feb 2014 – Aug 2015) to identify low-risk customer segments for strategic premium optimization and targeted marketing, thereby attracting new clients and improving portfolio profitability.

Key Deliverables
Risk Segmentation: Identification of low-risk provinces, zip codes, and demographic groups.

Hypothesis Testing: Statistical validation of risk differences across key geographical and demographic features.

Predictive Model: A Machine Learning model to predict optimal premium values based on customer, location, and vehicle characteristics.

Final Report: Comprehensive analysis and actionable recommendations for product and marketing strategy.

## 🚀 Repository Structure
The project is structured into logical modules reflecting the end-to-end data science lifecycle.

```bash
alpha-care-risk-analytics/
├── data/
│   └── historical_claims_data.txt    # Input data (ignored by Git)
├── notebooks/
│   ├── 01_eda_and_stats.ipynb        # Task 1: Exploratory Data Analysis & Feature Engineering
│   ├── 02_hypothesis_testing.ipynb   # Task 2: A/B Hypothesis Testing
│   └── 03_predictive_modeling.ipynb  # Task 3: Regression/ML Model Development
├── src/
│   ├── __init__.py                   # For modular Python code/functions
│   └── processing_functions.py       # Example: Data cleaning and feature creation utilities
├── README.md
├── requirements.txt
└── .gitignore
```

## Setup and Execution
### 1. Environment Setup
Clone the repository:
```bash
git clone <YOUR_REPO_URL>
cd alpha-care-risk-analytics
```
### 2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# OR .\venv\Scripts\Activate.ps1 for Windows PowerShell
```
### 3. Install dependencies:
```bash
pip install -r requirements.txt
```

### 4. Data Acquisition: 
Download the provided historical data and place the .txt file into the data/ directory.
