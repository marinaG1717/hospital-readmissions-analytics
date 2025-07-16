# hospital-readmissions-analytics
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
