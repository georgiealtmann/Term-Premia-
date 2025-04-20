# Term Premia Modeling and Empirical Analysis

This repository presents research on modeling and analyzing **term premia** in financial markets. Term premia represent the excess return investors demand for holding long-term bonds instead of rolling over short-term debt, reflecting compensation for various risks such as interest rate uncertainty and macroeconomic shocks.

The project is structured around two key components:
- `TP_ACM.ipynb`: Development and implementation of a term premia model, based on methodologies commonly used in affine term structure modeling (ATSM) and related econometric approaches.
- `empirical findings.ipynb`: Empirical analysis based on the estimated models, including validation, visualization, and interpretation of the term structure dynamics.

## Project Overview

Understanding term premia is crucial for evaluating monetary policy effectiveness, asset pricing, and risk management.  
This project aims to:
- Model the behavior of the term structure of interest rates.
- Decompose bond yields into expectations and term premium components.
- Provide empirical insights into the dynamics of term premia over time.

The modeling draws inspiration from established frameworks such as the Adrian, Crump, and Moench (2013) approach ("Pricing the Term Structure with Linear Regressions") and related dynamic factor models.

## Repository Structure

| File | Description |
|:-----|:------------|
| `TP_ACM.ipynb` | Construction of the term premia model, including data preparation, factor extraction, model estimation, and preliminary analysis. |
| `empirical findings.ipynb` | Empirical exploration of the term premia estimates, including time-series visualization, robustness checks, and interpretation of macro-financial implications. |

## Requirements

Developed using:
- Python 3.12+
- Jupyter Notebook
- Core libraries:
  - numpy
  - pandas
  - matplotlib
  - scikit-learn
  - statsmodels

Install the necessary packages with:

```bash
pip install -r requirements.txt
