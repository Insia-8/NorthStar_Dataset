***NorthStar Urban Mobility and Logistics — Databases and Analytics Coursework***

***Student:*** Insia Syed
***Student ID:*** 32146969
***Module:*** Databases and Analytics (CP60056E)
***Batch:*** 2

---

***Project Overview***

This repository contains the dataset and analytical notebooks for the NorthStar Urban Mobility and Logistics case study. The analysis investigates operational failures across delivery performance, customer complaints, vehicle maintenance, and app platform reliability using three technical environments.

---

***Notebooks***

__Section 1 — NorthStar_Section1_R.ipynb__
- Kernel: R
- Libraries: sqldf, dplyr, tidyr, ggplot2, lubridate, stringr, RCurl
- Contents: Data loading via RCurl, zone standardisation, date anomaly detection, SQL operations (SELECT/INSERT/UPDATE/DELETE), aggregate functions, six multi-table business queries, dplyr and tidyr manipulation, four visualisations, hypothesis testing

__Section 2 — NorthStar_Section2_Python.ipynb__
- Kernel: Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, scipy, sklearn
- Contents: Data loading, EDA, zone cleaning, missing value handling, feature engineering, NumPy statistics, Pandas analysis, Airport zone drill-down, correlation matrix, four visualisations, Random Forest classification model, confusion matrix, feature importance analysis

__Section 3 — NorthStar_Section3_MongoDB.ipynb__
- Kernel: Python 3
- Libraries: pymongo, dnspython, matplotlib, pandas
- Contents: MongoDB Atlas connection, NoSQL schema design, data insertion across five collections, CRUD operations, aggregation pipelines, indexing, explain() query performance analysis, three visualisations from live Atlas queries

---

***Key Findings***

- Central and Airport zones have the highest delivery failure rates at 20.2% and 40.4% respectively
- 30.8% of Airport zone deliveries use InRepair vehicles — the primary cause of zone underperformance
- Training score does not significantly predict delivery failure (r = 0.139, p = 0.095)
- Fuel cost exceeds order value in a subset of low-value orders — a minimum order value threshold of £15–£20 is recommended
- Random Forest model achieved 64% accuracy but could not identify failed deliveries from structured data alone — justifying the MongoDB redesign

---

That is all you need. Keep it factual and clear — the examiner just needs to know what is in the repo, how to open things, and what the work is about.
