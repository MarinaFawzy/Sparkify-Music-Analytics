# Sparkify-Music-Analytics
Modeling User Listening Patterns for Insightful Analysis(Data Warehouse Modeling and Analytics)

 ## Project Overview:

Sparkify, a startup in the music streaming industry, aims to gain insights from their data regarding user activity and song metadata. They lack a streamlined method to query their data, which is currently stored in CSV files containing user activity logs and song metadata.

Using Informatica Cloud Data Integration, we will develop an Extract, Transform, Load (ETL) pipeline to facilitate the extraction, transformation, and loading of Sparkify's data. This pipeline will enable Sparkify to efficiently process and store their data in a data warehouse, empowering them to analyze user activity and song metadata effectively.

## Extract (E):
Extract data from Sparkify's CSV files containing user activity logs and song metadata.

## Transform (T):
Apply transformations to the extracted data to prepare it for analysis.
Perform tasks such as data cleansing, data type conversions, and merging of data from different sources.

## Load (L):
Define target connections in Informatica Cloud Data Integration to load the transformed data into the data warehouse tables.
Configure mappings to specify how the transformed data should be loaded into the target tables.

One specific transformation we'll perform is converting the Unix timestamp (TS) to a date format, which will make it more human-readable and suitable for analysis. Additionally, we'll concatenate certain columns to combine their information for better analysis.

## To effectively answer questions like:
. "What hour of the day experiences the highest traffic?"

. "Which artist garners the most song plays?"

. "How is the gender distribution within our customer base?"

. "Who among the artists receives the highest number of plays from our female customers?"

## Data Warehouse Model:

![model](https://github.com/MarinaFawzy/Sparkify-Music-Analytics/assets/89097013/590b0829-fc43-43c7-a590-9a951b5e84fb)

