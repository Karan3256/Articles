# The Data Lakehouse

###### by Karan Rakheja


<img src="images\lakehouse.jpg" alt="drawing" height="200"/>

###### "Data Engineers are the Bridge" by Jennifer Shalamanov
---
<p style="text-align: left; width: 100%;" >
Data Lakehuse is a new data management paradigm that leverages the capabilites of data lakes and data warehouses. This adjuncture will allow **BI Users** and **Data Scientists** to work on the same sources. The data lakehouse is benefitted with schema enforcement and governance from data warehouse and with diverse data types from data lakes.

* Data Warehouse: It is a storage repository that holds structured data and helps to connect and perform analysis on that data. Raw data passess through many data transformation pipelines that integrates and cleans the data before performing any analysis on it. Data is usually housed in files and folder in data warehouses.

* Data Lake: It is also a storage repository that can accomodate all kinds of data, like a lake which can accommodate multiple tributaries. Data lakes can store structured, semi- structured and un-structured data like images, documents, logs, etc. It is big, fast and cost-effective and thus increase analytic performance. A unique identifier, with some metadata information, is tagged with each data element thus removing the need of schema approach.


Multiple data warehouses and a big data lake are still used parallelly in many organizations resulting in data duplication between the two with data transformation and management pipelines overhead, initiating towards the growth of data lakehouse.
  
Now that we have learned much about data warehouse and data lakes and their usage resulting to the exploration data lakehouse to reduce these overheads. Let's explore more about data lakehouse. 

### Features of Data Lakehouse

* **Transaction support**: It can handle multiple data transaction pipelines. Data integrity is being maintained as it supports concurrent read and write transactions, mainly through SQL.
* **Schema enforcement and Governance**: The Lakehouse has a way to support schema enforcement through warehouses, because it applies a schema to all the data. The structure of lakehouse can standardize a large amount of data, while conserving data integrity and applying robust data governance mechanisms.
* **BI and analytics support**: As data is now stored on a same single repository, lakehouse improves quality of BI by applying BI tools directly on the source data while speeding up the analytics and reducing the latency and cost to maintain different copies of same data on both data warehouses and data lakes. It also improves recency of data as it is more voluminous and more recently updated, hence improving BI and analytics support.
* **Extended data types**: The lakehouse structure supports diverse data types including structured, semi-structured and un-structured kind of data like files, video, audio, and system logs. Due to this wide range of data storage capability, lakehouses are used to store, refine and analyze data types used in many new data applications.
* **End-to-end streaming**: Real time reporting is the need of almost all organizations which is facilitated through lakehouse streaming analytics which eliminates the need for a separate real time data serving application.
* **Processing/storage decoupling**: The data lake structure incurs low-cost for hardware because it uses separate clusters both for storage and compute thus improving performance efficiency. This approach offers very cheap decentralized storage, scale to many more concurrent storage and aims to maximize available resources due to storage and execution of queries on data on a different clusters.
* **Openness**: The lakehouse provides a public API to access the data store in open and standard data format **Parquet**. This storage format can directly and efficiently be accessed via Python or R libraries.

</p>

# Why to Use the Data Lakehouse?

<p style="text-align: left;">
Though data warehouses and data lakes are widely used and popular among data engineers, there shortcomings led to the development of data lakehouses. Data lakehouses resolved many issue exsisting with these two major data repositories such as:

* **Data Redundancy**: Using both a data lake and many data warehouses in an organization creates data duplication because data is stored on both of them which creates data  inefficiency and inconsistency. Data lakehouse resolves this problem by storing data on a single data lakehouse for analysis and hence reducing data movement between warehouses and lakes.
* **Data Storage**: The data lakehouse provides cost-effective data storage options by combining the techniques being used by warehouses and lakes. Warehouse integrate disparate sources while lakes store data on cheap hardware provided by big data file systems.
* **Data governance**: Data lakeouse eliminates the oberhead of managing data governance on multiple data repositories. Sensitive data can be easily managed and goverened through single data governance instead of using multiple warehouses and lakes which will require proper control and encryption on data transference.
* **Data Access**: Data lakehouse provide direct access of data for BI developers who can then apply BI tools such as Tableau, Power BI, etc. This direct connection reduces the time taken for visualization of raw data.
* **ETL Jobs Removal**: With the usage of data lakehouses within an organization, the simple etl jobs, which were used in data warehousing to query or perform analysis on the data passed on from a data lake, have been eliminated by connecting the query engine directly to data lake.


</p>


# Architecture

<img src="images\Data-Lakehouse-Architecture.png" alt="drawing"/>

# Databricks Data Lakehouse vs Snowlake Data Lakehouse

<p style="text-align: left;">


</p>

# Conclusion

<p style="text-align: left;">


</p>

# References

* https://www.guru99.com/data-warehousing.html
* https://www.guru99.com/data-lake-architecture.html
* https://www.xplenty.com/glossary/what-is-a-data-lakehouse
* https://www.snowflake.com/guides/what-data-lakehouse
