# Data Engineering

## Overview

- *cult*: "Designing Data-Intensive Applications: The Big Ideas Behind Reliable, Scalable, and Maintainable Systems" [Martin Kleppmann; book; 2017-04](https://github.com/jeffrey-xiao/papers/blob/master/textbooks/designing-data-intensive-applications.pdf)
- 

## Data Architectures

### Data Lake: 
- AWS S3, GCS

### Data Warehouse
- Redshift, BigQuery

### Data Lakehouse

- *cult*: "Lakehouse: A New Generation of Open Platforms that Unify Data Warehousing and Advanced Analytics" [Databricks; paper; 2020-12](https://www.cidrdb.org/cidr2021/papers/cidr2021_paper17.pdf)
- Overview: "The Fundamentals of Data Warehouse + Data Lake = Lake House" [Garrett R Peternel; blog post; 2021-08-27](https://towardsdatascience.com/the-fundamentals-of-data-warehouse-data-lake-lake-house-ff640851c832)
- **Databricks** overview: "Master Databricks and Apache Spark Step by Step" [Bryan Cafferky; YouTube Playlist; 2021-01](https://www.youtube.com/playlist?list=PL7_h0bRfL52qWoCcS18nXcT1s-5rSa1yp)
- **BigLake** on Google Cloud Platform (GCP): "BigLake: unifying data lakes and data warehouses across clouds" [Google; blog post; 2022-04-06](https://cloud.google.com/blog/products/data-analytics/unifying-data-lakes-and-data-warehouses-across-clouds-with-biglake)
- Delta Lake, Apache Iceberg, Snowflake

### SQL Databases
- postgresql, mysql

### NoSQL Databases
- cassandra, mongoDB, redis, memcache, Elasticsearch

## Data Processing
- Batch:
  - Hadoop und Spark (Cluster) 
    - [Google Cloud Dataproc](https://cloud.google.com/dataproc) (also supports Apache Flink, Presto and other frameworks)
    - [AWS EMR](https://aws.amazon.com/de/emr/) (Elastic MapReduce, Hadoop, Presto etc. clusters)
    - [Azure HDInsight](https://azure.microsoft.com/de-de/services/hdinsight/#overview) (Hadoop, Spark, R Server, HBase, Storm, etc. clusters)
- Streaming: Spark, Flink, Storm, Kafka, RabbitMQ (message broker)
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
- ELT: Extract Load Transform-> [dbt (data build tool)](https://docs.getdbt.com/docs/introduction)
  - beginner: "DBT: A new way to transform data and build pipelines at The Telegraph" [Stefano Solimito; Blog; 2019-08](https://medium.com/the-telegraph-engineering/dbt-a-new-way-to-handle-data-transformation-at-the-telegraph-868ce3964eb4)
  - intermediate: "Practical tips to get the best out of Data Build Tool (dbt) — Part 1" [Stefano Solimito; Blog; 2020-03](https://medium.com/photobox-technology-product-and-design/practical-tips-to-get-the-best-out-of-data-building-tool-dbt-part-1-8cfa21ef97c5)



