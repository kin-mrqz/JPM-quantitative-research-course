# Quantitative Finance Notebooks

This repository contains four Jupyter notebooks demonstrating applied techniques in **quantitative finance**, from commodity price modeling to credit risk analysis.

## Contents

### 1. Natural Gas Price Analysis

* Descriptive & exploratory analysis
* Frequency analysis
* Autocorrelation analysis

### 2. Financial Modeling

* Interpolation & extrapolation of natural gas prices from historical data
* Calendar-aware model with bilinear regression & signal smoothing
* Pricing model for storage/injection/withdrawal transactions
* Example transaction included (Total Cost ≈ 1643.54)

### 3. Credit Risk Scorecard

* Part 1: Stratified train-test split, outlier treatment, missing value imputation
* Part 2: Variable bin cutoffs
* Part 3: Weight of Evidence (WoE) transformation
* Part 4: Model training with a Generalized Linear Model

### 4. FICO Automatic Quantization

* Data-driven approach to creating **k bins** for FICO scores to optimize default prediction
* Iterative centroid adjustment until convergence
* Advanced dynamic programming method for minimizing MSE

## Libraries Used

* `numpy`
* `pandas`
* `matplotlib`
* `statsmodels`
* `datetime` / `timedelta`
* `csv`

## Getting Started

Clone this repository and open any notebook in Jupyter Lab or Jupyter Notebook:

```bash
git clone https://github.com/kin-mrqz/quantitative-research-notebooks
cd quantitative-research-notebooks
jupyter notebook
```