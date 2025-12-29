## Welcome to my GitHub profile!

I’m **Simran Jadhav**, an M.S. Data Science student at the **University of Colorado Boulder** (GPA: **3.8/4**).  
I build data science and data engineering systems end-to-end — from ETL/ELT and data quality gates to model training, evaluation, and deployment.

---

## Education

- **University of Colorado Boulder** — M.S. in Data Science (Aug 2024 – May 2026) | GPA: **3.8/4**
- **Mumbai University, Rajiv Gandhi Institute of Technology** — B.E. in Computer Engineering (Jul 2020 – May 2024) | GPA: **3.7/4**

---

## Experience

### Nexus Weather & Climate — Data Science & Engineering Intern (May 2025 – Present) | Boulder, USA
- Built production **ETL/ELT** for NWP, station, wave, and precip feeds; produced partitioned **Parquet** datasets and automated daily refresh/backfills via **Airflow on Docker**.
- Implemented **data quality + inference gating** (schema, unit, range, shape checks, dedupe, backfills); replaced a legacy **SVM** with a tuned **Random Forest** and standardized evaluation (**MAE, MSE, CRPS**) with automated reports/plots.
- Designed a **CNN–LSTM** forecasting module with probabilistic calibration and CRPS-style / quantile-weighted objectives; automated training/eval via **YAML configs**; exported single-file artifacts and a **REST** service; shipped runtime health/drift dashboards.
- Set up **CI/CD** with GitHub Actions for nightly training/evaluation, artifact versioning, checksums, and failure alerts; improved p95 inference latency to **< 350 ms** via feature-pipeline streamlining and caching.

---

## Projects

- **Safer Ride — Risk-Aware Bike Routing (AWS: S3, Glue/Athena, Lambda, API Gateway)**  
  End-to-end pipeline ingesting crash/311/bike-infra data into S3, transforming into partitioned tables, and loading PostGIS layers on RDS with spatial indexes.  
  FastAPI on Lambda returns a **0–100 route risk score** using spatial joins; React + Leaflet renders overlays; EventBridge schedules refresh; QuickSight tracks trends.

- **AI-Powered Code Debugger (Python, Flask, GPT-4o, Docker, REST API)**  
  Flask app with a modular pipeline to debug/refactor/optimize Python code; packaged as a Dockerized REST service for reproducible integration.

- **PCOS Analysis & Detection (Python, Scikit-learn)**  
  ML pipeline for PCOS detection with preprocessing, predictive analytics, and automated validation for healthcare workflows.

- **Data Integration Solution — Denver International Airport (ServiceNow, Azure DevOps)**  
  Automated ETL integrating ServiceNow + Azure DevOps and built an interactive monitoring dashboard for operational visibility.

- **Yoga Posture Detection & Correction (Python, TensorFlow.js)**  
  Built an FNN achieving **96.5% accuracy**; deployed with TensorFlow.js for real-time, browser-based pose correction and feedback.

- **Amazon Prime Data Analysis (Tableau, SQL)**  
  Interactive Tableau dashboard over SQL data to analyze content performance, top-rated titles, and trending genres.

---

## Skills

- **Programming & Databases:** Python, R, SQL, C++, Java | MySQL, PostgreSQL, MongoDB  
- **ML & Big Data:** pandas, NumPy, scikit-learn, TensorFlow, PyTorch, XGBoost, LightGBM | Spark, Hadoop, Dask, xarray  
- **Cloud & MLOps:** AWS, Azure, GCP | Docker, Airflow, MLflow | Flask, FastAPI, REST APIs | GitHub Actions (CI/CD)  
- **Data Engineering:** ETL/ELT, time-series feature engineering, schema/QA validation, Parquet, orchestration  
- **Visualization:** Tableau, Power BI, Matplotlib, Seaborn

---

## Publication

- Technological paper: **Yoga Posture Detection and Correction**

---

## Links

- LinkedIn: https://www.linkedin.com/in/simran-jadhav20/
- GitHub: https://github.com/Simrann020
- Email: simranjadhavv022003@gmail.com
