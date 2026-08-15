![](images/cover_image.png)

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
seaborn>=0.13
```

# Repository structure
```text
├── code.ipynb
├── data
│   ├── cross_elasticities.csv
│   ├── own_elasticities.csv
│   ├── product_elasticities_df.csv
│   ├── product_elasticities_long_df.csv
│   └── synthetic_dataset.csv
├── data_generation.ipynb
├── images
│   ├── EDA
│   │   ├── elasticity_crosselasticity.png
│   │   └── price_vs_quantity.png
│   └── model
├── README.md
└── requirements.txt
```