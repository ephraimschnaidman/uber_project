# uber_project
should a driver drive tonight
driver-analytics/
├── data/
│   ├── raw/           # Put Uber + Lyft CSV exports here
│   └── processed/     # DuckDB will live here
├── models/
│   ├── staging/       # stg_uber_trips.sql, stg_lyft_trips.sql  
│   └── marts/         # fct_trips.sql, dim_zones.sql
├── scripts/
│   └── load_csv.py    # Load CSVs into DuckDB
├── dashboard.py       # Streamlit app
├── dbt_project.yml
└── README.md