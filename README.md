🌦️ Weather Data Pipeline using Airflow, Docker, and AWS
This project demonstrates an end-to-end data pipeline that fetches real-time weather data using the OpenWeather API, processes it through Apache Airflow, and stores it in PostgreSQL and AWS S3 for further analysis.

🚀 Project Overview
The pipeline automates the following steps:

Fetch Weather Data — Airflow retrieves weather data from the OpenWeather API.
Store in PostgreSQL — Data is cleaned and stored in PostgreSQL.
Backup to S3 — Processed data is exported to AWS S3 for persistence.
🧱 Architecture
AWS EC2 — Host environment for the project.
Docker — Containerized setup for Airflow and PostgreSQL.
Apache Airflow — Orchestrates ETL workflow.
PostgreSQL — Database for structured weather data.
AWS S3 — Storage for processed datasets.
OpenWeather API — Source of real-time weather data.
⚙️ Tech Stack
Apache Airflow
Docker
AWS EC2
PostgreSQL
AWS S3
OpenWeather API
