# Sparkify - Data Modeling with Cassandra

The main objective of the project is to model a NoSql database in Apache Cassandra and create an ETL pipeline using Python for a startup called Sparkify, which wants to analyze and query the data about songs and user activity from its new music streaming app in an easy way. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

## Analytical objectives

Model the given data by creating denormalized tables and provide to the analytics team an easy way to query it and understand the behavior of users activity within the Sparkify music streaming app and finally make decisions.

## Project Datasets

For this project, you'll be working with one dataset: event_data. The directory of CSV files partitioned by date. Here are examples of filepaths to two files in the dataset:

```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```

## Project Structure

```
|____event_data			# Contains Dataset for user activity and songs
|____images			# Images used for README file and show final csv structure
|____Project_1B_ Project_Template.ipynb			# ETL builder
|____README.md			# README file
```