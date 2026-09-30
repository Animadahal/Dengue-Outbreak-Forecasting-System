# Trustworthy AI for Dengue Forecasting

This project presents a Temporal Fusion Transformer (TFT) framework for dengue case forecasting using the **DengAI: Predicting Disease Spread** dataset.

## Key Features

* Dengue case forecasting for San Juan, Puerto Rico and Iquitos, Peru
* Temporal Fusion Transformer (TFT)
* 24-week historical window and 4-week forecasting horizon
* Comparison with Naive, Seasonal Naive, and LSTM baselines
* Probabilistic forecasting using 10th, 50th, and 90th quantiles
* Uncertainty estimation using PICP and PINAW
* Explainability through variable selection and temporal attention
* Rule-based risk stratification and decision support

## Main Results

| Metric |        TFT |
| ------ | ---------: |
| MAE    |  **6.560** |
| RMSE   | **10.724** |
| R²     |  **0.840** |
| sMAPE  | **63.40%** |
| PICP   | **93.12%** |
| PINAW  | **0.1623** |

## Workflow

The notebook covers the complete research workflow:

**Data Preprocessing → Feature Engineering → TFT Training → Baseline Comparison → Uncertainty Estimation → Explainability → Risk Stratification**

## Dataset

**DengAI: Predicting Disease Spread**
DrivenData: https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/

## Notebook

The repository includes the complete Jupyter Notebook containing the implementation, experiments, evaluation, and analysis.




