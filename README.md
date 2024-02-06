# Spark_Movie Data Analysis 

### This movie data analysis project aims to provide insights into movie review and rating information in the past few years. The projects with 3 datasets and put into GCP HDFS, to explore the analysis statement by using PySpark.

### Data Sources:
This projects contains 3 data CSV files 
1. movies: the data contains movieid, movie name(title), genres
2. ratings: the data contains userid, movieid, rating number, and timestamp
3. tags: the data contains userid, movieid, tag, and timestamp

### Tools
- GCP Dataproc (Google Cloud Platform managed service for Spark and Hadoop)
- Pyspark
- SparkSQL
- Jupyternotebook [page](link)

### Project Steps
Step 1 : Create GCP Dataproc \
Step 2 : Upload data CSV files into GCP via SSH \
Step 3 : put files into HDFS folder\
Step 4 : Explore the analysis via jupyternotebook accessing data in GCP HDFS 
