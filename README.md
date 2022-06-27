# ESG Open-source Data Project

## Description

With an increasing demand on investors to drive sustainable investment, many asset management firms are driven to integrate ESG metrics as part of their investment decision making process. Like many others, Eastspring relies on various ESG data providers (such as MSCI, Refinitiv etc.)  to suffice our ESG data needs.

Since ESG data providers has its own set of methodology / linkage, the data issues arises when business units consolidate multiple ESG data sources together with in-house data sources for their ESG needs. As a result, enormous amount of time spent to perform data cleansing before generating their own customized metrics based on project scope.

Lastly, ESG metrics (such as ratings / scoring etc.)  are influenced by numerous factors (which is dependent on the portfolio and securities industries). Hence, it’s often challenging for the team to track and monitor the changes based on these factors.


Key Objective: 
-	Automated Data Cleansing workflow to increase accuracy of ESG data quality and allow end-users to perform timely analysis 
-	Monitoring on ESG data quality health status for early intervention  
-	Repository for ESG taxonomy to provide ease of data comparison across enterprise 
-	Diagnostic Dashboard to understand the movement of ESG metrics from its contributing factor (at portfolio / security level)


## Useful Information 
- Key Issues in ESG that are relevant to each Industry / Sector
a. https://www.msci.com/our-solutions/esg-investing/esg-ratings/materiality-map

- ESG Ratings by Market Data Providers
a. https://www.msci.com/our-solutions/esg-investing/esg-ratings
b. https://www.refinitiv.com/content/dam/marketing/en_us/documents/methodology/refinitiv-esg-scores-methodology.pdf

## Datasets

1. Yahoo Finance API - ESG Risk (Powered by Sustainalytics), Statistics & News 
2. World Bank ESG Data - https://databank.worldbank.org/source/environment-social-and-governance-(esg)-data#
3. ESG Book - https://app.esgbook.com/dashboard
4. MSCI Free Report - https://www.msci.com/research-and-insights/esg-ratings-corporate-search-tool
5. Newsapi - Endpoint url : 'https://newsapi.org/v2/everything?'
6. ClimateBERT - https://climatebert.ai/language-model


## Format of Folder Structure

This is the recommended folder structure adopted from [Cookiecutter data science](https://github.com/drivendata/cookiecutter-data-science). Not all folders are relevant and present in this project, feel free to pick and choose.

```
├── LICENSE
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├── src                <- Source code for use in this project.
│   ├── __init__.py    <- Makes src a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io
```

## License

MIT
