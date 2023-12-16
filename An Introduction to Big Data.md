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
- **Veracity**: The data acquired should be reliable for analyzing and providing a recommendation for an action. The quality of the data should NOT be compromised such that it affects the prediction or business analysis *(M. Narang, 2023)*.
- **Value**: The data is considered valuable when it could bring valuable insights. The proper data types, variables, and intervals of acquisition make the data better *(M. Narang, 2023)*.

## Big Data Pipeline

An outline of the major steps involved in the big data analysis pipeline is given below. 

![Big Data Pipeline]([Big_Data_Pipeline.png)

- **Phase 1: Data Acquisition and Recording** - The preliminary step in any data pipeline is the generation of data from different sources. However, the entire data collected will not be useful most of the time and therefore, proper cleaning and compressions have to be implemented. Together with data collection, it is equally important to generate the right metadata to describe the data and its history *(D. Agrawal, et al., 2012)*.
- **Phase 2: Information Extraction and Cleaning** - Data is raw format and does not give any insights unless it is formatted in a structured manner like tables or databases. Along with this, the data has to be cleaned by filling in missing or null values and removing outliers to maintain consistency throughout the analysis *(D. Agrawal, et al., 2012)*.
- **Phase 3: Data Integration, Aggregation, and Representation** - Often, the data comes from different sources and different formats. In order to run an analysis on them, all the sources have to be integrated. It also helps reduce redundancies and inconsistencies. Once the data is integrated, it is important to visualize them in different possible ways - bar charts, histograms, boxplots, pie charts, and more *(D. Agrawal, et al., 2012)*.
- **Phase 4: Query Processing, Data Modeling, and Analysis** - Once the data is all set for analysis, we engage it with multiple queries to extract subsets and implement data models to organize the elements of the data and run primary analysis *(D. Agrawal, et al., 2012)*.
- **Phase 5: Interpretation** - This is the crucial step in any pipeline. The understanding and verification of results obtained from the above steps ensures the quality of the decision made from those insights *(D. Agrawal, et al., 2012)*.

## Challenges in Big Data Analysis

- **Heterogeneity and Incompleteness**: Machine learning algorithms require homogenous data structures to deal with. Unlike a direct human approach, the machines cannot segregate the nuances that arise in data and cope with them. Similarly, analyzing incomplete data, i.e., consisting of too many NULL values, could result in unexpected interpretations *(D. Agrawal, et al., 2012)*.
- **Scale**: The Volume characteristic of big data is ever challenging. It requires high efficiency and storage techniques that have to be upgraded very often to cope with the data demands *(D. Agrawal, et al., 2012)*.
- **Timeliness**: In real-time analysis, timely presentation of decisions and patterns is necessary. This requires a faster understanding of elements and using them for the analysis. Searching and querying should be faster to enable an efficient real-time analysis *(D. Agrawal, et al., 2012)*.
- **Privacy**: This concern has always been there with data. When data is the powerhouse of immense information and knowledge, it sacrifices the privacy of individuals. The balance between data and privacy remains unidentified *(D. Agrawal, et al., 2012)*.
- **Human Collaboration**: Like normal data analysis, big data analysis also requires human expertise to interpret the outcomes completely. Proper explanations for distinct patterns and abnormalities are the essence of data analysis and interpretation *(D. Agrawal, et al., 2012)*.


# References

S. Sagiroglu and D. Sinanc, *"Big data: A review"*, 2013 International Conference on Collaboration Technologies and Systems (CTS), San Diego, CA, USA, 2013, pp. 42-47, doi: 10.1109/CTS.2013.6567202.

J. Manyika, M. Chui, B. Brown, J. Bughin, R. Dobbs, C. Roxburgh and A. H. Byers, *"Big data: The next frontier for innovation, competition, and productivity"*, McKinsey Global Institute, 2011, 
[McKinsey Global Institute](http://www.mckinsey.com/~/media/McKinsey/dotcom/Insights%20and%20pubs/MGI/Research/Technology%20and%20Innovation/Big%20Data/MGI-big-data-full-report.ashx/)

M. Narang, *"What is Big Data: Types, Characteristics, and Benefits"*, KnnowledgeHut, 04th Sept 2023, 
[KnowledgeHut](https://www.knowledgehut.com/blog/big-data/types-of-big-data#what-is-big-data?%C2%A0)

P. Alexander, *"What Data Pipeline Architecture Should I Use?"*, Google Cloud Blog, 01st February 2023,
[Google Cloud Blog](https://cloud.google.com/blog/topics/developers-practitioners/what-data-pipeline-architecture-should-i-use/)

Agrawal D., Bernstein P., Bertino E., Davidson S., Dayal U., Franklin M., . . . . Widom J., *"Challenges and Opportunities with Big Data"*: A white paper prepared for the Computing Community Consortium committee of the Computing Research Association, 2012
[White Paper](http://cra.org/ccc/resources/ccc-led-whitepapers/)
