# Big Data Event Analysis & SQL Automation Pipeline

## 📌 Project Overview
While my primary research focus is in high-energy astrophysics, this project was developed to demonstrate proficiency in **Big Data engineering, relational database management (SQL), and automated data visualization pipelines**. 

Using a massive dataset of e-commerce user interactions (2M+ events), this project builds an end-to-end analytical pipeline to process, filter, and extract statistical distributions. The methodologies applied here (sequential funnel filtering, anomaly detection, Pareto distributions, and temporal binning) are mathematically and structurally equivalent to processing large-scale astronomical event catalogs or satellite sensor telemetry.

## 📂 Repository Structure
* `sql_queries/`: Advanced SQL scripts utilizing Window Functions and CTEs for data deduplication, funnel analysis, and Pareto distributions.
* `notebooks/`: Python ingestion scripts designed to load out-of-core datasets into SQL Server using memory-efficient chunking strategies.
* `bots/`: Python automation scripts (Interactive EDA bots) that directly query the SQL database, generate publication-quality visualizations, and dynamically handle backend rendering.
* `presentation/`: Contains visual outputs, charts, and project presentation slides.

## 🛠️ Tech Stack & Methodologies
* **Database Management:** SQL Server, T-SQL.
* **Data Pipeline:** `Python`, `pandas`, `sqlalchemy` (bridging SQL databases with Python environments via `fast_executemany`).
* **Visualization & Automation:** `matplotlib`, `seaborn` (Automated generation of inset graphics and range overlay plots).
* **Big Data Concepts:** Memory-safe batch ingestion, deduplication partitions, long-tail (80/20) statistical modeling.

## 🔍 The Scientific Connection
The ability to query millions of rows, handle missing data, and automate the visualization of time-series events is domain-agnostic. Whether tracking user conversion rates or filtering background noise from Gamma-Ray Burst triggers, the core data science architecture remains identical.

---
*Developed by Ceren C. to showcase cross-domain data engineering capabilities.*
