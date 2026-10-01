<!--
  Profile README for github.com/Logicalengineer109
  Publish: create a PUBLIC repo named exactly Logicalengineer109, then upload README.md,
  data-platform.svg and flow.svg (all three in the main folder).
  To add email or LinkedIn, paste these into the "Get in touch" block next to the GitHub badge:
  [![Email](https://img.shields.io/badge/email-me-0f766e?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0b1320)](mailto:YOUR-EMAIL)
  [![LinkedIn](https://img.shields.io/badge/linkedin-connect-0f766e?style=for-the-badge&labelColor=0b1320)](https://linkedin.com/in/YOUR-HANDLE)
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0b1320,55:0f766e,100:10b981&height=200&section=header&text=Logical%20Engineer&fontSize=46&fontColor=e6fffa&fontAlign=30&fontAlignY=38&desc=Senior%20Data%20Engineer%20%C2%B7%20Sydney%2C%20Australia&descSize=17&descAlign=30&descAlignY=58&rotate=0" width="100%" alt="Logical Engineer, Senior Data Engineer" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1600&color=2DD4BF&center=true&vCenter=true&width=780&lines=%3E+SELECT+*+FROM+pipelines+WHERE+trusted+%3D+true%3B;%3E+dbt+build+--select+marts+%E2%9C%94+all+tests+passed;%3E+kafka+%E2%86%92+spark+%E2%86%92+delta+%7C+streaming+in+near+real+time;%3E+airflow+dags+trigger+daily_elt+%E2%9C%94+success;%3E+raw+data+%E2%86%92+trusted+models+%E2%86%92+better+decisions" alt="Typing SVG" />
</a>

<br/>

![focus](https://img.shields.io/badge/focus-batch%20%C2%B7%20streaming%20%C2%B7%20CDC-0f766e?style=flat&labelColor=0b1320)
![warehouses](https://img.shields.io/badge/warehouses-Snowflake%20%C2%B7%20Databricks%20%C2%B7%20BigQuery-0f766e?style=flat&labelColor=0b1320)
![pipelines](https://img.shields.io/badge/pipelines-passing-10b981?style=flat&labelColor=0b1320&logo=apacheairflow&logoColor=white)

</div>

<br/>

I build the data infrastructure that product and business decisions run on. My work starts at messy source systems (production databases, event streams, SaaS APIs and flat files) and ends at **data models that analysts, dashboards and ML systems can trust without double-checking**. Along the way I care about three things: **correctness, observability and cost**.

---

## 🎯 What I own

| Area | What it looks like in production |
|:--|:--|
| **Ingestion** | Python ETL/ELT from REST APIs (auth, pagination, rate limits), SaaS tools (Shopify, HubSpot, Salesforce, Stripe, Qualtrics), SFTP files and production databases |
| **Incremental loads** | Watermark and control tables, `MERGE` upserts, soft deletes, idempotent reruns, backfills and schema drift detection |
| **Streaming & CDC** | Kafka, Kafka Connect and Debezium feeding Spark Structured Streaming, Delta Lake and Snowpipe for near-real-time views |
| **Modeling** | Kimball star schemas, conformed dimensions, surrogate keys, SCD Type 2, One Big Table and medallion layers, with the grain agreed first |
| **Transformation** | dbt incremental models, snapshots, macros, exposures, docs, data contracts and the dbt Semantic Layer |
| **Orchestration** | Airflow, Dagster, Prefect, Databricks Workflows and GitHub Actions for scheduling, dependencies, backfills and failure recovery |
| **Quality & observability** | dbt tests, Great Expectations, freshness SLAs, anomaly alerts, lineage, runbooks and data dictionaries |
| **Cost & performance** | Partitioning, clustering, incremental models, query tuning, right-sized compute and cost per pipeline |
| **ML & AI readiness** | MLflow, Unity Catalog, Feature Store, Snowflake Cortex, semantic views, vector search and MCP servers over governed data |

---

## 🗺️ Platform blueprint

<p align="center">
  <img src="data-platform.svg" width="100%" alt="Data platform blueprint: sources, ingestion with batch, CDC and streaming, a lakehouse or warehouse with bronze, silver and gold layers, transformations with dbt and Spark, then analytics, ML and AI, with orchestration, data quality and governance underneath" />
</p>

---

## 🧰 Stack by layer

| Layer | Tools |
|:--|:--|
| **Languages** | ![Python](https://img.shields.io/badge/-Python-0b1320?style=flat&logo=python&logoColor=3776AB) ![SQL](https://img.shields.io/badge/-SQL-0b1320?style=flat&logo=postgresql&logoColor=5eead4) ![PySpark](https://img.shields.io/badge/-PySpark-0b1320?style=flat&logo=apachespark&logoColor=E25A1C) ![Scala](https://img.shields.io/badge/-Scala-0b1320?style=flat&logo=scala&logoColor=DC322F) ![Bash](https://img.shields.io/badge/-Bash-0b1320?style=flat&logo=gnubash&logoColor=4EAA25) ![pandas](https://img.shields.io/badge/-pandas-0b1320?style=flat&logo=pandas&logoColor=white) |
| **Warehouse & lakehouse** | ![Snowflake](https://img.shields.io/badge/-Snowflake-0b1320?style=flat&logo=snowflake&logoColor=29B5E8) ![Databricks](https://img.shields.io/badge/-Databricks-0b1320?style=flat&logo=databricks&logoColor=FF3621) ![BigQuery](https://img.shields.io/badge/-BigQuery-0b1320?style=flat&logo=googlebigquery&logoColor=669DF6) ![Redshift](https://img.shields.io/badge/-Redshift-0b1320?style=flat) ![Delta Lake](https://img.shields.io/badge/-Delta%20Lake-0b1320?style=flat) ![Unity Catalog](https://img.shields.io/badge/-Unity%20Catalog-0b1320?style=flat&logo=databricks&logoColor=FF3621) ![Iceberg](https://img.shields.io/badge/-Iceberg-0b1320?style=flat) ![DuckDB](https://img.shields.io/badge/-DuckDB-0b1320?style=flat&logo=duckdb&logoColor=FFF000) |
| **Streaming & CDC** | ![Kafka](https://img.shields.io/badge/-Kafka-0b1320?style=flat&logo=apachekafka&logoColor=white) ![Kafka Connect](https://img.shields.io/badge/-Kafka%20Connect-0b1320?style=flat&logo=apachekafka&logoColor=white) ![Debezium](https://img.shields.io/badge/-Debezium-0b1320?style=flat) ![Spark Streaming](https://img.shields.io/badge/-Structured%20Streaming-0b1320?style=flat&logo=apachespark&logoColor=E25A1C) ![Kinesis](https://img.shields.io/badge/-Kinesis-0b1320?style=flat) ![Flink](https://img.shields.io/badge/-Flink-0b1320?style=flat&logo=apacheflink&logoColor=E6526F) ![Snowpipe](https://img.shields.io/badge/-Snowpipe-0b1320?style=flat&logo=snowflake&logoColor=29B5E8) |
| **Transform & orchestrate** | ![dbt](https://img.shields.io/badge/-dbt-0b1320?style=flat&logo=dbt&logoColor=FF694B) ![dbt Semantic Layer](https://img.shields.io/badge/-dbt%20Semantic%20Layer-0b1320?style=flat&logo=dbt&logoColor=FF694B) ![Airflow](https://img.shields.io/badge/-Airflow-0b1320?style=flat&logo=apacheairflow&logoColor=017CEE) ![Dagster](https://img.shields.io/badge/-Dagster-0b1320?style=flat&logo=dagster&logoColor=white) ![Prefect](https://img.shields.io/badge/-Prefect-0b1320?style=flat&logo=prefect&logoColor=white) ![Databricks Workflows](https://img.shields.io/badge/-Databricks%20Workflows-0b1320?style=flat&logo=databricks&logoColor=FF3621) ![Fivetran](https://img.shields.io/badge/-Fivetran-0b1320?style=flat&logo=fivetran&logoColor=0073FF) ![Airbyte](https://img.shields.io/badge/-Airbyte-0b1320?style=flat&logo=airbyte&logoColor=615EFF) ![n8n](https://img.shields.io/badge/-n8n-0b1320?style=flat&logo=n8n&logoColor=EA4B71) |
| **Modeling** | ![Kimball](https://img.shields.io/badge/-Kimball-0f766e?style=flat) ![Star Schema](https://img.shields.io/badge/-Star%20Schema-0f766e?style=flat) ![SCD2](https://img.shields.io/badge/-SCD%20Type%202-0f766e?style=flat) ![Medallion](https://img.shields.io/badge/-Medallion-0f766e?style=flat) ![OBT](https://img.shields.io/badge/-One%20Big%20Table-0f766e?style=flat) ![Data Vault](https://img.shields.io/badge/-Data%20Vault%202.0-0f766e?style=flat) ![Data Contracts](https://img.shields.io/badge/-Data%20Contracts-0f766e?style=flat) ![Semantic Layer](https://img.shields.io/badge/-Semantic%20Layer-0f766e?style=flat) |
| **Quality & governance** | ![dbt tests](https://img.shields.io/badge/-dbt%20tests-0b1320?style=flat&logo=dbt&logoColor=FF694B) ![Great Expectations](https://img.shields.io/badge/-Great%20Expectations-0b1320?style=flat) ![pytest](https://img.shields.io/badge/-pytest-0b1320?style=flat&logo=pytest&logoColor=0A9EDC) ![Soda](https://img.shields.io/badge/-Soda-0b1320?style=flat) ![OpenLineage](https://img.shields.io/badge/-OpenLineage-0b1320?style=flat) ![DataHub](https://img.shields.io/badge/-DataHub-0b1320?style=flat) ![RBAC](https://img.shields.io/badge/-RBAC%20%26%20PII%20masking-0b1320?style=flat) |
| **ML, AI & BI** | ![MLflow](https://img.shields.io/badge/-MLflow-0b1320?style=flat&logo=mlflow&logoColor=0194E2) ![Feature Store](https://img.shields.io/badge/-Feature%20Store-0b1320?style=flat&logo=databricks&logoColor=FF3621) ![Cortex](https://img.shields.io/badge/-Snowflake%20Cortex-0b1320?style=flat&logo=snowflake&logoColor=29B5E8) ![MCP](https://img.shields.io/badge/-MCP-0b1320?style=flat&logo=modelcontextprotocol&logoColor=white) ![pgvector](https://img.shields.io/badge/-pgvector-0b1320?style=flat&logo=postgresql&logoColor=5eead4) ![Power BI](https://img.shields.io/badge/-Power%20BI-0b1320?style=flat) ![Looker](https://img.shields.io/badge/-Looker-0b1320?style=flat&logo=looker&logoColor=4285F4) ![Tableau](https://img.shields.io/badge/-Tableau-0b1320?style=flat) ![Streamlit](https://img.shields.io/badge/-Streamlit-0b1320?style=flat&logo=streamlit&logoColor=FF4B4B) |
| **Cloud & DevOps** | ![AWS](https://img.shields.io/badge/-AWS%20(S3%20%C2%B7%20Lambda%20%C2%B7%20Glue%20%C2%B7%20Secrets%20Manager%20%C2%B7%20IAM)-0b1320?style=flat) ![GCP](https://img.shields.io/badge/-GCP-0b1320?style=flat&logo=googlecloud&logoColor=4285F4) ![Azure](https://img.shields.io/badge/-Azure-0b1320?style=flat) ![Terraform](https://img.shields.io/badge/-Terraform-0b1320?style=flat&logo=terraform&logoColor=7B42BC) ![Docker](https://img.shields.io/badge/-Docker-0b1320?style=flat&logo=docker&logoColor=2496ED) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-0b1320?style=flat&logo=kubernetes&logoColor=326CE5) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-0b1320?style=flat&logo=githubactions&logoColor=2088FF) ![Jenkins](https://img.shields.io/badge/-Jenkins-0b1320?style=flat&logo=jenkins&logoColor=D24939) |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-0b1320?style=flat&logo=postgresql&logoColor=4169E1) ![MySQL](https://img.shields.io/badge/-MySQL-0b1320?style=flat&logo=mysql&logoColor=4479A1) ![SQL Server](https://img.shields.io/badge/-SQL%20Server-0b1320?style=flat) ![MongoDB](https://img.shields.io/badge/-MongoDB-0b1320?style=flat&logo=mongodb&logoColor=47A248) ![Redis](https://img.shields.io/badge/-Redis-0b1320?style=flat&logo=redis&logoColor=DC382D) |
| **Daily tools** | ![Git](https://img.shields.io/badge/-Git-0b1320?style=flat&logo=git&logoColor=F05033) ![Jira](https://img.shields.io/badge/-Jira-0b1320?style=flat&logo=jira&logoColor=2684FF) ![Datadog](https://img.shields.io/badge/-Datadog-0b1320?style=flat&logo=datadog&logoColor=632CA6) ![Grafana](https://img.shields.io/badge/-Grafana-0b1320?style=flat&logo=grafana&logoColor=F46800) ![Claude Code](https://img.shields.io/badge/-Claude%20Code-0b1320?style=flat&logo=anthropic&logoColor=D97757) ![Cursor](https://img.shields.io/badge/-Cursor-0b1320?style=flat&logo=cursor&logoColor=white) |

---

## 🔁 How I work

<p align="center">
  <img src="flow.svg" width="100%" alt="How I work, drawn as a pipeline DAG: understand, model, build, test, operate" />
</p>

## 📐 Principles I build by

1. **Agree on the grain before writing SQL.** Most broken dashboards trace back to a fact table nobody defined.
2. **Every load can run twice.** Pipelines are incremental and idempotent, so a rerun or backfill never creates duplicates.
3. **Tests ship with the model.** Schema tests, contracts and freshness checks live in the same PR as the code.
4. **If it isn't monitored, it isn't done.** Every pipeline has an owner, an alert and a runbook.
5. **Cost is a feature.** Partitioning, incremental models and right-sized compute are part of the design, not a cleanup task.
6. **AI assistants speed me up, not sign off for me.** I use them for drafting, review and debugging, and I own every line that ships.

---

<!--
  Uncomment this section once these repos exist and are public, then check the links.

## 📂 Featured projects

| Project | What it shows | Stack |
|:--|:--|:--|
| [snowflake-saas-elt-framework](https://github.com/Logicalengineer109/snowflake-saas-elt-framework) | Config-driven API ingestion, MERGE upserts, watermarks, SCD2 star schema | Python · Snowflake · dbt · GitHub Actions · AWS |
| [realtime-cdc-medallion-lakehouse](https://github.com/Logicalengineer109/realtime-cdc-medallion-lakehouse) | Postgres CDC to a bronze, silver and gold lakehouse in near real time | Debezium · Kafka · Spark Streaming · Delta · Airflow |
| [governed-llm-retrieval-mcp](https://github.com/Logicalengineer109/governed-llm-retrieval-mcp) | MCP server over governed tables with masking enforced at query time | Databricks · Unity Catalog · pgvector · MCP |
| [lakehouse-cost-observability](https://github.com/Logicalengineer109/lakehouse-cost-observability) | Cost per pipeline and freshness SLA models with alerts | dbt · Snowflake · Streamlit · Grafana |
| [databricks-campaign-forecasting-lift](https://github.com/Logicalengineer109/databricks-campaign-forecasting-lift) | Campaign forecasting and incrementality testing as an MLOps pipeline | PySpark · MLflow · Unity Catalog · Asset Bundles |

---
-->

## 📬 Get in touch

Need a data platform built, pipelines nobody trusts fixed, or your data made ready for BI and AI? Let's talk.

<div align="center">

[![GitHub](https://img.shields.io/badge/github-Logicalengineer109-0f766e?style=for-the-badge&logo=github&logoColor=white&labelColor=0b1320)](https://github.com/Logicalengineer109)

<br/>

![Profile Views](https://visitor-badge.laobi.icu/badge?page_id=Logicalengineer109.Logicalengineer109&left_text=profile%20views&left_color=%230b1320&right_color=%230f766e)

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:10b981,45:0f766e,100:0b1320&height=90&section=footer&rotate=180" width="100%" alt="" />

</div>
