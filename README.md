# etl-pipeline-spotify-aws
# Spotify Data Engineering Pipeline on AWS

This project is a comprehensive data engineering endeavor designed to create a seamless data pipeline using Spotify data. It encompasses the following key components:

## Integration with Spotify API and Data Extraction
The project begins by establishing a connection with the Spotify API to extract data efficiently.

## AWS Lambda for Data Extraction
We leverage AWS Lambda to deploy code that facilitates data extraction from Spotify's API. This ensures scalability and efficiency in the extraction process.

## Automatic Extraction Trigger
To streamline data extraction, an automated trigger is implemented. This trigger ensures that data extraction occurs at predefined intervals without manual intervention.

## Transformation Function Development
Data extracted from Spotify's API often requires processing for analysis. In this project, we've developed a transformation function to prepare the data for subsequent stages.

## Automated Transformation Trigger
To keep the data processing up-to-date, an automated trigger is set up for the transformation function. It initiates data processing whenever new data is extracted.

## Proper S3 File Storage
The transformed data is securely stored on Amazon S3, following best practices for data organization and security.

## Analytics Table Creation
To facilitate data analysis, analytics tables are constructed using AWS Glue and Athena. These tables simplify querying and provide valuable insights from the data.


