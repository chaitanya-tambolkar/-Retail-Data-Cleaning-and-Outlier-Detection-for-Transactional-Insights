# Retail Data Cleaning and Outlier Detection for Transactional Insights

This project, developed as part of **FIT5196 – Data Science for Text Analytics (Assessment 2)** at Monash University, focuses on **data cleansing, outlier detection, and predictive validation** using Python.  
It demonstrates a full end-to-end pipeline to detect anomalies, impute missing data, and model delivery-charge relationships for transactional retail datasets.

---

## Project Overview

The dataset represents **10,000 + online retail transactions** from a fictional Melbourne-based electronics store (DigiCO).  
Due to data corruption and incomplete records, several files contained **dirty data, missing values, and outliers**.  
This project addresses those issues through systematic **data wrangling, validation, and geospatial optimisation**.

The project also explores **data transformation and normalisation** for preparing suburb-level property data for linear modelling (Task 2).

---

##  Key Achievements

###  1. Data Cleaning and Validation  
- Resolved **100 % of data inconsistencies** in the retail dataset.  
- Handled anomalies through type correction, logical validation, and duplicate removal.  
- Ensured structural integrity across all attributes before transformation.

###  2. Geolocation Optimisation  
- Implemented the **Haversine Formula** to compute accurate distances between customers and their nearest warehouses.  
- Enhanced logistics insights and delivery-charge validation through spatial analytics.

###  3. Predictive Modelling & EDA  
- Built a **Linear Regression model** achieving **99.5 % R² accuracy** in validating delivery charges.  
- Conducted comprehensive **Exploratory Data Analysis (EDA)** to uncover transactional trends and seasonality effects.  
- Supported business decisions through interpretable model outputs and visualisations.

###  4. Data Reshaping and Transformation (Task 2)  
- Explored **standardisation, min-max scaling, log, power, and Box-Cox transformations** on property market data.  
- Evaluated feature linearity and scaling suitability for regression modelling of `median_house_price`.  
- Produced a structured comparative analysis to recommend the best transformation approach.

###  5. Reflection and Documentation  
- Compiled a professional report detailing methodology, justifications, and improvements for future iterations.  
- Followed Monash’s Assessment 2 marking rubric and reproducibility standards.

---

##  Skills & Tools

| Category | Tools & Libraries |
|-----------|------------------|
| **Languages** | Python 3.10 + |
| **Data Analysis** | pandas · numpy · matplotlib · seaborn |
| **Data Cleaning** | re · datetime · json · scikit-learn (preprocessing, imputation) |
| **Machine Learning** | scikit-learn (linear_model) · numpy.linalg |
| **Sentiment Analysis** | nltk.sentiment.vader (SentimentIntensityAnalyzer) |
| **Environment** | Google Colab / Jupyter Notebook |
| **Documentation** | Markdown · PDF reports · GitHub version control |

---


## 🧩 Workflow of the Project

Below is a visual representation of the project pipeline — starting from raw retail data through cleaning, modelling, transformation, and reporting.

            ┌────────────────────────────┐
            │     Raw Retail Datasets     │
            │ (dirty, missing, outlier)   │
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │   Task 1: Data Cleaning     │
            │ - Fix anomalies & typos     │
            │ - Validate field consistency│
            │ - Handle duplicates         │
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │ Task 1: Missing Data        │
            │ - Impute missing values     │
            │ - Restore logical accuracy  │
            │ - Validate numeric integrity│
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │ Task 1: Outlier Detection   │
            │ - Identify anomalies in     │
            │   delivery_charges          │
            │ - Remove/adjust outliers    │
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │ Predictive Validation Model │
            │ - Linear Regression (R²=0.995) │
            │ - Validate delivery logic   │
            │ - Evaluate seasonal trends  │
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │ Task 2: Data Reshaping      │
            │ - Normalisation & Scaling   │
            │ - Box-Cox / Log transforms  │
            │ - Feature correlation check │
            └──────────────┬─────────────┘
                           │
                           ▼
            ┌────────────────────────────┐
            │ Task 3: Documentation &     │
            │ Reflective Report           │
            │ - Methodology summary       │
            │ - Insights & future scope   │
            └────────────────────────────┘



