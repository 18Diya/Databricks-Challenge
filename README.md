<img width="1580" height="300" alt="banner" src="https://github.com/user-attachments/assets/54b3b592-3e41-4af9-a404-e4bf57faf2eb" />


<div align="center">

# Databricks 14-Days of AI Challenge

</div>

Excited to be joining the Databricks 14 Days AI Challenge by Indian Data Club!
I’m looking forward to strengthening my fundamentals in Databricks, Apache Spark, and real‑world data engineering workflows through hands‑on learning. Excited to learn, build, and grow alongside the community over the next 14 days.

Grateful for the support and initiative by [Databricks,](https://databricks.com/) [Codebasics](https://codebasics.io/) and [Indian Data Club.](https://www.linkedin.com/company/indian-data-club/)


# Day 0 | Setup & Data Loading – Databricks 14 Days AI Challenge

Focused on setting up the environment and preparing data before starting Day 1.

What I completed: → Created Databricks Community Edition account and cluster → Configured Kaggle API credentials → Created schema and volume for data storage → Downloaded and extracted e‑commerce dataset from Kaggle → Loaded October & November 2019 data into Spark

Setup done. Data ready.

# PHASE 1: FOUNDATION (Days 1-4)

# DAY 1 (09/01/26)– Platform Setup & First Steps

I’ve completed Day 1 of the Databricks AI Challenge, and it was an exciting start to my journey into the Databricks Lakehouse ecosystem.

What I Learned Today:
• Why Databricks over Pandas & Hadoop • Lakehouse Architecture fundamentals • Overview of Databricks Workspace structure • Real‑world industry use cases (Netflix, Shell, Comcast)

Tasks I Completed: 
• Created a Databricks Community Edition account • Explored Workspace, Compute, and Data Explorer • Created my first Databricks notebook • Ran basic PySpark commands

<img width="1901" height="828" alt="image" src="https://github.com/user-attachments/assets/c5cd33d1-63de-4f71-a332-a8344bdf37ee" />

# DAY 2 (10/01/26) – Apache Spark Fundamentals

I’ve completed Day 2 of the Databricks AI Challenge, where the focus was on building strong fundamentals in Apache Spark and understanding how data is processed at scale.

What I Learned Today:
• Apache Spark architecture (Driver, Executors, DAG) • Difference between DataFrames and RDDs • Concept of lazy evaluation in Spark • Usage of notebook magic commands (%sql, %python, %fs)

Tasks I Completed:
• Uploaded a sample e‑commerce CSV file • Read data into Spark DataFrames • Performed basic operations like select, filter, groupBy, and orderBy • Exported processed results

<img width="1915" height="902" alt="image" src="https://github.com/user-attachments/assets/b3db2bf1-236f-4b02-a058-02746cc94104" />
<img width="1913" height="890" alt="image" src="https://github.com/user-attachments/assets/2b290189-1fa2-4a8f-bb78-7caa01ba44a4" />
<img width="1914" height="895" alt="image" src="https://github.com/user-attachments/assets/b317c849-91ce-4260-b910-a4d62f538ef9" />

 # DAY 3 (11/01/26) – PySpark Transformations Deep Dive

I’ve completed Day 3 of the Databricks AI Challenge, and today was all about going deeper into PySpark transformations and real-world data processing.

What I Learned Today:
• Key differences between PySpark and Pandas for large-scale data processing
• Implementing joins (inner, left, right, full outer) in PySpark
• Using window functions for running totals and ranking analytics
• Creating and applying User-Defined Functions (UDFs)

Tasks I Completed:
• Loaded the full e-commerce dataset into Databricks
• Performed complex joins across multiple tables
• Calculated running totals using window functions
• Built derived features for analytical use cases

<img width="1916" height="899" alt="image" src="https://github.com/user-attachments/assets/c264fa61-97e7-4f9e-8d14-640307856e4f" />
<img width="1919" height="613" alt="image" src="https://github.com/user-attachments/assets/ba34914e-5243-4f24-88cd-24e33997741a" />
<img width="1918" height="772" alt="image" src="https://github.com/user-attachments/assets/e57b4224-dd72-43d1-aadd-260360908f66" />

# DAY 4 (12/01/26)– Delta Lake Introduction

I’ve completed Day 4 of the Databricks AI Challenge, focusing on Delta Lake fundamentals and reliability in data engineering.

What I Learned Today:
• Understanding Delta Lake architecture and how it extends Parquet
• How ACID transactions ensure data consistency in distributed systems
• Schema enforcement vs schema evolution in Delta tables
• Key differences between Delta Lake and Parquet for analytics workloads

Tasks I Completed:
• Converted raw CSV data into Delta format
• Created managed Delta tables using SQL and PySpark
• Tested schema enforcement by attempting invalid writes
• Handled duplicate inserts using Delta Lake constraints and overwrite strategies

<img width="1912" height="911" alt="image" src="https://github.com/user-attachments/assets/79b3aa39-81b9-44c7-bb9e-d6c3a2099ed4" />
<img width="1919" height="886" alt="image" src="https://github.com/user-attachments/assets/c1890565-d8a2-4e0e-b65f-52f8a629f05a" />

# PHASE 2: DATA ENGINEERING (Days 5-8)
# DAY 5 (13/01/26) – Delta Lake Advanced

I’ve successfully completed Day 5 of the Databricks AI Challenge, diving deep into advanced Delta Lake operations that enable reliable, high-performance data engineering workflows.

What I Learned Today:
• Delta Lake time travel and version history querying
• Incremental data processing using MERGE (upserts)
• Performance tuning with OPTIMIZE and Z-ORDER
• Data lifecycle management using VACUUM

Tasks I Completed:
• Implemented incremental MERGE operations on Delta tables
• Queried historical versions using time travel
• Optimized Delta tables for faster query performance
• Cleaned up obsolete data files using VACUUM

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/57920bfa-56f9-4c02-8d20-a979ed53fab3" />
<img width="1916" height="786" alt="image" src="https://github.com/user-attachments/assets/715c4822-cee3-400f-b224-65a6bc887ff0" />
<img width="1914" height="911" alt="image" src="https://github.com/user-attachments/assets/054c1c03-8d58-4a83-b9d5-60182652290d" />
<img width="1919" height="916" alt="image" src="https://github.com/user-attachments/assets/3978af16-ad9d-42b4-b861-9ad6d40d73ee" />

# DAY 6 (14/01/26) – Medallion Architecture

I’ve successfully completed Day 6 of the Databricks AI Challenge, focusing on building a scalable Medallion Architecture to structure data pipelines for analytics-ready workloads.

What I Learned Today:
• Medallion Architecture: Bronze (raw) → Silver (cleaned) → Gold (aggregated)
• Best practices for designing each data layer
• Incremental processing patterns for efficient data movement

Tasks I Completed:
• Designed a robust 3-layer Medallion architecture
• Built the Bronze layer for raw data ingestion
• Implemented the Silver layer with data cleaning and validation
• Created the Gold layer with business-ready aggregations

<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/83b58cbe-1d1c-4c0e-acda-42acf032417a" />
<img width="1917" height="912" alt="image" src="https://github.com/user-attachments/assets/1a1c8695-660c-48a8-a80f-c077b938d42b" />

# DAY 7 (15/01/26) – Workflows & Job Orchestration

I’ve successfully completed Day 7 of the Databricks AI Challenge, focusing on orchestrating production-grade data pipelines using Databricks Jobs.

What I Learned Today:
• Differences between Databricks Jobs and notebooks
• Building multi-task workflows for end-to-end pipelines
• Using parameters and scheduling for automation
• Implementing error handling and retries

Tasks I Completed:
• Added parameter widgets to notebooks
• Created a multi-task job workflow (Bronze → Silver → Gold)
• Configured task dependencies
• Scheduled automated job execution

<img width="1915" height="901" alt="image" src="https://github.com/user-attachments/assets/0ff1bd88-61c0-4197-9fb5-2379291b3da2" />
<img width="1899" height="870" alt="image" src="https://github.com/user-attachments/assets/4f694321-6c80-4916-b9cd-db6f176aae20" />
<img width="1664" height="750" alt="image" src="https://github.com/user-attachments/assets/3e4b2ae6-b0b2-463e-bf75-04bcafcac190" />
<img width="1919" height="904" alt="Screenshot 2026-01-15 183255" src="https://github.com/user-attachments/assets/3ddfb342-5ce7-47e8-9fa0-82ff45e48258" />
<img width="1918" height="908" alt="image" src="https://github.com/user-attachments/assets/043326f8-2c81-42bd-9945-5e804eb4c2f2" />

# DAY 8 (16/01/26) – Unity Catalog Governance

I’ve successfully completed Day 8 of the Databricks AI Challenge, where the focus was on data governance using Unity Catalog—a critical foundation for secure, scalable, and enterprise-grade data platforms in Databricks.

What I Learned Today:
• Catalog → Schema → Table hierarchy in Unity Catalog
• Fine-grained access control using GRANT / REVOKE
• Understanding and exploring data lineage
• Differences between managed and external tables

Tasks I Completed:
• Created catalogs and schemas in Unity Catalog
• Registered Delta tables under governed catalogs
• Configured permissions for secure data access
• Built views to enable controlled, role-based data consumption

<img width="1919" height="892" alt="image" src="https://github.com/user-attachments/assets/6e92a4cb-81f5-472d-bece-439943343054" />
<img width="1912" height="898" alt="image" src="https://github.com/user-attachments/assets/c190b334-db6c-4160-aa12-399cd88e4ac7" />
<img width="1913" height="871" alt="image" src="https://github.com/user-attachments/assets/d4faa407-c39e-4387-aac0-306fb345b77f" />

# PHASE 3: ADVANCED ANALYTICS (Days 9-11)
# DAY 9 (17/01/26) – SQL Analytics & Dashboards

I’ve successfully completed Day 9 of the Databricks AI Challenge, focused on SQL Warehouses and analytics-driven dashboards—turning curated data into business-ready insights.

What I Learned Today:
• SQL Warehouses architecture and performance considerations
• Writing complex analytical SQL (aggregations, window functions)
• Dashboard creation for business reporting
• Interactive visualizations with filters and refresh schedules

Tasks I Completed:
• Created and configured a SQL Warehouse
• Wrote analytical queries for revenue, funnels, and product insights
• Built dashboards showing revenue trends, funnels, and top products
• Added interactive filters and scheduled data refreshes

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/341f7d9c-7531-4bdd-99ef-bc9f3473055b" />
<img width="1915" height="893" alt="image" src="https://github.com/user-attachments/assets/5e31fe0d-ca7d-4743-9391-2cd7bc806c5c" />
<img width="1919" height="848" alt="image" src="https://github.com/user-attachments/assets/d9d4ffdb-33b7-42a2-bf7a-f52f7baa1d8a" />
<img width="1919" height="837" alt="image" src="https://github.com/user-attachments/assets/02f7b1a2-5ed7-4ffe-913e-69d694474e04" />
<img width="1919" height="891" alt="image" src="https://github.com/user-attachments/assets/1cffd439-3a73-4ea9-83b6-0dcce8591da9" />
<img width="1919" height="872" alt="image" src="https://github.com/user-attachments/assets/c38d8bcd-95b8-4e60-9b62-36d6fac205fc" />

# DAY 10 (18/01/26) – Performance Optimization

I’ve successfully completed Day 10 of the Databricks AI Challenge, focused on query performance optimization—an essential step for building fast, scalable analytics on large datasets.

What I Learned Today:
• Understanding and interpreting Spark SQL query execution plans
• Effective partitioning strategies for large Delta tables
• Performance tuning using OPTIMIZE and ZORDER
• Leveraging caching techniques to reduce query latency

Tasks I Completed:
• Analyzed query execution plans to identify bottlenecks
• Partitioned large tables to improve scan efficiency
• Applied OPTIMIZE and ZORDER for data layout optimization
• Benchmarked performance improvements before and after tuning

<img width="1919" height="850" alt="image" src="https://github.com/user-attachments/assets/05de74da-78c8-48a6-a7b0-161b0defaf26" />
<img width="1916" height="885" alt="image" src="https://github.com/user-attachments/assets/b73238d3-d2b0-47a3-9f39-8a94bd16fc9b" />
<img width="1914" height="655" alt="image" src="https://github.com/user-attachments/assets/21157283-d725-469a-943e-89ef3d8ffa90" />

# DAY 11 (19/01/26) – Statistical Analysis & ML Prep

I’ve successfully completed Day 11 of the Databricks AI Challenge, focused on applying statistical thinking and feature engineering to real-world data—turning raw events into ML-ready insights.

What I Learned Today:
• Descriptive statistics to summarize large datasets
• Hypothesis testing concepts and A/B test design
• Comparing behavioral patterns (weekday vs weekend)
• Feature engineering techniques for machine learning

Tasks I Completed:
• Calculated statistical summaries (mean, variance, distributions)
• Tested hypotheses comparing weekday and weekend behavior
• Identified correlations between key business metrics
• Engineered temporal and behavioral features for ML models

<img width="1916" height="905" alt="image" src="https://github.com/user-attachments/assets/48903f5c-e812-4237-a01f-e250e503108d" />
<img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/daf24148-924e-4534-bb3e-0b973f381fb6" />
<img width="1919" height="464" alt="image" src="https://github.com/user-attachments/assets/36987141-8aeb-4c39-b885-eed2d9e3bfe5" />
<img width="1909" height="908" alt="image" src="https://github.com/user-attachments/assets/63afe41b-76d3-47f3-97dc-d21e493d2d77" />

# PHASE 4: AI & ML (Days 12-14)
# DAY 12 (20/01/26) – MLflow Basics

I successfully completed Day 12 of the Databricks AI Challenge, focused on MLflow fundamentals and experiment tracking.

What I Learned Today:
• MLflow components (tracking, models, registry)
• Experiment tracking concepts
• Logging parameters, metrics, and models
• Using MLflow UI to analyze runs
• Comparing multiple model runs

Tasks I Completed:
• Trained simple regression models
• Logged parameters, metrics, and models to MLflow
• Viewed experiment runs in MLflow UI
• Compared model performance across runs

<img width="1919" height="906" alt="image" src="https://github.com/user-attachments/assets/afff1a3f-15ec-46a6-8d36-d58dc3bf58e4" />

<img width="1919" height="915" alt="image" src="https://github.com/user-attachments/assets/bc3b21c8-eab6-4f85-ac56-436a182119ef" />


<img width="1919" height="906" alt="image" src="https://github.com/user-attachments/assets/c9f80353-8c23-49e2-a8ad-060cce5543d7" />


