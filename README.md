# Time Series Module

A Python-based time-series forecasting workflow covering **Statistical Forecasting** and **Machine Learning Forecasting** techniques.

This repository provides an end-to-end workflow for analyzing time-series data, engineering features, selecting predictors, building forecasting models, and evaluating model performance.

The project uses the **Daily Sales French Bakery dataset** as an example.

## Project Overview

The workflow explores several approaches to time-series forecasting, including:

- **Data Preparation** – Data cleaning, preprocessing, and chronological train-test splitting.
- **Exploratory Data Analysis** – Understanding time-series patterns, trends, seasonality, and data characteristics.
- **Feature Engineering** – Creating calendar-based, lag, and rolling-window features.
- **Statistical Forecasting** – Applying traditional statistical forecasting methods.
- **Machine Learning Forecasting** – Building ML models using engineered time-series features.
- **Feature Selection** – Applying WoE transformation, LightGBM feature selection, Gini Stepwise, and Gini-MC.
- **Model Evaluation** – Comparing forecasting performance using appropriate evaluation metrics.

## Repository Structure

```text
Time-Series-Module/
│
├── Time-Series-Modelling-Workflow.ipynb
├── daily_sales_french_bakery.csv
└── README.md
```

*The repository structure may evolve as additional forecasting methods and experiments are introduced.*

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries used throughout the notebook.

## Getting Started

### 1. Install Python

Download and install Python from the official website:

https://www.python.org/downloads/

### 2. Download the Dataset

Download the `daily_sales_french_bakery.csv` dataset used in this project.

Ensure the dataset is placed in the appropriate directory so that it can be accessed by the notebook.

### 3. Clone the Repository

Clone the repository using Git:

```bash
git clone https://github.com/JoshuaVincentius/Time-Series-Module.git
```

Alternatively, download the repository as a ZIP file directly from GitHub.

### 4. Install Dependencies

Install the Python libraries required by the notebook.

For example:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
```

Additional libraries may be required depending on the forecasting methods and feature-selection techniques being used.

### 5. Run the Notebook

Navigate to the repository directory and launch Jupyter Notebook:

```bash
cd Time-Series-Module
jupyter notebook
```

Open the notebook file and execute the cells sequentially.

## Methodologies

The project covers two main forecasting approaches:

### 1. Statistical Forecasting

Explores traditional time-series forecasting methods, including statistical models for capturing trends, seasonality, and temporal dependencies.

### 2. Machine Learning Forecasting

Uses supervised machine learning techniques with time-series feature engineering.

The workflow also incorporates feature-selection and transformation techniques:

| Technique | Purpose |
|---|---|
| WoE Transformation | Transform predictors into Weight of Evidence representations |
| LightGBM Feature Selection | Identify relevant predictors using LightGBM |
| Gini Stepwise | Perform stepwise feature selection based on Gini improvement |
| Gini-MC | Evaluate feature contributions using Gini-based multicollinearity analysis |

## Dataset

The example dataset used in this project is the **Daily Sales French Bakery dataset**, which contains daily sales observations for different bakery products.

It can be used to explore:
- Daily sales patterns
- Weekly seasonality
- Trend and seasonal behavior
- Lagged sales relationships
- Forecasting performance across different models

## Author

**Joshua Vincentius**

GitHub: [JoshuaVincentius](https://github.com/JoshuaVincentius)

---

*This repository is intended for educational purposes and experimentation with statistical and machine learning approaches to time-series forecasting.*
