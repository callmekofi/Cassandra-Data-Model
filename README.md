# Data-Model (Cassandra)

Introduction: This assignment aims to construct a NoSql database using Cassandra to examine songs and user activity data collected by Sparkify. This uses models to design and create tables to optimise queries on datasets made available by Sparkify as log data and song data in JSON formats. At the end of this project, the Sparkify analysis team can retrieve results based on queries on what songs its users are listening to.

IMPORTANT PROCESSES:
- Create tables in sql_queries.py

- Build ETL processes and Pipelines in etl.py

- Test queries on dB.

NOTE: ETL pipeline retrieves data from files and transforms them into tables in a dB. This process starts by extracting files using python file-handling methods and pandas to read the individual files. Functions are created to iterate over the individual files in the dir and extract information from the files. The files are processed based on content and inserted into the unique tables created using SQL queries.


TABLES CREATED:

Facts: 

Song plays = Made up of songplay events for the datasets given to inform business decisions.

Dim: 

Users = Made up of users registered to the Sparkify app. 

songs = Made up of all available songs in the Sparkify music dB 

artists = Made up of all artists of the songs in the Sparkify misuc dB 

Time = Made up of the timestamps of the song played by users of the Sparkify app.
