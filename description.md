# The Data Lakehouse

###### by Karan Rakheja


<img src="images\lakehouse.jpg" alt="drawing" height="600"/>

###### ["Lakehouse - The Evolution of the Data Warehouse?" by Stefan Koch](https://www.stefanko.ch/en/post/lakehouse/)
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

<img src="images\Data-Lakehouse-Architecture.jpg" alt="drawing"/>

###### ["Data Lakehouse, meet fast queries and visualization" by George Anadiotis](https://www.zdnet.com/article/data-lakehouse-meet-fast-queries-and-visualization-databricks-unveils-delta-engine-acquires-redash/)

The above architecture of Data Lakehouse is self explanatory. It can accommodate any sort kind of data whether it is structured, semi-structured and un-strucutred data. Data can be anything from audio, video, files, system logs, etc. The data storage on data lakehouse can be of any amount. Therefore, data lakehouse has overcome many shortcomings of data warehouse and data lake because it can store large amount of data to be processed and analyzed to gather insights from it.

# Databricks Data Lakehouse vs Snowflake Data Lakehouse

<p style="text-align: left;">
  
Databricks and Snowflake are both data repositories which are competing with themselves to provide one-stop solution to it's users in handling and processing all kinds of data for any use case. Thier objective is to to provide elasticity in terms of both cost and performance to it's customers so that they can concentrate more on generating business value. Though they both aims to provide same benefits to their users but there exists some differences between them. Let's discuss them below:

Snowflake | Databricks
--------- | ----------
It requires a user to structure the un-structured data before any analysis can be done on it. It automatically transforms the data into its internal structured data format | It does not require a user to convert data into any other format and lets a user to retain the data into it's original raw format.
It does not completely decouples the data storage and data processing layers. It means that Snowflake still owns both of these layers internally. | It does not own any of the data storage and data processing layers. It fully decouples them meaning that data can be stored anywhere, in any format, still allowing the processing on it to gather business intelligence.
It uses third party ecosystem for leveraging the processing capability on data, e.g. Apache Spark. The data transference may give rise to problems such as data integrity, data reliability and low latency issues. It is best suited for SQL based queries processing on data. | It also supports high performance SQL queries for data processing. It provides data reliability and high latency ensuring high data performance for analysis.

Thses differences made many things clear about these two data repositories for their popularity among data experts. Snowflake data lakehouse is generally preferred due to its simplicity while databricks data lakehouse is far more versatile and freedom of data storage and access from anywhere from processing increases it's demand among organisations.

</p>

# Conclusion

<p style="text-align: left;">
  
Datalakehuses are still in their early stage and will require more time to rule over the data storage market. As so many organisations are still dependent on data warehouses and data lakes for thier data storge requirements it is difficult for them to make transition of their bulk data over data lakehouses due of their initial phase of introduction to the data market. Although, the lakehouses provide all the functionality but it leads it to become more monolithic and in-flexible and harder to maintain. Data experts believe in using more modular applications to make their life easier and they also believe that the lakehouses will mature further to become more efficient and tangible to be accepted by data community wholeheartedly.

</p>

# References

* https://www.guru99.com/data-warehousing.html
* https://www.guru99.com/data-lake-architecture.html
* https://www.xplenty.com/glossary/what-is-a-data-lakehouse
* https://www.snowflake.com/guides/what-data-lakehouse
* https://www.datagrom.com/data-science-machine-learning-ai-blog/snowflake-vs-databricks
