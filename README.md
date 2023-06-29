## Description
This repository contains a Spring Boot application it will Read the CSV File then Csv file data Loaded into Objects.
Comparing Database table data to exixsting csv file data.
## Getting Started
To set up and run the project locally, follow these steps:
### Prerequisites
 Java Development Kit (JDK) version X or later.
 Maven version X or later.
 An IDE (e.g., IntelliJ, Eclipse) for Java development.
 ### Installation
 1. Clone the repository to your local machine:
    
     ```https://github.com/kcs-pratibhadeokar/Insurance_Config_Server.git```
 3. Open the project in your preferred IDE.

 4. Build the project using Maven. This will download all the necessary dependencies:
   
    ```mvn clean install```
    
### Configuration
Open the application.properties file located in the src/main/resources directory.

Provide the values in application properties file.

- CSV_file_path   -provide csv file path to compare with database data.
- file_seprator   -based on separator it separates data (eg-pipe,comma).
- database_table_name   -provide table name to compare data with csv file.
- sorting_field_name   -based on field it will sort data.

 ### Summary
 Prepare following details

- Level: Overview
  - Total Rows from Table   485
  - Total Rows from File    485
  - Difference    0   
- Level: Summary
   - Count No. of values available        
   - Table    CSV    Difference
   - Dstinct Count/Total of Value if item is Integer
   - Table    CSV    Difference.
- Level: Detail
  - Sort by any of the given date fields from the table
  - Pick the random 10 lines of data from the table and the same data line from CSV.
  - Have the difference between these data in case any have the flag true or false
  
 
