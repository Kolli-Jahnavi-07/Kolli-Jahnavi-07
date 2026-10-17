## Hi, I'm Sai Jahnavi Kolli 👋

I'm a data engineer who builds pipelines people can trust: batch and streaming ingestion, warehouse models, and the tests and checks that keep data correct as it changes. I like turning messy source data into clean, well-modeled tables that analysts and applications can rely on.

**What I can do**
- Build batch and real-time pipelines with Spark, Kafka and Python
- Design incremental loads, CDC and SCD Type 2 history in Snowflake and dbt
- Ingest from APIs, databases and files into AWS and Azure, with infrastructure as code
- Add data quality checks, contracts and CI so pipelines fail loudly instead of silently

**What I'm interested in**
- Open lakehouse formats (Apache Iceberg, Delta Lake)
- Data infrastructure for AI: retrieval pipelines, embeddings and evaluation
- Streaming systems and exactly-once processing
- Financial and automotive data

📫 **Contact:** kollijahnavi07@gmail.com · 🌐 [saijahnavikolli.com](https://saijahnavikolli.com)

### Projects

| Project | What it does | Stack |
|---|---|---|
| [**snowflake-incremental-elt**](https://github.com/Kolli-Jahnavi-07/snowflake-incremental-elt) | Continuous CDC ELT on Snowflake: Snowpipe loads, Streams capture changes, a Task graph merges them into current state, SCD2 history and an incremental mart | Snowflake · Snowpipe · Streams · Tasks · SQL · Python · AWS S3 |
| [**multicloud-ingestion-framework**](https://github.com/Kolli-Jahnavi-07/multicloud-ingestion-framework) | Config-driven ingestion from REST APIs, databases and vendor files into S3 and ADLS Gen2, with data contracts and crash-safe MERGE loads into Snowflake | Python · AWS · Azure Data Factory · ADLS Gen2 · Snowflake · Terraform · Docker |
| [**iceberg-lakehouse**](https://github.com/Kolli-Jahnavi-07/iceberg-lakehouse) | EV battery-health lakehouse on Apache Iceberg: upserts, schema and partition evolution, time travel, compaction | Apache Iceberg · PyIceberg · DuckDB · Parquet · AWS Glue · Snowflake |
| [**rag-ingestion-pipeline**](https://github.com/Kolli-Jahnavi-07/rag-ingestion-pipeline) | The data side of RAG: incremental document sync, PII redaction, chunking, embedding cache, hybrid search and a retrieval-quality gate in CI | Python · Embeddings · Vector search · BM25 · DuckDB · pgvector |
| [**realtime-fraud-streaming**](https://github.com/Kolli-Jahnavi-07/realtime-fraud-streaming) | Real-time card-fraud detection: windowed rules, stream-stream joins and watermarks, with exactly-once writes to Delta Lake | Kafka · Spark Structured Streaming · Delta Lake · Python · Docker |
| [**automotive-loan-risk-analytics**](https://github.com/Kolli-Jahnavi-07/automotive-loan-risk-analytics) | Loan risk warehouse: raw applications to a tested star schema with delinquency and roll-rate marts | PySpark · dbt · Snowflake · Airflow · SQL |
| [**de-medallion-pipeline**](https://github.com/Kolli-Jahnavi-07/de-medallion-pipeline) | CDC pipeline through bronze, silver and gold with SCD Type 2 history, reconciled row for row against the source | Python · DuckDB · SQL · Airflow · CDC · SCD2 |
| [**DataWhisperer**](https://github.com/Kolli-Jahnavi-07/DataWhisperer) · [live demo](https://kolli-jahnavi-07.github.io/DataWhisperer/) | Profile any CSV in the browser: quality checks, health score, generated dbt tests and warehouse DDL | DuckDB-WASM · TypeScript · SQL · Vite · Playwright |

### Toolbox

- **Languages:** Python, SQL, PySpark, TypeScript
- **Processing:** Apache Spark, Spark Structured Streaming, Kafka, dbt, DuckDB, Apache Iceberg
- **Cloud and warehouse:** AWS (S3, IAM, Glue), Azure (Data Factory, Databricks, Synapse, ADLS Gen2), Snowflake (Snowpipe, Streams, Tasks), Delta Lake
- **Orchestration and DevOps:** Airflow, Azure Data Factory, Terraform, GitHub Actions, Docker
- **AI data:** RAG pipelines, embeddings, vector and hybrid search, retrieval evaluation
