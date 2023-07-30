---
layout: default
title: Data Engineer
description: Data Engineer Projects
---

## Data Engineer Projects

**Title: Import Export Data**
- **Technology Stack:** Python, pandas, wasabi, ThreadPoolExecutor, boto3
- **Problem Statement:** Develop an ETL (Extract, Transform, Load) pipeline to extract import-export data from the Trade Statistics portal of the Ministry of Commerce and Industry, Government of India. Create a large dataset spanning 16 years with monthly trade data at the country level, totaling over 100 GB. Utilize Python programming language and pandas library for data manipulation and preparation during the ETL process.
- **Steps Followed:**
  - Applied ETL techniques to extract data from the Trade Statistics portal.
  - Created a large import-export dataset from scratch, spanning 16 years and consisting of over 100 GB of monthly trade data at the country level.
  - Used Python programming language and pandas library for data manipulation, cleaning, and preparation.
  - Executed several steps during the ETL process, including data extraction, cleaning, transformation, and loading.
  - Implemented the ThreadPoolExecutor and multiprocessing library to parallelize data processing tasks, significantly reducing execution time.
  - The resulting dataset is valuable for analyzing trade patterns, identifying market opportunities, and monitoring trade policy changes.
  - Successful completion of the project demonstrates skills in data manipulation, ETL processes, and handling large volumes of data.

**Title: Real-Time Stock Market Data with Kafka**
- **Technology Stack:** Python, AWS, Apache Kafka, Glue, Athena, SQL
- **Problem Statement:** As a Data Engineer, develop a real-time stock market data system using Python and Apache Kafka. Implement data acquisition, processing, and analysis by leveraging AWS services like Glue and Athena. Enable real-time data computations and visualization using SQL queries and streaming frameworks. Ensure efficient and reliable data processing through performance optimization and error handling.
- **Project Overview:**
  - Developed a real-time stock market data system using Python and Apache Kafka.
  - Utilized AWS services like Glue and Athena for data acquisition, processing, and analysis.
  - Enabled real-time data computations and visualization through SQL queries and streaming frameworks.
  - Ensured efficient and reliable data processing by implementing performance optimization techniques and robust error handling.

**Title: MinDepExpScrapper**
- **Technology Stack:** Python, pandas, Camelot
- **Problem Statement:** Create a data extraction and preprocessing pipeline using Python and Camelot to extract expenditure data from Ministries and Departments in PDF format. Preprocess the data using pandas and store it in CSV format. Perform data transformation by reshaping and aggregating the data to create a comprehensive and structured database.
- **Steps Followed:**
  - Used Camelot and pandas to extract expenditure data from Ministries and Departments in PDF format.
  - Preprocessed the extracted data using pandas and stored it in CSV format.
  - Performed data transformation by using pandas' melt and pivot functions to reshape the data into long and wide formats.
  - Aggregated the data to create a comprehensive and structured database.


**Title: PMAY Data Scrapper**
- **Technology Stack:** Python, pandas, wasabi, ThreadPoolExecutor, selenium, boto3
- **Problem Statement:** As a Data Engineer for the PMAY Data Scrapper project, the goal was to automate the data acquisition and processing tasks for the Pradhan Mantri Awas Yojana (PMAY) using various Python libraries such as pandas, selenium, wasabi, ThreadPoolExecutor, and boto3. The responsibilities included automating the login process, extracting tokens, designing a logging mechanism, fetching data for specific cities, creating data frames, parallelizing data acquisition, converting data to CSV format, uploading files to S3, and following best practices for software development.
- **Steps Followed:**
  - Automated the login process and token extraction for accessing the PMAY data.
  - Designed and implemented a logging mechanism to track the data scraping process.
  - Developed data acquisition methods to fetch data for specific cities from the PMAY platform.
  - Utilized pandas library to create data frames for organizing and manipulating the acquired data.
  - Implemented ThreadPoolExecutor to parallelize data acquisition tasks, optimizing the data scraping process.
  - Converted the acquired data to CSV format for further analysis and storage.
  - Utilized boto3 library to upload the processed data files to the Wasabi storage platform.
  - Followed best practices for software development to ensure code quality and maintainability throughout the project.

[back](./)
