# Big Data

## What is Big Data?

"Big data is a term for massive data sets having a large, more varied, and complex structure with the difficulties of storing, analyzing, and visualizing for further processes or results *(Sagiroglu & Sinanc, 2013)*". 

## Examples or Sources of Big Data

We come across big data in a variety of forms and almost everywhere. According to the McKinsey Global Institute, big data has five potential sources or topics, *(Manyika, et al., 2011)* they are -  
- **Healthcare**: This sector has multiple and varied stakeholders from the pharmaceuticals and medical products industries to the consumer, i.e., the patients. The massive inflow of data from all the stakeholders is vital in the health industry business analysis *(Manyika, et al., 2011)*.
- **Public sector**: The availability of massive public data gives governments an advantage if used appropriately, to improve performance and transparency *(Manyika, et al., 2011)*. 
- **Retail**: In this sector, big data can be used to segment customers and manage supply chains in the most efficient manner *(Manyika, et al., 2011)*.
- **Manufacturing**: Like the retail sector, the manufacturing sector utilizes big data in the analysis of the points in the value chain to decide on the places where the market, research, and development have to be altered or improved *(Manyika, et al., 2011)*.
- **Personal location data**: Location data cuts across all industries and sectors. Smartphones add to the generation of this data which is available for organizations to analyze their customer behaviors *(Manyika, et al., 2011)*.

## Types of Big Data

There are three types of big data depending on the structure of the incoming data *(M. Narang, 2023)*. They are - 
- Structured Data: The data that can be processed, accessed, and stored in a fixed format. A few examples of structured data are address, age, bank account/card numbers, and cell numbers *(M. Narang, 2023)*.
- Unstructured Data: The data that constitutes images, videos, audio, and log files are classified into this category. They do not have a formal structure and are difficult to analyze *(M. Narang, 2023)*.
- Semi-structured Data: This is a mixture of structured and unstructured data types. Some semi-structured data are XML and JSON.

Besides, big data is often classified based on how the data is generated or its origin as - machine (operational logging), social media or event-triggered, and geospatial(locational) *(M. Narang, 2023)*.

Moreover, big data can be divided into different categories based on the source/usage *(P. Alexander, 2023)* -
- **Batch Data**: Those data with tabular information (CSV, JSON, Avro, parquet) where the data is collected at a defined threshold or intervals *(P. Alexander, 2023)*.
- **Transactions Data**: Those data that are stored in Databases like RDBMS or NoSQL *(P. Alexander, 2023)*.
- **Stream Data**: The data is used in real-time communication and exchange of messages *(P. Alexander, 2023)*.
- **Flat file**: Non-tabular or pdfs that have to be processed for analysis to extract information *(P. Alexander, 2023)*.

## 6 V's of Big Data

The 6 V's or characteristics of big data define it. They are - 
- **Volume**: The size of the big data, as the name denotes, should be huge, i.e., usually ranging from petabytes or exabytes and cannot be handled by a single machine *(M. Narang, 2023)*. 
- **Velocity**: The data is accumulated at a high rate, i.e., it is not fixed or stagnant data. The data is analyzed in real-time and some sources will have a high data generation rate *(M. Narang, 2023)*.
- **Variety**: Another characteristic of big data is its different data types, its uniqueness in organizing, and the readiness to be processed. With a high data accumulation rate or velocity, the data models have to handle a number of varieties of data efficiently *(M. Narang, 2023)*.
- **Variability**: The data collected and stored should be available for processing and analyzing different purposes *(M. Narang, 2023)*. 
- **Veracity**: The data acquired should be reliable for analyzing and providing a recommendation for an action. The quality of the data should be compromised such that it affects the prediction or business analysis *(M. Narang, 2023)*.
- **Value**: The data is considered valuable when it could bring valuable insights. The proper data types, variables, and intervals of acquisition make the data better *(M. Narang, 2023)*.

## Big Data Pipeline

An outline of the major steps involved in the big data analysis pipeline is given below. 

![Big Data Pipeline](data:image/png;base64,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)
# References

S. Sagiroglu and D. Sinanc, *"Big data: A review"*, 2013 International Conference on Collaboration Technologies and Systems (CTS), San Diego, CA, USA, 2013, pp. 42-47, doi: 10.1109/CTS.2013.6567202.

J. Manyika, M. Chui, B. Brown, J. Bughin, R. Dobbs, C. Roxburgh and A. H. Byers, *"Big data: The next frontier for innovation, competition, and productivity"*, McKinsey Global Institute, 2011, 
[McKinsey Global Institute](http://www.mckinsey.com/~/media/McKinsey/dotcom/Insights%20and%20pubs/MGI/Research/Technology%20and%20Innovation/Big%20Data/MGI-big-data-full-report.ashx/)

M. Narang, *"What is Big Data: Types, Characteristics, and Benefits"*, KnnowledgeHut, 04th Sept 2023, 
[KnowledgeHut](https://www.knowledgehut.com/blog/big-data/types-of-big-data#what-is-big-data?%C2%A0)

P. Alexander, *"What Data Pipeline Architecture Should I Use?"*, Google Cloud Blog, 01st February 2023,
[Google Cloud Blog](https://cloud.google.com/blog/topics/developers-practitioners/what-data-pipeline-architecture-should-i-use/)
