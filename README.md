# Big-Data-with-PySpark
Big Data projects exploring PySpark functionality. Going through rdd's, dataframes, machine learning (recommendations), streaming, ETL pipelines and AWS ETL (S3,RDS,DMS,Glue,Lambda) pipelines with mySQL and postgreSQL integration.

### Office-Data-Project ###
A simple project showing data analysis and data manipulation using pyspark, mostly RDD's and DataFrames.
Notebook imported from databricks cloud.

### Students-Project ###
A simple project showing data analysis and data manipulation using pyspark, mostly RDD's and DataFrames.
Notebook imported from databricks cloud.

### Collaborative-Filtering ###
Collaborative filtering with PySpark (recommender system). 
Predicting which movies a user will like and getting movie recommendations to the user by using machine learnin algorythms.

### ETL-Project ###
Exploring ETL with pyspark. Extracting data from a text file, 
doing transformations with pyspark functions and loading it into AWS RDS with postgreSQL.

### CDC-Project ###
A CDC - Change Data Capture (Replication on Going) project.
A MySQL database will be placed in AWS RDS. 
AWS DMS will take data from RDS and write that data into temporary S3 bucket.
Next Lambda funtion will be triggered for every new object stored in temp S3 bucket 
and invoke PySpark Job in AWS Glue.
All the changes to the RDS DB will be eventually replicated to the final S3 storage.

![chart](https://github.com/rafaski1/Big-Data-with-PySpark/blob/main/CDC.PNG?raw=true)
