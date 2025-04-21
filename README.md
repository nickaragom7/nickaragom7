🚀 Data Engineering Roadmap by Nicolás Gómez Aragón

👨‍💻 About Me

I'm Nicolás Gómez Aragón — a Backend Developer, mathematician in training, and future Data Engineer. Currently working in technical support, I’m transitioning into the world of Data Engineering to improve my quality of life, gain financial independence, and eventually build a tech startup. I ride a Himalayan 411 named Ryan, and I dream of exploring the world on motorcycles while solving big data problems from anywhere with my dog Anubis.

🎯 Purpose

This repository is the center of my transformation into a professional Data Engineer. It holds the roadmap I’m following to build end-to-end ETL projects, with increasing complexity. Each project is designed to teach me skills that align with real-world data roles, especially in the financial sector.

All projects are implemented locally first, and cloud services like AWS will be introduced in the next stage of my learning.


---

🛣️ My 10-Project Roadmap

Each project contains:

Objective

Project Description

To-Do List (clear step-by-step tasks)


1. ETL: API to CSV

Objective: Learn to extract data from a public API and save it in a CSV. Description: A lightweight ETL where you call an API, clean the data, and save it to disk. To-Do:

Choose a public API (e.g., COVID, weather, currencies)

Use requests to extract data

Clean with pandas

Save data to a local CSV



---

2. ETL: CSV to SQLite

Objective: Learn how to move data from a flat file into a database. Description: Import a CSV into a local SQLite DB and run basic queries. To-Do:

Load CSV with pandas

Create SQLite DB and table schema

Insert data using sqlite3

Query and validate data



---

3. ETL: MySQL to Visualizations

Objective: Extract structured data and visualize insights. Description: Connect to MySQL, extract data, and visualize it using matplotlib or seaborn. To-Do:

Connect to a local MySQL DB

Query relevant tables

Load into pandas

Visualize patterns and trends



---

4. ETL: Multiple Sources to MongoDB

Objective: Integrate data from CSV, SQL, NoSQL and APIs into MongoDB. Description: Combine and transform data from different origins into a NoSQL format. To-Do:

Extract from CSV

Extract from SQL (SQLite or MySQL)

Call API

Standardize and normalize data

Insert into MongoDB



---

5. Airflow Orchestration - Weather Data Pipeline

Objective: Learn orchestration with Apache Airflow. Description: Automate a data pipeline that collects weather data daily. To-Do:

Install and set up Airflow locally

Create DAGs for extract, transform, load steps

Schedule the pipeline

Monitor and handle retries



---

6. Real-Time ETL with Kafka + Spark + MongoDB

Objective: Learn to handle real-time streaming data. Description: Stream financial or weather data using Kafka, process with Spark, store in Mongo. To-Do:

Set up Kafka producer (simulated data)

Stream to Spark Structured Streaming

Transform and write to MongoDB



---

7. AWS Glue + Redshift (For future stage)

Objective: Migrate to cloud-based ETL. Description: Serverless ETL with AWS Glue and analytics-ready Redshift warehouse. To-Do:

Prepare test dataset

Use Glue for ETL

Create Redshift schema

Load and query



---

8. Data Validation & Logging System

Objective: Implement proper validation and logging mechanisms. Description: Learn how to build resilient ETL pipelines by integrating pydantic, custom loggers, and error handling. To-Do:

Define validation schemas

Integrate with existing pipelines

Add structured logging

Create error tracking/reporting



---

9. Data Quality Audits + Reporting System

Objective: Ensure reliability and transparency of pipelines. Description: Build a dashboard or reporting system to detect anomalies and missing data. To-Do:

Profile your datasets

Set data quality rules (nulls, ranges, outliers)

Generate reports (could be email or dashboards)



---

10. Final Project: Financial Analytics Platform

Objective: Integrate all tools, patterns, and concepts learned. Description: A full ETL and analytics platform:

Extract data from financial APIs, CSVs, and DBs

Load into a local data warehouse (PostgreSQL)

Run analytics

Visualize dashboards (Streamlit or Dash) To-Do:

Reuse previous pipelines

Create unified schema

Document everything

Deploy locally (or with Docker)



---

🧠 My Learning Principles

Build small, iterate fast

Learn by doing

Share progress weekly on LinkedIn

Connect each project to market needs in Colombia and Latin America


📌 Let’s Connect

GitHub: nicolasgomezaragon

LinkedIn: @nigomeza



---

> This roadmap is a lifelong project. It will grow with me.




---

