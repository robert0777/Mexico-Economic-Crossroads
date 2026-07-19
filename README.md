# Mexico's Economic Crossroads (2026-2027)

A quantitative analysis of Mexico's fiscal outlook using a KLR Signals-based Monte Carlo simulation with 100,000 iterations.

## Overview

This repository contains the complete Python implementation powering the analysis for the Medium article *"Mexico's Economic Crossroads: A Data-Driven Analysis of the 2026-2027 Fiscal Landscape"* by Dr. Robert Hernández Martínez.

## Key Features

- **Composite Crisis Probability Model (CCPM)**: KLR signals-based Monte Carlo simulation
- **8 Key Indicators**: GDP Growth, Core Inflation, Sovereign Rating, Banking Sector, Fiscal Deficit, Debt Service, USMCA Uncertainty, Institutional Quality
- **Real Estate Trajectory Simulation**: Predictive modeling of residential property value trends
- **Interactive Visualizations**: All charts from the article generated directly from the code

## Methodology

The model integrates three established academic frameworks:
1. Kaminsky-Lizondo-Reinhart (KLR) Signals Approach (1998)
2. Berg-Pattillo Probit/Logit Framework (1999)
3. World Bank Panel Logit Methodology (2021)

## Results

- **Point Estimate**: 74.1% crisis probability
- **80% Confidence Interval**: [54.91%, 85.65%]
- **P(Crisis > 50%)**: 94.56%
- **Peak Risk Period**: February 2027

## Requirements

- Python 3.7+
- Jupyter Notebook
- Required packages: numpy, pandas, matplotlib, seaborn, tqdm

## Run the Analysis

```bash
pip install -r requirements.txt
jupyter notebook "Mexico's_Economic_Crossroads_A_Data_Driven_Analysis_of_the_2026_2027_Fiscal_Landscape_Dr_Robert_Hernández_Martínez.ipynb"
