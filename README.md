# Bootstrap vs Classical Estimation: Statistical Inference Methods Comparison

A comprehensive Python-based analysis comparing traditional and bootstrap methods for confidence interval estimation, with applications to real-world health data and systematic simulation studies.

## 📊 Project Overview

This project implements and compares four confidence interval estimation methods for mean parameter inference:
- **Classical t-CI** (traditional parametric approach)
- **Percentile Bootstrap** (non-parametric resampling)
- **Studentized Bootstrap** (t-statistic based bootstrap)
- **BCa Bootstrap** (Bias-Corrected and Accelerated)

The analysis evaluates method performance across different sample sizes and probability distributions using both real-world data (diabetes health indicators) and Monte Carlo simulations.
## 📁 Repository Contents
Bootstrap-vs-Classical-Estimation/
│
├── notebooks/
├──Bootstrap_vs_Classical_Notebook-2.ipynb # Extended analysis
│
├── src/
│ ├── ci_implementations.py # Core CI method implementations
│ ├── simulation_engine.py # Monte Carlo simulation framework
│ ├── data_loader.py # Data loading and preprocessing
│ └── visualization.py # Plotting and result visualization
│
├── data/
│ ├── raw/ # Original datasets
│ │ └── diabetes_012_health_indicators_BRFSS2015.csv
│
│
├── results/
│ ├── figures/ # Generated plots and visualizations
│ │ ├── BMI_hist_full.png
│ │ ├── BMI_hist_small_n20.png
│ │ └── coverage_plots/
│ └── simulation_results/ # Simulation outputs
│ └
