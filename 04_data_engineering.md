# Data Engineering

- Data Architectures
  - Data Lake: AWS S3, GCS
  - Data Warehouse: Redshift, BigQuery
  - **Data Lakehouse**: databricks, Delta Lake, Apache Iceberg, Snowflake
    - Overview: "The Fundamentals of Data Warehouse + Data Lake = Lake House" [Garrett R Peternel; blog post; 2021-08-27](https://towardsdatascience.com/the-fundamentals-of-data-warehouse-data-lake-lake-house-ff640851c832)
  - SQL Databases: postgresql, mysql
  - NoSQL Databases: cassandra, mongoDB, redis, memcache, Elasticsearch

Data Processing:
  - Batch: Spark, Hadoop
  - Streaming: Spark, Flink, Storm, Kafka, RabbitMQ (message broker)
  - Logging: Fluentd, logstash
  
 Orchestration:
   - Airflow
 
 - Big Data Tools
   - Hadoop Ecosystem: Core (MapReduce), HDFS, Hive (SQL), Mahout (ML service), Pig (ETL jobs), Yarn ("**Y**et **A**nother **R**esource **N**egotiator") [Zookeeper, HBase, Lucene, Solr, Storm]
   - Spark Ecosystem: Core, Streaming, SQL, MLlib, GraphX
  
 - Data formats
   - HDFS
   - Parquet
   - Avro
   - JSON, bson
   - protobuf
