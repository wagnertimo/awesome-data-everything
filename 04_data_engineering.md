# Data Engineering
## Data Architectures
- Data Lake: AWS S3, GCS
- Data Warehouse: Redshift, BigQuery
- **Data Lakehouse**: databricks, Delta Lake, Apache Iceberg, Snowflake
  - Overview: "The Fundamentals of Data Warehouse + Data Lake = Lake House" [Garrett R Peternel; blog post; 2021-08-27](https://towardsdatascience.com/the-fundamentals-of-data-warehouse-data-lake-lake-house-ff640851c832)
  - **databricks** overview: "Master Databricks and Apache Spark Step by Step" [Bryan Cafferky; YouTube Playlist; 2021-01](https://www.youtube.com/playlist?list=PL7_h0bRfL52qWoCcS18nXcT1s-5rSa1yp)
  - **BigLake** on Google Cloud Platform (GCP): "BigLake: unifying data lakes and data warehouses across clouds" [Google; blog post; 2022-04-06](https://cloud.google.com/blog/products/data-analytics/unifying-data-lakes-and-data-warehouses-across-clouds-with-biglake)
- SQL Databases: postgresql, mysql
- NoSQL Databases: cassandra, mongoDB, redis, memcache, Elasticsearch

## Data Processing
- Batch:
  - Hadoop und Spark (Cluster) 
    - [Google Cloud Dataproc](https://cloud.google.com/dataproc) (also supports Apache Flink, Presto and other frameworks)
    - [AWS EMR](https://aws.amazon.com/de/emr/) (Elastic MapReduce)
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
