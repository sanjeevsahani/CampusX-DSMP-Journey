# 🏠 Capstone Project — Real Estate Price Prediction

> Part of [CampusX DSMP Journey](../README.md) · Instructor: Nitish Singh

---

## 🎯 Project Overview

An end-to-end Real Estate Price Prediction application built using
the complete Data Science pipeline — from raw data to deployed web app.

| | |
|---|---|
| **Project** | Real Estate Price Prediction |
| **Domain** | Real Estate |
| **Tech Stack** | Python, Pandas, Scikit-learn, Streamlit, AWS |
| **Modules** | Price Prediction + Analytics + Recommender System + Insights |
| **Deployment** | AWS |

---

## 📋 Sessions Overview

| Session | Topics | Notebook |
|---------|--------|---------|
| Session 01 | Project Overview, Data Gathering, Details of Data | `s01_data_gathering.ipynb` |
| Session 02 | Merging House & Flats Data, Basic Level Data Cleaning | `s02_data_cleaning.ipynb` |
| Session 03 | Feature Engineering — additionalRoom, areaWithType, agePossession, furnishDetails, luxury Score | `s03_feature_engineering.ipynb` |
| Session 04 | EDA — Univariate Analysis, PandasProfiling, Multivariate Analysis | `s04_eda.ipynb` |
| Session 05 | Outlier Detection and Removal | `s05_outlier_detection.ipynb` |
| Session 06 | Missing Value Imputation | `s06_missing_value_imputation.ipynb` |
| Session 07 | Feature Selection — SHAP, RFE, LASSO, Random Forest, Gradient Boosting, Linear Regression | `s07_feature_selection.ipynb` |
| Session 08 | Model Selection — OHE, Target Encoding, Pipeline, Price Prediction Streamlit App | `s08_model_selection.ipynb` |
| Session 09 | Analytics Module — Geo map, Word cloud, Scatterplot, Pie chart, Boxplot, Distplot | `s09_analytics_module.ipynb` |
| Session 10 | Recommender System — TopFacilities, Price Details, LocationAdvantages | `s10_recommender_system.ipynb` |
| Session 11 | Recommender System Part 2 — Evaluation, Streamlit Web Interface | `s11_recommender_streamlit.ipynb` |
| Session 12 | Insights Module | `s12_insights_module.ipynb` |
| Session 13 | Deploying on AWS | `s13_aws_deployment.ipynb` |

---

## 📅 Daily Log

| Day | Session | Type | Progress |
|-----|---------|------|----------|
| — | — | — | Not started yet |

---

## 📁 Notebooks

| File | Session | Topic |
|------|---------|-------|
| — | — | Not started yet |

---

## 🏗️ Project Architecture
```
🏠 Capstone Project — Real Estate Price Prediction
│
├── 📂 data/
│   ├── 📂 raw/
│   │   ├── houses.csv                ← Raw house data
│   │   └── flats.csv                 ← Raw flats data
│   └── 📂 processed/
│       ├── merged_data.csv           ← Merged dataset
│       ├── cleaned_data.csv          ← After cleaning
│       └── final_data.csv            ← Ready for ML
│
├── 📂 notebooks/
│   ├── s01_data_gathering.ipynb      ← Session 01
│   ├── s02_data_cleaning.ipynb       ← Session 02
│   ├── s03_feature_engineering.ipynb ← Session 03
│   ├── s04_eda.ipynb                 ← Session 04
│   ├── s05_outlier_detection.ipynb   ← Session 05
│   ├── s06_missing_value.ipynb       ← Session 06
│   ├── s07_feature_selection.ipynb   ← Session 07
│   └── s08_model_selection.ipynb     ← Session 08
│
├── 📂 models/
│   └── pipeline.pkl                  ← Trained model pipeline
│
├── 📂 app/
│   ├── app.py                        ← Main Streamlit app
│   ├── price_predictor.py            ← Price prediction module
│   ├── analytics.py                  ← Analytics dashboard
│   ├── recommender.py                ← Recommender system
│   └── insights.py                   ← Insights module
│
├── requirements.txt                  ← Dependencies
├── Dockerfile                        ← For AWS deployment
└── README.md
```

---

## 🔄 Project Pipeline
```
Raw Data        →   Data Cleaning   →   Feature Engg   →   EDA & Outliers
(Houses+Flats)      (Merge+Clean)       (Luxury Score)      Detection
                                                                  │
                                                                  ↓
AWS Deployment  ←   Streamlit App   ←   Model          ←   Feature
                    │                   Selection           Selection
                    │
                    ├── 💰 Price Predictor
                    ├── 📊 Analytics Dashboard
                    ├── 🏘️  Recommender System
                    └── 💡 Insights Module
```
---

<p align="center"><i>Updated regularly as I progress through the sessions.</i></p>
