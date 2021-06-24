# Data Modeling with Cassandra
> 
In this project I am taking on the role of a Data Engineer to create an Apache Cassandra database which can create queries on song play data to answer specific questions for a fictional startup called Sparkify. The queries are designed with a focus on what songs users are listening to. The project tasks included the modelling of the data by creating tables in Apache Cassandra to run queries on as well as the creation of an ETL pipeline that transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.

**Specifically, the data modelling tasks are centered around three questions:**
> 1. Give me the artist, song title and song's length in the music app history that was heard > during sessionId = 338, and itemInSession = 4
> 2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
> 3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

## Table of contents

* [Data and Code](#data-and-code)
* [Prerequisites](#prerequisites)
* [Instructions on running the application](#instructions-on-running-the-application)

## Data and Code
The dataset for the project is contained in event_data directory, which is a directory of CSV files partitioned by date. 

In addition to the data files, the project workspace includes two files:
* **Project_1B_ Project_Template.ipynb** : contains all the project data modelling code and ETL


## Prerequisites
* cassandra
* pandas
* csv
* os
* numpy
* json
Jupyter notebook and python 3 are needed to run the notebooks and python scripts.

## Instructions on running the application
Download the required data sets and if required modify the directory paths.
You also need access to a working Apache Cassandra installation.
Follow the instructions on the jupyter notebooks to execute the ETL pipeline.