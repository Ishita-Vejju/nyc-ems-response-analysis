# NYC EMS Response Time Analysis

Cleaning and analyzing NYC ambulance dispatch data with Python, SQL and Tableau.

**Status:** In progress
**Data:** [FDNY - EMS Incident Dispatch Data](https://data.cityofnewyork.us/Public-Safety/EMS-Incident-Dispatch-Data/76xm-jjuj), NYC Open Data, public domain.

## Why this project
(TODO: 2-3 sentences — response times, public safety, data quality challenge)

## Pipeline
1. **Explore** — measured missing values, duplicates, inconsistent text (`notebooks/01_exploration.ipynb`)
2. **Clean** — Pandas, decisions documented in `data_quality_log.md` (`notebooks/02_cleaning.ipynb`)
3. **Load** — cleaned data into PostgreSQL/Supabase (`sql/schema.sql`)
4. **Analyze** — 8-10 SQL queries incl. window functions (`sql/analysis_queries.sql`)
5. **Stats** — group comparisons and correlation (`notebooks/03_statistics.ipynb`)
6. **Dashboard** — Tableau Public: (TODO: link)

## Key findings
(TODO: 3-5 sentences, fill after analysis)

## How to run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploration.ipynb
```

## Data quality summary
(TODO: paste condensed version of data_quality_log.md here)
