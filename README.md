# CTRL-database2
<!-- CTRL Database
This repository contains the schema and structure for the CTRL Database, designed to store and manage medical and patient-related data. -->

<!-- Database Overview
The CTRL Database serves as a foundational backend for a healthcare system. It tracks information related to users (patients, providers, and staff), appointments, health statistics, and symptoms -->


<!-- Database Credentials
You can access the CTRL Database using the following credentials:
Username: devuser
Password: Amazing1!
Host: localhost
Port: 5432
Database: CTRL




prerequisites:
You will need postgres running as localhost on port 5432 -->

...
<!-- <!-- How to Set Up the Database -->
<!-- 1. Clone this repository to your local machine:
git clone https://github.com/yourusername/CTRL-database2.git
1. Navigate to the repository directory:
cd CTRL-database
1. Open PostgreSQL and create a new database (if not already created):
   CREATE Database CTRL;
4.Create a new user devuser with a password:
CREATE USER devuser WITH PASSWORD 'Amazing1!';
1. Grant the user full access to the CTRL database:
GRANT ALL PRIVILEGES ON DATABASE CTRL TO devuser; 
1. Use the schema.sql file to create the tables in the CTRL database, you create this file in the repo you cloned and then run the below command to execute the schema
psql -U devuser -d CTRL -f schema.sql
7.To check if the tables were created successfully, list all the tables in the CTRL database using the commands:
a. psql -U devuser -d CTRL -h localhost -p 5432
b. \dt
 -->


