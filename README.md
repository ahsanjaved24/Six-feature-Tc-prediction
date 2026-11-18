
# Superconducting Critical Temperature Prediction

This repository contains the computational workflow for machine learning-based prediction of superconducting critical temperature (Tc) using composition-derived statistical and physics-guided descriptors.

## Repository Structure

```text
Superconducting-Tc-Prediction/
│
├── Data/
│   ├── Material_Tc_13494.xlsx
│   ├── Composition_Tc_13494.xlsx
│   ├── Features_37_13494.xlsx
│   ├── Features_29_13494.xlsx
│   ├── Pearson_correlation_matrix.xlsx
│   └── blind_holdout_10.xlsx
│
├── Code/
│   ├── Features_Pearson_Consensus.ipynb
│   └── ModelDevelopment_BlindPrediction.ipynb
│
└── README.md
```

## Dataset Description

- **Material_Tc_13494.xlsx:** Original dataset containing chemical formulas and experimental Tc values.
- **Composition_Tc_13494.xlsx:** Elemental stoichiometric representation of the chemical formulas.
- **Features_37_13494.xlsx:** Complete dataset containing 37 statistical and physics-based descriptors.
- **Features_29_13494.xlsx:** Refined dataset containing 29 features after Pearson correlation filtering.
- **Pearson_correlation_matrix.xlsx:** Pearson correlation matrix of the engineered features.
- **blind_holdout_10.xlsx:** Independent set of 10 materials reserved for blind prediction.

## Code Description

- **Features_Pearson_Consensus.ipynb:** Feature engineering, Pearson correlation analysis, and consensus feature selection.
- **ModelDevelopment_BlindPrediction.ipynb:** Comparative machine learning models, Gaussian Process Regression, and blind prediction of superconducting critical temperatures.
