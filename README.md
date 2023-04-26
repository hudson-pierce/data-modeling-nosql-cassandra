# NoSQL Data Modeling with Apache Cassandra

### Overview

This a completed project which I finished as part of a Data Engineering Udacity course. This project sets up a simple ETL pipeline for reading data from a CSV file which is then used to create a NoSQL database with 3 tables which correspond to the following 3 queries:

1. Give me the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4

2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182

3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'

### Running the Project:

In order to run this project, it is assumed you have Apache Cassandra installed on your machine. For install instructions, see the official [Apache Cassandra documentation](https://cassandra.apache.org/doc/latest/cassandra/getting_started/installing.html)

Once Cassandra is installed and running on your machine, you can run the [Jupyter Notebook](./Data_Modeling_NoSQL_Cassandra.ipynb).
