# Covid-19 Data Analysis | End-To-End Data Engineering Project

## Description:
In this project, I undertook a comprehensive data engineering journey focused on COVID-19 data, leveraging AWS services to create a powerful data infrastructure. My goal was to make the COVID-19 data accessible, understandable, and valuable for analysis.

## Key Steps:
1. **Data Collection and Storage:** I started by downloading COVID-19 datasets from Registry of Open Data on AWS and uploaded them to an Amazon S3 bucket, establishing a Data Lake. Here is the data set url: https://registry.opendata.aws/aws-covid19-lake/
2. **Data Cataloging:** I ran AWS Crawlers on the S3 data to extract schema and information, making the data easily discoverable and queryable.
3. **Data Exploration:** Using AWS Athena's query editor, I conducted ad-hoc SQL queries to explore and understand the data's insights.
4. **Data Modeling:** I constructed an Entity-Relationship (ER) Data Model by gathering valuable data insights obtained from Athena.
5. **Dimensional Modeling:** I designed a Dimensional Model with a star schema. It includes the COVID-19 Fact Table, Date Dimension Table, Region Dimension Table, and Hospital Dimension Table for structured data representation.
6. **ETL Processing:** Python was utilized to perform Extract-Load-Transform (ETL) operations on the data, generating various dataframes that are the foundation for our Dimensional Model tables.
7. **Data Storage:** The transformed data was saved in the Amazon S3 bucket for accessibility.
8. **Data Warehousing:** I established a Dimensional Schema within Snowflake, a powerful data warehouse.
9. **Data Integration:** The Dimensional Model was loaded into Snowflake, offering a robust and scalable data warehousing solution.
10. **Data Visualization:** To analyze data effectively, I connected Power BI to Snowflake, creating insightful data visualizations.


## Architecture:
![Architecture diagram](https://github.com/abakash08/covid-19-data-analysis-end-to-end-project/blob/main/Covid-19%20DE%20Architecture.png)

## Tools and Their Use:

- **Amazon S3:** Used for data storage, providing scalability and flexibility.
- **Crawler:** Employed to automate schema extraction and data cataloging from S3, making data easily queryable.
- **Amazon Athena:** Enabled ad-hoc SQL querying for data exploration and analysis.
- **AWS Glue:** Utilized for ETL processing to transform and structure data.
- **Snowflake:** Served as the data warehouse to store the Dimensional Model, providing robust data storage and management.
- **Power BI:** Connected to Snowflake for data visualization and generating actionable insights.

This project demonstrates the effective use of cloud services and data engineering techniques to harness the potential of COVID-19 data, from storage to meaningful insights.

