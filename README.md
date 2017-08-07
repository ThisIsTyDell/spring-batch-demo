# spring-batch-demo
This spring batch demo reads from CSV, processes the data, and stores results in db.

Link to main: https://github.com/ThisIsTyDell/spring-batch-demo/tree/master/src/main/java/hello

1. The application imports 1000 records from a CSV file containing user information of First Name and Last Name.
2. During processing of each record it will be transformed into Uppercase.
3. LoggerFactory will log each conversion.
4. After processing each record will be written to the DB.
5. Upon completion of the job, LoggerFactory will log that the job is complete, query the database, and log the results from DB.
