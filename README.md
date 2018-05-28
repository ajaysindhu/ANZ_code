# ANZ_code
DataIngestion
# This repo contains the high level design for ingesting structured data from a set of 3 CSV files into hive tables batch mode using hive query language
# Directory sturcture
#The files will arrive in a desLanding zone 
# exception handling, error reporting, logging.
error reporting

Unit testing:
check the count of files in the landing directory
check for empty files
check for any change in reference file:
If there is no change in reference file, do not upload that.

Validations Post loading the csv files in hive table:

Count the number of records in csv file using wc -l and compare it with number of records loaded in the hive table using select * from table_name


Once the files are loaded in hive tables.
Keep the files for N days before moving them to archive directory.








