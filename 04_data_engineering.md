# Data Engineering

## Overview

- *cult*: "Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems" [Martin Kleppmann; book; 2017-04](https://github.com/jeffrey-xiao/papers/blob/master/textbooks/designing-data-intensive-applications.pdf)
- *introductionary*: "Data Engineering on GCP Cheatsheet" [GitHub; Cheatsheet; 2018](https://github.com/ml874/Data-Engineering-on-GCP-Cheatsheet/blob/master/data_engineering_on_GCP.pdf)

## Data Architectures

### Data Lake: 
- AWS S3, GCS

### Data Warehouse
- Redshift, Athena, BigQuery, Snowflake, Teradata

### Data Lakehouse

- *cult*: "Lakehouse: A New Generation of Open Platforms that Unify Data Warehousing and Advanced Analytics" [Databricks; paper; 2020-12](https://www.cidrdb.org/cidr2021/papers/cidr2021_paper17.pdf)
- Overview: "The Fundamentals of Data Warehouse + Data Lake = Lake House" [Garrett R Peternel; blog post; 2021-08-27](https://towardsdatascience.com/the-fundamentals-of-data-warehouse-data-lake-lake-house-ff640851c832)
- **Databricks** overview: "Master Databricks and Apache Spark Step by Step" [Bryan Cafferky; YouTube Playlist; 2021-01](https://www.youtube.com/playlist?list=PL7_h0bRfL52qWoCcS18nXcT1s-5rSa1yp)
- **BigLake** on Google Cloud Platform (GCP): "BigLake: unifying data lakes and data warehouses across clouds" [Google; blog post; 2022-04-06](https://cloud.google.com/blog/products/data-analytics/unifying-data-lakes-and-data-warehouses-across-clouds-with-biglake)
- Delta Lake, Apache Iceberg, Snowflake

### Data Vault (2.0)
- 

### SQL Databases
- postgresql, mysql

### NoSQL Databases
- cassandra, mongoDB, redis, memcache, Elasticsearch

### Feature Stores
A Feature Store is a data management layer for machine learning that allows to share & discover features and create more effective machine learning pipelines (https://www.featurestore.org/).

- Open Source:
  - [Feast (feature store)](https://docs.feast.dev/)
    - Using [Redis](https://redis.com/blog/building-feature-stores-with-redis-introduction-to-feast-with-redis/)
    - Using [Google Cloud (Datastore/BigQuery)](https://docs.feast.dev/reference/providers/google-cloud-platform)
    - Example Demo using GCP: "Feature Store for Machine Learning - MLOps" [AI Engineering; YouTube 2021-04](https://www.youtube.com/watch?v=ZeJdr0nZ9PA&ab_channel=AIEngineering)
- Proprietary
  - [Google: Vertex AI Feature Store](https://cloud.google.com/vertex-ai/docs/featurestore?hl=de)
  - [Databricks](https://docs.databricks.com/applications/machine-learning/feature-store/index.html)
  - [Amazon SageMaker Feature Store](https://aws.amazon.com/de/sagemaker/feature-store/)
  - [Microsoft Azure](https://techcommunity.microsoft.com/t5/ai-customer-engineering-team/bringing-feature-store-to-azure-from-microsoft-azure-redis-and/ba-p/2918917)
  - [H20](https://h2o.ai/platform/ai-cloud/make/feature-store/)


## Data Processing
- Batch:
  - Hadoop und Spark (Cluster) 
    - [Google Cloud Dataproc](https://cloud.google.com/dataproc) (also supports Apache Flink, Presto and other frameworks)
    - [AWS EMR](https://aws.amazon.com/de/emr/) (Elastic MapReduce, Hadoop, Presto etc. clusters)
    - [Azure HDInsight](https://azure.microsoft.com/de-de/services/hdinsight/#overview) (Hadoop, Spark, R Server, HBase, Storm, etc. clusters)
- Streaming: Spark, Flink, Storm, Kafka, RabbitMQ (message broker)
- Lambda Architecture (Streaming+Batch): Spark ("How we built a data pipeline with Lambda Architecture using Spark/Spark Streaming" [Walmart Global Tech Blog; Blog; 2018-06](https://medium.com/walmartglobaltech/how-we-built-a-data-pipeline-with-lambda-architecture-using-spark-spark-streaming-9d3b4b4555d3))
- Delta (Lake) Architecture (beyond lambda): Databricks [Databricks; YouTube; 2020](https://www.youtube.com/watch?v=FePv0lro0z8&t=49s&ab_channel=Databricks)
- Logging: Fluentd, logstash
  
## Orchestration:
- Airflow
- Google Cloud Composer
 
## Big Data Tools
- Hadoop Ecosystem: Core (MapReduce), HDFS, Hive (SQL), Mahout (ML service), Pig (ETL jobs), Yarn ("**Y**et **A**nother **R**esource **N**egotiator") [Zookeeper, HBase, Lucene, Solr, Storm]
- Spark Ecosystem: Core, Streaming, SQL, MLlib, GraphX
  
## Data formats
- HDFS
- Parquet
- Avro
- JSON, bson
- protobuf

## Modern Data Stacks

- "The Post Modern Data Stack" [Jacopo Tagliabue; YouTube; 2022-04](https://www.youtube.com/watch?v=5kHDb-XGHtc&ab_channel=JacopoTagliabue)

## DataOps

- ETL: Extract Transform Load
  - Orchestration:
    - **Dagster**: Phython library "Build ETL Pipelines with Dagster" [Haq Nawaz; Blog; 2022-06](https://blog.devgenius.io/build-etl-pipelines-with-dagster-4c5f2ac678db)
    - Airflow (GCP Composer)
    - Luigi
    - Argo (Kubernetes, also for GitOps)
  - Tools: Spark, GCP Dataflow / Data Fusion, AWS Glue, Azure Data Factory, Informatica
- ELT: Extract Load Transform-> [dbt (data build tool)](https://docs.getdbt.com/docs/introduction)
  - beginner: "DBT: A new way to transform data and build pipelines at The Telegraph" [Stefano Solimito; Blog; 2019-08](https://medium.com/the-telegraph-engineering/dbt-a-new-way-to-handle-data-transformation-at-the-telegraph-868ce3964eb4)
  - intermediate: "Practical tips to get the best out of Data Build Tool (dbt) — Part 1" [Stefano Solimito; Blog; 2020-03](https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-building-tool-dbt-part-1-8cfa21ef97c5)
- Data Catalogs / Discovery: GCP Dataplex / Data Catalog "26 Data Catalogs – From Open Source To Managed" [Seattle Data Guy; Blog; 2022-08](https://www.theseattledataguy.com/26-data-catalogs-from-open-source-to-managed/#page-content)
- Master Data Management (MDM): managing, storing main enterprise data which rarely changes (e.g. customers, products) that all departments have a common vire (single source of truth)
   - "What is master data management(MDM) | mdm architecture & products (2022)" [IT k Funde; YouTube; 2022-05](https://www.youtube.com/watch?v=qCEbL1TXOtw&list=PLcnJIHtHiTA2HmIleev4scARSFwrQ0bIy&index=18&ab_channel=ITkFunde)
   - Tools: Ataccama, Informatica, SAP
 - 5 Data Challenges: Data Discovery, Data Quality, Data Auditing & Monitoring (Compliance; Lacks Maturing+Tools), Data Masking/Anonymization, Data & Business Value Generation

## Data Engineering on the Cloud

### Google Cloud (GCP)

#### Overview

- "Google Cloud documentation: Guides for GCP products, services and APIs" [Google; Documentation; 2022](https://cloud.google.com/docs)
- "Cloud Architecture Center: reference architectures, diagrams, design patterns, guidance, and best practices" [Google; Architecture Center; 2022](https://cloud.google.com/architecture)

#### GCP Professional Data Engineer Certification

- **Google Cloud Data Engineer Dossier** from Linux Academy: Overview of GCP services regarding data engineering [see Lucid Chart](https://lucid.app/lucidchart/0ca44a63-4ea4-4d78-8367-2465512d21be/view?page=5CetVcvv3YSZ#)
- **Cheatsheet Videos** for Google Cloud Data Engineer Exam [IT Cheer Up; YouTube Videos; 2021-01](https://www.youtube.com/playlist?list=PLWXckUXLY7LwbBz6eyYzDocZo1vkvRWC7)
- **Learning Videos**: Google Cloud Professional Data Engineer Certification [Google; YouTube Playlist; 2020-10](https://www.youtube.com/playlist?list=PLWXckUXLY7LzOBySwKXb9fqejwpGcnAwi)

