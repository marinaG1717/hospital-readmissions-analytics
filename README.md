# hospital-readmissions-analytics
This project builds a modern data pipeline for analyzing 30-day hospital readmissions using synthetic EHR data (Synthea) and CMS benchmarks. Technologies used: Databricks, Delta Lake, and dbt for modeling.

## Features:
- Data ingestion from Synthea
- Readmission detection using DBT models
- Dashboard-ready summary tables

## Repo Structure:
- `dbt_project/` – SQL models for readmission logic
- `notebooks/` – ETL and EDA
- `docs/` – project documentation

## License: MIT

hospital-readmissions-analytics/
│
├── dbt_project/             # DBT models, configs, tests
│   ├── models/
│   │   ├── staging/
│   │   ├── marts/
│   │   └── readmissions/
│   ├── seeds/
│   ├── dbt_project.yml
│   └── profiles.yml         # optional; or keep it local
│
├── notebooks/               # Databricks notebooks for EDA & ETL
│   ├── load_synthea_data.py
│   ├── explore_readmissions.ipynb
│   └── transform_to_delta.py
│
├── docs/                    # Markdown docs
│   ├── project_overview.md
│   └── data_dictionary.md
│
├── dashboards/              # Optional: dashboard JSON or screenshots
│
└── README.md
