This repository contains the workflow for machine learning-based prediction of superconducting critical temperature (Tc) using composition-derived statistical and physics-guided consensus features.
│
├── Data/
│   ├── Material_Tc_13494.xlsx (Chemical formula and Tc)
│   ├── Composition_Tc_13494.xlsx (Elemental stoichiometric representation for feature generation)
│   ├── Features_37_13494.xlsx (Complete dataset containing 37 statistical and physics-based descriptors)
│   ├── Features_29_13494.xlsx (Dataset after Pearson correlation filtering)
│   ├── Pearson_correlation_matrix.xlsx
│   └── blind_holdout_10.xlsx (Independent set of 10 materials reserved for blind prediction)
│
├── Code/
│   ├── Features_Pearson_Consensus (Features, Pearson correlation and consensus feature selection)
│   └── ModelDevelopment_BlindPrediction.ipynb (Comparative machine learning models and blind prediction)
│
└── README.md
