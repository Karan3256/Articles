# The Data Lakehouse

###### by Karan Rakheja


<img src="images\Data-Engineer_Graphic.png" alt="drawing"/>

###### "Data Engineers are the Bridge" by Jennifer Shalamanov
---
<p style="text-align: left; width: 100%;" >
Data Lakehuse is a new data management paradigm that leverages the capabilites of data lakes and data warehouses. This adjuncture will allow **BI Users** and **Data Scientists** to work on the same sources. The data lakehouse is benefitted with schema enforcement and governance from data warehouse and with diverse data types from data lakes.

* Data Warehouse: It is a storage repository that holds structured data and helps to connect and perform analysis on that data. Raw data passess through many data transformation pipelines that integrates and cleans the data before performing any analysis on it. Data is usually housed in files and folder in data warehouses.

* Data Lake: It is also a storage repository that can accomodate all kinds of data, like a lake which can accommodate multiple tributaries. Data lakes can store structured, semi- structured and un-structured data like images, documents, logs, etc. It is big, fast and cost-effective and thus increase analytic performance. A unique identifier, with some metadata information, is tagged with each data element thus removing the need of schema approach.
</p>

# Why to Use the Data Lakehouse?

<p style="text-align: left;">
Multiple data warehouses and a big data lake are still used parallelly in many organizations resulting in data duplication between the two with data transformation and management pipelines overhead, initiating towards the growth of data lakehouse.
  
Now that we have learned much about data warehouse and data lakes and their usage resulting to the exploration data lakehouse to reduce these overheads. Let's explore more about data lakehouse. 

### Features of Data Lakehouse

* **Transaction support**: Lakehouses can handle multiple data pipelines. This means that they support concurrent read and write transactions without compromising data integrity.
* **Schemas**: Warehouses apply a schema to all data; lakes do not. The lakehouse structure can reason about the application of schemas and standardize a greater volume of data.
* **BI and analytics support**: Both teams work with a single data repository. The information contained in the lakehouse has passed through a cleansing and integration process, which speeds up analytics. It is also more voluminous and more recently updated than a warehouse, which improves the quality of BI.
* **Extended data types**:Warehouses can only store structured data. The lakehouse structure provides access to a much broad range of data, including files, video, audio, and system logs.
* **End-to-end streaming**: Lakehouses support streaming analytics, which facilitates real-time reporting. This is increasingly a must-have for many enterprises.
* **Processing/storage decoupling**: The data lake structure uses clusters, which run on low-cost hardware. This approach offers very cheap decentralized storage. To further improve efficiency, the lakehouse model decouples processing from storage. This means that the lakehouse might store data in one cluster, but execute queries on a different cluster. It will always aim to maximize available resources.
* **Openness**: The Databricks version of the lakehouse uses the open standard Parquet. This storage format has a public API that developers can easily access via Python or R.


Concurrent reading and writing of data
Schema support with mechanisms for data governance 
Direct access to source data 
Separation of storage and compute resources 
Standardized storage formats 
Support for structured and semi-structured data types, including IoT data 
End-to-end streaming 



* **Data Architect**
<img src="images\DA.png" alt="drawing" width="200" style="float: right"/>

A Data Architect provides the blueprint for Data Management Systems. He's responsible for understanding the business objective and existing data infrastructure, and then work out a plan for integrating, centralizing, and maintaining all the data, shaping the data architecture or pipelines as per the requirements and standards.
<br>
<br>

* **Data Engineer**
<img src="images\DE.png" alt="drawing" width="200" style="float: right"/>

A Data Engineer develop, construct, test, and maintain architectures. As a hardcore engineer, they work along with a Data Architect to develop such high-performance data pipelines and work on Data reliability, efficiency, and quality. In short, He deals with gathering the data and process them.
<br>
<br>

* **Data Scientist**
<img src="images\DS.png" alt="drawing" width="200" style="float: right"/>

A Data Scientist uses the pipelines or architectures designed by Data Engineer and tries to extract valuable insights from the data. He's more mathematically inclined, usually trained in areas like Machine Learning, Statistics, and some hardcore domains like 
Text Analytics(NLP), Computer Vision(CV) etc.

</p>

# What are the skills needed for these roles?

<p style="text-align: left;">

<img src="images\chart.png" alt="drawing"/>

A **Data Architect** plans a strategy on how to solve a business problem. He may or may not have a technical background but he possesses an immense amount of In-depth knowledge of Database architecture. He's also good with Spreadsheets, BI tools, and Extraction Transformation and Load (ETL)

Some of the other important skills he possesses are :

* Business Skill
* Programming Skills
* Data Modelling
* Applied Math’s and Statistics
* Design Skills
* Excellent Communication Skill
* Databases and Cloud Architecture
* Creative and Analytical Problem Solving
* Ability to use a variety of Design/Visualization tools

![](images\da-salary.png)

##### [Click here to know more](https://datacatchup.com/top-10-skills-for-data-architects/) 

A **Data Engineer** develops large and manages large databases and create data pipelines.  So, He generally comes from a technical background and usually has a deep knowledge and expertise in one or more different database software like SQL, NoSQL.

Some of the other important skills he possesses are :

* Data APIs
* Database Systems
* Data warehousing solutions
* Data Modeling and ETL tools
* Knowledge of algorithms and data structures
* Python, Java, and Scala programming language
* Understanding the basics of distributed systems

![](images\de-salary.png)

##### [Click here to know more](https://www.springboard.com/library/data-engineering/skills/) 

A **Data Scientist** extracts useful insights from data. He's an excellent StoryTeller and can use various data visualization techniques for its good. Well versed in Maths and Statistics, He knows the concepts of predictive modeling and can find out a gold nugget from the sack of Data. 

Some of the other important skills he possesses are :

* Big Data
* Data Munging
* Analytic Mind
* Data Ingestion
* Data Visualization
* Programming (Python or R)
* Data-Driven Problem Solving
* Tool Box(Hadoop, Spark, MS Excel)
* Machine Learning and Advanced Machine Learning (Deep Learning)

![](images\ds-slary.png)

##### [Click here to know more](https://www.edureka.co/blog/how-to-become-a-data-scientist/) 

</p>

# Closing Remark

<p style="text-align: left;">

Given above is an interpretation of what we have observed while researching at the time of writing this article. We tried to explore some well known but misunderstood Job Profiles in the field of Data.

Restating, Data is everywhere. Every company wants a guy who can bring the potential out of these Data that can change the world we are looking at right now. Pursue the field that you love and have a passion for, irrespective of its scope and salary, because, in the end, it'll bring immense pleasure and satisfaction. And if you're good with your field, then there will be demand and you'll grow. 
</p>

# References

* https://www.guru99.com/data-warehousing.html
* https://www.guru99.com/data-lake-architecture.html
* https://www.xplenty.com/glossary/what-is-a-data-lakehouse
* https://www.snowflake.com/guides/what-data-lakehouse
