# Youtube-Data-Analysis-and-Cloud-Integration-
This project focuses on efficiently managing, processing, and analyzing structured and semi-structured YouTube video data, with an emphasis on video categories and trending metrics.
Overview
This project focuses on securely managing, optimizing, and analyzing structured and semi-structured data from YouTube videos based on their categories and trending metrics.

## Project Goals
Data Ingestion: Develop a mechanism to gather data from various sources.<br>
ETL System: Transform raw data into a structured format for analysis.<br>
Data Lake: Establish a centralized repository to store data sourced from multiple channels.<br>
Scalability: Ensure that the system can scale as data volume increases.<br>
Cloud Integration: Leverage cloud computing resources to handle large datasets, specifically using AWS.<br>
Reporting: Create a dashboard to provide insights based on previously defined questions.<br>
## Services Utilized
Amazon S3: An object storage service that ensures scalability, data availability, security, and performance.<br>
AWS IAM: Identity and access management service for secure access to AWS resources.<br>
Amazon QuickSight: A scalable, serverless, and machine learning-powered business intelligence service designed for the cloud.<br>
AWS Glue: A serverless data integration service that simplifies the process of discovering, preparing, and combining data for analytics, machine learning, and application development.<br>
AWS Lambda: A computing service that enables code execution without the need for server management.<br>
AWS Athena: An interactive query service that allows direct querying of data stored in S3 without requiring data loading.<br>
## Dataset Utilized
This project employs a dataset from Kaggle that includes statistics (in CSV format) on daily trending YouTube videos over several months. It features up to 200 popular videos published each day across different regions. Each region has its own file containing details such as video titles, channel titles, publication dates, tags, views, likes, dislikes, descriptions, and comment counts. Additionally, a category_id field, which varies by region, is included in the linked JSON file.

You can access the dataset [here](https://www.kaggle.com/datasets/datasnaek/youtube-new).
