# Overview
use PyMC to estimate price elasticities with synthetic data

https://www.pymc.io/welcome.html

# Methods
* Log-log
* Bayesian therom
* Random number generator
* No pooling PyMC
* Partial pooling PyMC (Hierarchical price elasticity)
* Hierarchical price elasticity + cross-price elasticity
* Plots

# Notebook
code.ipynb

# Requirement

```
numpy>=1.24
pandas>=2.0
matplotlib>=3.7
arviz>=0.16
pymc>=5.10
jupyter>=1.0
```

# Repository structure
```text
├── code.ipynb
├── data
│   ├── catalog.csv
│   ├── cross_elasticities.csv
│   ├── own_elasticities.csv
│   └── synthetic_dataset.csv
├── data_generation.ipynb
├── images
│   ├── EDA
│   └── model
├── README.md
└── requirements.txt
```