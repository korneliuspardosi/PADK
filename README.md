# PADK
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

## Main References
* Ablaza, C. M. J., Alladi, V., & Pape, U. J. (2023). *Indonesia’s informal economy: Measurement, evidence, and a research agenda*. World Bank.
* Hapsari, I. M., Yu, S., Pape, U. J., & Mansour, W. (2023). *Informality in Indonesia: Levels, trends, and features*. World Bank.
* Rothenberg, A. D., et al. (2016). Rethinking Indonesia's informal sector. *World Development*, 80, 96-113.
