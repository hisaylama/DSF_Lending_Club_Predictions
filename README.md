# Final Project on Data Science in Finance 

![dsif_header_1](https://github.com/user-attachments/assets/65aba106-7de7-4db7-a5b6-08148018392c)
---
This repository contains the development of predictive models for the Lending Club platform. The primary aim is to determine whether loan applications should be approved or rejected based on various financial indicators. 

- Dataset source - [Lending club dataset](https://www.kaggle.com/code/faressayah/lending-club-loan-defaulters-prediction#%E2%9C%94%EF%B8%8F-Artificial-Neural-Networks-(ANNs))
- Follow the technical report to use this repository - [Technical report](https://github.com/hisaylama/DSF_Lending_Club_Predictions/blob/main/Technical_Report.ipynb)

**Note:** Headings with blue fonts in the Technical report are clickable, it links to a notebook which has additional information.
  
## Repository Contents

- `Data_cleaning.ipynb`: Jupyter notebook for initial data cleaning processes.
- `Exploratory_data_analysis.ipynb`: Detailed exploratory data analysis of the lending dataset.
- `Predictive_model.ipynb`: Construction and validation of the predictive model.
- `Model_deployment.ipynb`: Notebook demonstrating the deployment of the predictive model.
- `Technical_Report.ipynb`: Comprehensive report detailing the methodologies, analyses, results, and conclusions of the predictive modeling process.
- `baseline_model_2.pkl`: Model used for initial predictions.
- `ds6utility.py`: `Python` function file is used while running `Predictive_model.ipynb` .

## Project Objective

The goal of this project is to enhance decision-making for loan approvals using data-driven insights. By applying machine learning models, we aim to:
- Deploy a real-time scoring model that can provide instant financial decisions - "Approve or reject loan application"
- Implications
    - Minimize the risk of default.
    - Reduce operational costs by automating the decision-making process.

## Real-time Scoring Application
The project explores the potential for a real-time scoring application that rates loan applicants as either 0 or 1. This score is determined by predictive models such as `Random Forest` and `XGBoost`, which classify applicants based on the likelihood of fulfilling loan repayment.

## Getting Started

To get started with this project:
1. Clone the repository to your local machine or download all the files.
2. Follow the [`Technical_Report.ipynb`]((https://github.com/hisaylama/DSF_Lending_Club_Predictions/blob/main/Technical_Report.ipynb)
)

## Usage

Each notebook is self-contained and includes comments explaining the purpose of each section of code. Follow the notebooks in the order they are listed to replicate the analysis and model development.

## Acknowledgments

- Thanks to all Elvtr and teams who have invested their efforts in develop this project

**Note**: This code will soon be integrated with a front-end API for an improved user interface. 
Stay tuned for updates.


   
