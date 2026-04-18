# Paper-PADK
Econometric analysis of the determinants of informality in Indonesia using the ISES 2023 dataset and Multinomial Logit regression.

# Determinants of Informality in Indonesia: An Empirical Analysis

## Project Overview
This repository contains the code, derived data, and econometric analysis manuscript investigating the factors that influence the decision of micro and small enterprise (MSE) owners in Indonesia to remain in the informal sector.

Utilizing the **2023 Indonesia Informal Sector Enterprise Survey (ISES)** dataset from the World Bank, this study categorizes the reasons for informality into three main constraints:
1. **Regulatory Burden** (e.g., taxes, complex licensing procedures)
2. **Information Gap** (e.g., lack of knowledge regarding registration benefits)
3. **Voluntary** (e.g., no perceived benefit to registering)

**Key Findings:** The analysis reveals that human capital, specifically education level, is a crucial determinant. Higher educational attainment significantly reduces the probability of entrepreneurs remaining informal voluntarily. However, it simultaneously triggers a sharp increase in the probability of perceiving regulatory burdens as the primary barrier. This highlights that for educated entrepreneurs, informality is driven by institutional exclusion rather than a deliberate exit strategy.

## Methodology
This project employs a discrete choice econometric approach:
* **Primary Model:** Multinomial Logit (MNL) Regression.
* **Interpretation:** Average Marginal Effects (AME) to quantify absolute probability changes.
* **Controls:** City Fixed Effects to account for unobserved heterogeneity in local bureaucratic efficiency and infrastructure.

## Repository Structure
* `notebooks/` : Jupyter Notebooks (`.ipynb`) containing data cleaning, exploratory data analysis (EDA), and regression modeling.
* `paper/` : The final manuscript and publication drafts (LaTeX/PDF format).
* `requirements.txt` : List of Python dependencies required to run the analysis (e.g., `pandas`, `statsmodels`, `matplotlib`, `seaborn`).

## How to Run
1. Clone this repository to your local computer.
2. Make sure you have Python 3.8 or later.
3. Install all dependencies by running the command: `pip install -r requirements.txt`
4. Open the files inside the `notebooks/` folder using Jupyter Notebook or VS Code.
