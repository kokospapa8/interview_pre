# INfra
- AWS/GCP Service useful for ETL/data engineering

# Crawler
- 

# ETL
- used ETL tools/frameworks {Airflow, Luigi, Spark, Glue, etc} before?
    - (if used) advantages/disadvantages?
    - (if used) contributed to the community/project?
    - (if used) how to deploy? how to scale?  
- difference between ETL and ELT?
- what is atomicity in ETL and why is it important?
- what are the challenges of real-time streaming?

# Data
- what is star schema vs snowflake schema, why is it used?
- have experience with {hadoop, hive, pig, mahout, flume, etc}?
    - (if so) explain a use case?
    - (if so) explain some advantages/disadvantages?
- what separates "Big Data" from normal use cases?
    - *Large datasets, oftentimes unstructured, difficult to analyze with traditional processing tools.*
    - *Often some (much?) of the data is not useful, requires processing time/power to filter*
- What does "Data Engineering" mean to you?
    - *Looking for an answer that points towards some sort of ETL architecture and not {Data Science, Analysis, Machine Learning}*
- what is columnar storage type {redshift, parquet, etc} and why is it beneficial?
- Unstructured (and semi-structured) Data
    - What is it?
        - *Unstructured: follows no data model, rules, or semantics.*
        - *Semi-structured: No data model, but has some structure (tags, elements).*
    - Examples?
        - *Unstructured: pdfs, images, word documents*
        - *Semi-structured: emails, XML data*
    - Challenges?
        - *difficult to index, retrieve information, and store*
    - Have you worked with it before?
        - If so, what were some of the unique challenges when working with this type of data?
            - *Due to having little or no structure, it is difficult to extract and store into a data warehouse*
        - If not, what are some challenges you think you could face when working with this type of data?
- Difference between Datalake vs Datawarehouse
