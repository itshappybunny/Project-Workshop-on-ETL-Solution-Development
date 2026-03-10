# Project-Workshop-on-ETL-Solution-Development


2026/03/10 09:22:05 - Spoon - Starting job...
2026/03/10 09:22:05 - Job CSV_to_MYsql - Start of job execution
2026/03/10 09:22:05 - Job CSV_to_MYsql - Starting entry [Set variables]
2026/03/10 09:22:05 - Job CSV_to_MYsql - Starting entry [File exists]
2026/03/10 09:22:05 - Job CSV_to_MYsql - Starting entry [HTTP ]
2026/03/10 09:22:05 - HTTP  - Start of HTTP job entry.
2026/03/10 09:22:05 - HTTP  - Connecting to URL: https://raw.githubusercontent.com/BosenkoTM/workshop-on-ETL/main/data_for_lessons/samplestore-general.csv
2026/03/10 09:22:06 - HTTP  - Resource type: Content-Type: application/octet-stream, last modified on: Tue, 10 Mar 2026 06:22:06 GMT.
2026/03/10 09:22:06 - HTTP  - Finished writing 2488346 bytes to result file [/home/dev/Downloads/lab_etl/data_for_labs/lab_csvexl_to_mysql/datain/samplestore-general.csv]
2026/03/10 09:22:06 - Job CSV_to_MYsql - Starting entry [Wait for]
2026/03/10 09:22:11 - Job CSV_to_MYsql - Starting entry [csv to orders]
2026/03/10 09:22:11 - csv to orders - Using run configuration [Pentaho local]
2026/03/10 09:22:11 - lab_02_1_csv_orders - Dispatching started for transformation [lab_02_1_csv_orders]
2026/03/10 09:22:13 - table production.0 - Connected to database [Mysql_core] (commit=10000)
2026/03/10 09:22:14 - CSV file input.0 - Header row skipped in file '/home/dev/Downloads/lab_etl/data_for_labs/lab_csvexl_to_mysql/datain/samplestore-general.csv'
2026/03/10 09:22:14 - CSV file input.0 - Finished processing (I=9995, O=0, R=0, W=9994, U=0, E=0)
2026/03/10 09:22:14 - Select values.0 - Finished processing (I=0, O=0, R=9994, W=19988, U=0, E=0)
2026/03/10 09:22:14 - Dummy (do nothing).0 - Finished processing (I=0, O=0, R=9994, W=9994, U=0, E=0)
2026/03/10 09:22:14 - Write to log.0 - 
2026/03/10 09:22:14 - Write to log.0 - ------------> Linenr 1------------------------------
2026/03/10 09:22:14 - Write to log.0 - row_id = 4354
2026/03/10 09:22:14 - Write to log.0 - order_date = 10/12/2019
2026/03/10 09:22:14 - Write to log.0 - ship_date = 12/12/2019
2026/03/10 09:22:14 - Write to log.0 - ship_mode = Second Class
2026/03/10 09:22:14 - Write to log.0 - sales = 13
2026/03/10 09:22:14 - Write to log.0 - quantity = 2
2026/03/10 09:22:14 - Write to log.0 - discount = 0
2026/03/10 09:22:14 - Write to log.0 - profit = 6.2
2026/03/10 09:22:14 - Write to log.0 - returned = null
2026/03/10 09:22:14 - Write to log.0 - 
2026/03/10 09:22:14 - Write to log.0 - ====================
2026/03/10 09:22:14 - table production.0 - ERROR (version 9.4.0.0-343, build 0.0 from 2022-11-08 07.50.27 by buildguy) : Unexpected error
2026/03/10 09:22:14 - table production.0 - ERROR (version 9.4.0.0-343, build 0.0 from 2022-11-08 07.50.27 by buildguy) : org.pentaho.di.core.exception.KettleStepException: 
2026/03/10 09:22:14 - table production.0 - Field [product_type] is required and couldn't be found!
2026/03/10 09:22:14 - table production.0 - 
2026/03/10 09:22:14 - table production.0 - 	at org.pentaho.di.trans.steps.tableoutput.TableOutput.processRow(TableOutput.java:105)
2026/03/10 09:22:14 - table production.0 - 	at org.pentaho.di.trans.step.RunThread.run(RunThread.java:62)
2026/03/10 09:22:14 - table production.0 - 	at java.base/java.lang.Thread.run(Thread.java:829)
2026/03/10 09:22:14 - Filter rows.0 - Finished processing (I=0, O=0, R=41, W=41, U=0, E=0)
2026/03/10 09:22:14 - Write to log.0 - Finished processing (I=0, O=0, R=1, W=1, U=0, E=0)
2026/03/10 09:22:14 - lab_02_1_csv_orders - ERROR (version 9.4.0.0-343, build 0.0 from 2022-11-08 07.50.27 by buildguy) : Errors detected!
2026/03/10 09:22:14 - Value mapper.0 - Finished processing (I=0, O=0, R=2, W=2, U=0, E=0)
2026/03/10 09:22:14 - Memory group by.0 - Finished processing (I=0, O=0, R=9994, W=141, U=0, E=0)
2026/03/10 09:22:14 - table production.0 - Finished processing (I=0, O=0, R=1, W=0, U=0, E=1)
2026/03/10 09:22:14 - lab_02_1_csv_orders - Transformation detected one or more steps with errors.
2026/03/10 09:22:14 - lab_02_1_csv_orders - Transformation is killing the other steps!
2026/03/10 09:22:14 - lab_02_1_csv_orders - ERROR (version 9.4.0.0-343, build 0.0 from 2022-11-08 07.50.27 by buildguy) : Errors detected!
2026/03/10 09:22:14 - Job CSV_to_MYsql - Starting entry [Write to log]
2026/03/10 09:22:14 -  - no connect to resourse
2026/03/10 09:22:14 - Job CSV_to_MYsql - Starting entry [Abort job]
2026/03/10 09:22:14 - Abort job - ERROR (version 9.4.0.0-343, build 0.0 from 2022-11-08 07.50.27 by buildguy) : Aborting job.
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [Abort job] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [Write to log] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [csv to orders] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [Wait for] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [HTTP ] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [File exists] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Finished job entry [Set variables] (result=[false])
2026/03/10 09:22:14 - Job CSV_to_MYsql - Job execution finished
