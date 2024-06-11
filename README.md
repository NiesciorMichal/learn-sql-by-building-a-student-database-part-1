insert_data.sh: Script to insert data from courses.csv and students.csv into students database.

student_info.sh: More advanced script to print various students info using JOINS, AGGREGATES, REGEX etc.

bike-shop.sh: CLI to use Bike Rental Shop (data stored in the bikes.sql)

To recreate database from the dump, first you must create database from the PSQL prompt:
CREATE DATABASE bikes;

Then from bash use:

$ psql -U <username> bikes < bikes.sql

You may then add additional rows to the database within all the constraints.