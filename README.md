# BIG-DATA-Real-Time-Integration
A big data POC to Integrate Sqoop, Kafka, Spark, Hadoop, Hive and RDBMS, move data real time or shortest possible time. 
Following is the Detail Description of the POC with an example:

Project Scenario:
Step 1: Assume Employee Table in source Oracle Database has 5 records with each row has salary of $1000
Step 2: Move all 5 records from source to HDFS
Step 3: HDFS should have all 5 employee records as is in source
Step 4: Final Target table should have one row that looks like Employee Count = 5 and Total Salary = $5000
Step 5: Update one employee record in source and increase salary by 10%
Step 6: Insert 1 new employee record in source with salary = $1000
Step 7: Both inserted record and updated record should be moved to HDFS
Step 6: Target should now reflect change like Employee Count = 6 and Total Salary = $6100


Technology Stack used of POC:

•	MYSQL as a Relational Database
•	Kafka message bus
•	Spark streaming 
•	Scala
•	HDFS
•	Hive

