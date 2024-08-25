# News_api_pipeline
# Features
**Extraction**: Retrieves news articles from the NewsAPI, filtering by keywords, and specific date ranges.
**Transformation**: Processes the news data into a tabular format using Pandas, keeping essential fields like title, timestamp, URL, content, source, and author. 
**Loading**: Saves the processed data locally in Parquet format and then uploads it to Amazon S3.
**Snowflake Integration**: Utilizes Snowflake external tables to read the data directly from S3.
**Orchestration**: The entire workflow is automated and scheduled via Apache Airflow.
