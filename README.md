# Atomic management of two data sources, Using Spring batch
This repository implements a job to manage two data sources , with #Spring-batch #Spring-boot Framework version 3, #PostgreSQL for the management of the created database and #Lombok.

Below, we are going to have a brief look at the exact SQL commands used to set up the demo database, along with detailed descriptions of each table. After that, we will demonstrate the use of the app using the job to manage the two data sources in case of error and rollback action .. 

# First Step/Commit : Config Batch with one step : 
Batch configuration.

Chunck orineted step.

CSV reader + JDBC Writer (postgres BD).

Processor: Data mapping + step execution context management.
