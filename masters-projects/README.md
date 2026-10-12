# MSc Data Analytics — Master's Projects

**Eswar Surya Danaboina** · MSc Data Analytics, Dublin Business School · 2025–2026

This repository is an index of the projects I completed as part of my Master's studies and related MSc-level analytics work. To preserve the original project history, code, issues, and project-specific documentation, each project remains in its own canonical repository. This repository organises them by theme and links to those sources rather than duplicating their files.

## Project map

```text
masters-projects/
├── README.md
├── machine-learning/
│   ├── human-vitals-anomaly-detection-thesis
│   └── lstm-anomaly-detection-timeseries
├── business-intelligence/
│   ├── bike-sales-dashboard-tableau-project
│   └── customer-support-ticket-analytics-bi
└── python-sql-analytics/
    └── walmart-sales-analytics-python-sql
```

The tree above is a navigation map. The folders are represented by links to the existing repositories; their source files are not copied into this index repository.

## 1. Machine learning and anomaly detection

### Human Vitals Anomaly Detection Thesis

**Focus:** Unsupervised anomaly detection and explainable machine learning for human vital-sign records.

**Technologies:** Python, Pandas, NumPy, scikit-learn, Isolation Forest, SHAP, Jupyter Notebook.

**Project work documented in the source repository:**
- Cleaned and prepared multivariate vital-sign data.
- Built an Isolation Forest workflow for anomaly detection.
- Used SHAP to explain feature contributions to anomaly decisions.
- Documented methodology, assumptions, limitations, and public-safe outputs.

**Evidence noted in the project README:** 200,020 records in the full project dataset. The raw dataset is not published.

[Open the original thesis repository](https://github.com/eswarsurya/human-vitals-anomaly-detection-thesis)

### LSTM Anomaly Detection Timeseries

**Focus:** Time-series analysis and anomaly review candidates using LSTM modelling concepts and sequence-based analysis.

**Technologies:** Python, Pandas, NumPy, TensorFlow/Keras concepts, Jupyter Notebook.

**Project work documented in the source repository:**
- Prepared timestamped data and sequence windows.
- Reviewed rolling behaviour and deviations from recent baselines.
- Produced daily activity summaries and ranked candidates for analyst review.
- Documented results without claiming production alerting.

**Evidence noted in the project README:** 10,320 half-hourly records covering July 2014 to January 2015.

[Open the original LSTM repository](https://github.com/eswarsurya/lstm-anomaly-detection-timeseries)

## 2. Business intelligence and dashboards

### Bike Sales Dashboard — Tableau

**Focus:** Bike sales and resale analysis across brands, models, states, owners, and seller types.

**Technologies:** Tableau, CSV data preparation, visual analytics, dashboard design.

**Evidence noted in the project README:** 10,000 records, 8 brands, 40 models, and 10 Indian states; aggregate outputs and dashboard review notes are documented.

[Open the original Tableau repository](https://github.com/eswarsurya/bike-sales-dashboard-tableau-project)

### Customer Support Ticket Analytics BI

**Focus:** Ticket demand, support operations, first-response and resolution SLA performance, and data quality.

**Technologies:** Power BI, Tableau, Excel, data cleaning, KPI reporting, business analysis.

**Evidence noted in the project README:** public-safe evidence covers 2,330 support tickets; the README reports 86.65% first-response SLA attainment and 66.39% resolution SLA attainment.

[Open the original BI repository](https://github.com/eswarsurya/customer-support-ticket-analytics-bi)

## 3. Python and SQL analytics

### Walmart Sales Analytics — Python & SQL

**Focus:** Weekly retail sales, store-level trends, holiday behaviour, and relationships with external business factors.

**Technologies:** Python, Pandas, SQL, Jupyter Notebook, Excel, business reporting.

**Project work documented in the source repository:**
- Prepared and explored store-level weekly sales data.
- Wrote SQL analysis queries and produced Python summaries.
- Documented business interpretations and limitations, including that 2012 is a partial year in the available data.

[Open the original Walmart analytics repository](https://github.com/eswarsurya/walmart-sales-analytics-python-sql)

## Related engineering extension

The human-vitals thesis modelling approach was also extended into a service-oriented API. This is a related engineering project rather than an additional thesis folder.

[Human Vitals Anomaly Detection API](https://github.com/eswarsurya/human-vitals-anomaly-api)

## Review and reproducibility

Use each original repository's README as the source of truth for setup instructions, data context, available notebooks, outputs, and test commands. Report local test results, CI checks, and real deployments separately. Figures in this index are copied from the respective project READMEs and have not been independently recalculated here.

## Academic and public-sharing notes

- Original repositories and their histories are preserved.
- Check each repository's licence and data-sharing notes before reusing materials.
- Do not commit raw, private, or sensitive datasets; follow each project's documented public-sharing approach.
- This index is for academic and portfolio navigation. It does not claim that every project is production-deployed.
