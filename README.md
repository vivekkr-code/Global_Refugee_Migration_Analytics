# Global Refugee Migration Analytics

An end-to-end data analytics and machine learning project focused on understanding displacement corridors, analyzing humanitarian assistance patterns, and forecasting migration trends using historical data.

---

## 📌 Project Overview

Forced displacement is one of the most critical global humanitarian challenges. This project analyzes cross-border movements, socio-economic drivers, and financial flows to uncover key migration patterns. The goal is to provide data-driven insights that assist policymakers and humanitarian organizations in proactive resource planning and emergency response.

### Key Objectives
* **Exploratory Data Analysis (EDA):** Identify primary migration corridors, origin-to-asylum patterns, and yearly displacement trends.
* **Correlation & Outlier Analysis:** Evaluate relationships between financial aid/socioeconomic indicators and refugee volumes, accounting for significant crisis events.
* **Predictive Modeling:** Train and compare regression and time-series models to predict displacement numbers and annual funding needs.

---

## 📂 Repository Structure

```text
├── data/
│   ├── raw/                  # Original downloaded datasets (UNHCR / ODA)
│   └── processed/            # Cleaned data (df_clean.csv)
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_and_visualization.ipynb
│   └── 03_modeling_and_evaluation.ipynb
├── src/
│   ├── preprocessing.py      # Cleaning and outlier handling scripts
│   └── model.py              # ML model training and evaluation
├── visualisations/           # Heatmaps, boxplots, and trend charts
├── requirements.txt          # Python dependencies
└── README.md
