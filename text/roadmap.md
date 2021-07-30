> Text version for visually impaired users

# Data Engineer in 2021

* CS fundamentals
	* Basic terminal usage [general recommendation]
	* Data structures & algorithms [general recommendation]
	* APIs [general recommendation]
	* REST [general recommendation]
	* Structured vs unstructured data [general recommendation]
	* Serialisation
	* Linux [general recommendation]
		* CLI
		* Vim
		* Shell scripting
		* Cronjobs
	* How does the computer work? [general recommendation]
	* How does the Internet work? [general recommendation]
	* Git — Version control [general recommendation]
	* Math & statistics basics [general recommendation]

*Note: Git is used for tracking changes in source code and coordinating work among programmers. In your day to day work you will use Git server as a service like GitHub, GitLab or Bitbucket.*

* Learn a programming language
	* Python [personal recommendation]
	* Java [general recommendation]
	* Scala
	* Go

*Note: Learn how to write clean, extensibile code. Spend some time understanding programming paradigms (functional vs. OOP) and best practices (design patterns, YAGNI, stateful vs stateless applications). Get familiar with an IDE or code editor like VSCode.*

* Testing
	* Unit testing [general recommendation]
	* Integration testing [general recommendation]
	* Functional testing [general recommendation]

* Database fundamentals
	* SQL [general recommendation]
	* Normalisation [general recommendation]
	* ACID transactions [general recommendation]
	* CAP theorem [general recommendation]
	* OLTP vs OLAP [general recommendation]
	* Horizontal vs vertical scaling [general recommendation]
	* Dimensional modeling [general recommendation]

* Relational databases
	* MySQL 
	* PostgreSQL 
	* MariaDB
	* Amazon Aurora (MySQL & PostgreSQL) [general recommendation]

* Non-relational databases
	* Document databases
		* MongoDB [general recommendation]
		* Elasticsearch [general recommendation]
		* Apache CouchDB
		* Azure CormosDB
	* Wide column databases
		* Apache Cassandra [general recommendation]
		* Apache HBase 
		* Google Cloud Bigtable [personal recommendation]
	* Graph databases
		* Neo4j
		* Amazon Neptune
		* TigerGraph [personal recommendation]
	* Key-value stores
		* Redis [personal recommendation]
		* Memcached
		* Amazon DynamoDB [general recommendation]

*Note: Understand the difference between Document, Wide column, Graph and Key-value NoSQL databases. We recommend mastering one database from each category.*

* Data warehouses (learn the differences between the following)
	* Snowflake [general recommendation]
	* Amazon Redshift [general recommendation]
	* Google BigQuery [personal recommendation]
	* Azure Synapse [general recommendation]

* Data Lake / Object storage
	* AWS S3 (the next 3 are basically the same) [general recommendation]
	* Azure Blob Storage
	* Azure Data Lake Storage Gen 2
	* Google Cloud Storage
	* HDFS [general recommendation]

* Data Catalog Tools
	* Technical metadata
		* Hive metastore [general recommendation]
		* AWS Glue Catalog & Lakeformation 
	* Business Metadata
		* Alation 
		* Collibra
		* Apache Amundsen [general recommendation]

*Note: Learn common metadata techniques like SQL Query Log Mining, data lineage capture, data dictionaries, data quality metadata, etc*

* Data Lake storage SQL Tools
	* Presto / Amazon Athena [general recommendation]
	* Spark SQL

* Data Lake ACID Transaction Tools
	* Databricks Delta Lake
	* Apache HUDI
	* AWS Lakeformation Governed Tables

* Data Ingestion / ETL
	* Business Focused GUI
		* Fivetran [general recommendation]
		* Stitch
	* Technical GUI
		* Apache NiFi [general recommendation] 	
		* StreamSets Data Collector
		* AWS Glue
		* Azure Data Factory
	* Database Change Data Capture [general recommendation]
		* Qlik Replicate
		* AWS Database Migration Service
		* Azure Data Factory
		* Kafka Debezium
	* Stream Ingestion
		* AWS Kinesis Firehose
		* Azure Event Hubs Capture
		* Kafka Connect 

*Note: Understand data ingestion fundamentals like Schema Evolution, Transaction Log Scanning for CDC, Data Backfills.*


* Cluster computing fundamentals
	* Apache Spark [general recommendation]
	* Apache Hadoop 
	* MapReduce
	* Lambda & Kappa architecture basics
	* Managed Spark 
		* Databricks [general recommendation]
		* Amazon EMR
		* Google Dataproc
		* Azure Data Lake

*Note: Most modern data processing frameworks are based on Apache Spark, which is in turn based on Hadoop & MapReduce to some extent. Understanding these concepts can help you learn modern data processing frameworks much quicker.*

* Data processing
	* Batch
		* Apache Pig
		* Apache Arrow
		* data build tool for Data Warehouses [personal recommendation]
	* Hybrid
		* Apache Spark / Lambda Architecture [general recommendation]
		* Apache Beam 
		* Apache Flink / Kappa Architecture [general recommendation]
		* Apache NiFi
	* Streaming
		* Apache Kafka / Confluent Ecosystem [personal recommendation]
		* Apache Pulsar [personal recommendation]
		* Apache Storm 
		* Amazon Kinesis
		* Azure Event Hubs

*Note: Hybrid frameworks are able to process both batch and streaming data. Batch data processing is often done by analytical data warehouse applications. See Data warehouses section for more.*

* Messaging (mainly learn the difference between messaging & streaming data)
	* RabbitMQ [general recommendation]
	* Apache ActiveMQ
	* Amazon SNS & SQS
	* Google PubSub
	* Azure Service Bus

* Workflow scheduling
	* Apache Airflow [personal recommendation]
		* Google Composer
		* AWS Managed Airflow
	* AWS Step Functions
	* Azure Data Factory
	* Dagster
	* Apache Oozie
	* Luigi

* Data Catalogs
	* Metadata Management
	* Data Quality Metadata
	* Data Lineage 

*Note: Cloud Composer is a managed Apache Airflow service on Google Cloud Platform.*

* Monitoring and observability for data pipelines
	* Prometheus [general recommendation]
	* Datadog [general recommendation]
	* Sentry [general recommendation]
	* Monte Carlo
	* Datafold
	* Soda Data
	* StatsD

* Networking
	* Protocols [general recommendation]
		* HTTP / HTTPS
		* TCP
		* SSH
		* IP
		* DNS
	* Firewalls
	* VPN 
	* VPC [general recommendation]

* Infrastructure as Code
	* Containers
		* Docker [personal recommendation]
	* Container orchestration
		* Kubernetes [general recommendation]
			* Google Kubernetes Engine (GKE)
			* AWS Elastic Kubernetes Service
			* Azure Kubernetes Service 
		* Kubernetes Helm [general recommendation]
	* Infrastructure provisioning
		* Terraform [personal recommendation]
		* AWS CDK [general recommendation]
		* AWS CloudFormation
		* Azure Resource Manager Templates

* CI/CD
	* GitHub Actions [general recommendation]
	* Jenkins

* Identity and access management
	* Active Directory [general recommendation]
		* Azure Active Directory
		* Active Directory Federation Services
	* SAML Protocol
	* LDAP Protocol
	* OAuth 2.0 Protocol

* Data security & privacy
	* Role based access management
	* Attribute based access management
	* Legal compliance (GDPR / CCPA) requirements [general recommendation]
	* Encryption [general recommendation]
	* Key management [general recommendation]
		* Hashicorp Vault
		* Azure Key Vault
		* AWS Secrets Manager
	* Data governance & integrity
