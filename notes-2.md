### Databases in AWS

- **RDBMS (= SQL / OLTP):** RDS, Aurora – great for joins

- **NoSQL database** – no joins, no SQL : DynamoDB (~JSON), ElastiCache (key / value pairs), Neptune (graphs), DocumentDB (for MongoDB), Keyspaces (for Apache Cassandra)

- **Object Store:** S3 (for big objects) / Glacier (for backups / archives)

- **Data Warehouse** (= SQL Analytics / BI): Redshift (OLAP), Athena, EMR

- **Search:** OpenSearch (JSON) – free text, unstructured searches

- **Graphs:** Amazon Neptune – displays relationships between data

- **Ledger:** Amazon Quantum Ledger Database => recording financial transactions

- **Time series:** Amazon Timestream

- **DocumentDB:** DocumentDB is the same for MongoDB (which is a NoSQL database)

- DocumentDB doesn't have a Serverless option and it doesn't have a global database feature.

- Apache Cassandra database => Amazon Keyspaces


### Data & Analytics



#### Amazon Athena
- Serverless query service to analyze data stored in Amazon S3
- Performance Improvement => columnar data, Compress data, Use larger files, Partition
- Allows you to run SQL queries across data stored in relational, non-relational, object, and custom data sources


#### Redshift
- Redshift is based on PostgreSQL, but it’s not used for OLTP


#### OpenSearch Service
- With OpenSearch, you can search any field, even partially matches


#### Amazon EMR
- EMR helps creating Hadoop clusters (Big Data) to analyze and process vast amount of data
- Use cases: data processing, machine learning, web indexing, big data


#### Amazon QuickSight
- Serverless machine learning-powered business intelligence service to create interactive dashboards

#### AWS Glue

- Managed extract, transform, and load (ETL) service

- Glue Job Bookmarks: prevent re-processing old data

- Glue Elastic Views: Combine and replicate data across multiple data stores using SQL No custom code, Glue monitors for changes in the source data, serverless Leverages a “virtual table” (materialized view)

- Glue DataBrew: clean and normalize data using pre-built transformation

- Glue Studio: new GUI to create, run and monitor ETL jobs in Glue

- Glue Streaming ETL (built on Apache Spark Structured Streaming): compatible with Kinesis Data Streaming, Kafka, MSK (managed Kafka)


### AWS Lake Formation

- Data lake = central place to have all your data for analytics purposes
























==

