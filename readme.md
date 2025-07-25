# Common Cloud Services for DA Roles

### Which cloud to focus upon?
---

*Unofficial - Ant's opinion only, blah, blah, blah!!!*

|Provider|Benefit|
|---|---|
|AWS|Biggest (first mover advantage), widest range of services.|
|GCP|The developers cloud. Made by developers, for developers.|
|Azure|Leverages Microsoft's monopoly on enterprise software for greater compatibility with on-premise platforms|

The following is a selection of tools on each of the platforms which in the absense of cloud certification, an employer may expect you to be learning about for entry-level DA roles.

#### Overview
Generally speaking, if a data pipeline goes:

`Data Lake` >  `Data Warehouse` > `Database`

...and that roughly maps to:

`Unstructured` >  `Semi-structured` > `Structured`

Then each cloud provider can offer services for each stage of the lifecycle, and any processing and analysis that happens inbetween. 

The decision about which one to use may come down to whichever offers the specific services and compatibility with workloads, but other things to consider include 
- Which cloud provider has been adopted elsewhere in the organisation.
- Cost effectiveness, and optimisations. For example serverless services allowing you to pay per execution.
- Existing institutional knowledge.
- Various others...

### DA Relevant Services
---
#### AWS (Amazon Web Services)

|Service|Purpose|Use Case|
|---|---|---|
|Amazon S3|Scalable object storage|Store raw or processed datasets|
|Amazon RDS|Managed relational databases|Host SQL databases for analytics|
|Amazon QuickSight|Business intelligence and visualization|Create dashboards and reports|
|Amazon Redshift|Data warehousing|Run complex queries on large datasets|
|AWS Glue|ETL (Extract, Transform, Load)|Prepare and clean data for analysis|

Also useful: Amazon Kinesis for real-time data streaming and processing. Amazon EMR (Elastic Map Reduce) for big data processing with Spark/Hadoop (Open Source, Apache platform - one is optimised for clustered deployments).

**AWS certification** - [Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/)

---
#### GCP (Google Cloud Platform)
|Service|Purpose|Use Case|
|---|---|---|
|BigQuery|Serverless data warehouse|Analyze large datasets using SQL|
|Cloud Storage|Object storage|Store structured/unstructured data|
|Looker Studio|Data visualization|Build interactive dashboards|
|Dataflow|Stream and batch processing|Real-time or scheduled data pipelines|
|Dataprep|Data cleaning and transformation|Prepare data without writing code|

GCP also offers a beginner-friendly Data Analytics Certificate to help new analysts build skills with hands-on projects.

**GCP certification** - [Cloud Digital Leader](https://cloud.google.com/learn/certification/cloud-digital-leader)

---
#### Microsoft Azure
|Service|Purpose|Use Case|
|---|---|---|
|Azure Synapse Analytics|Unified analytics platform|Combine big data and data warehousing|
|Power BI|Business intelligence|	Visualize and share insights|
|Azure Data Factory|Data integration and ETL|Move and transform data across sources|
|Azure SQL Database|Managed relational database|Store and query structured data|
|Azure Analysis Services|Semantic data modeling|Build enterprise-grade data models|

Azure also supports Jupyter Notebooks and HDInsight for more technical data exploration and processing.

**Azure certification** - [Azure Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/?practice-assessment-type=certification)