## Case Introduction
Implementation of deploying a web login page built using Flask and PostgreSQL.
Data from user sign-ups will be stored in a PostgreSQL database.
Deployment simulation is conducted using Docker to build images of Flask and PostgreSQL, which are then run within Docker containers

![dc](https://github.com/user-attachments/assets/326e289e-87b9-4fbf-8b41-9bef8059c92f)


## WorkFlow
1. Setup custom Image for PostgreSQL
2. Create Flask APP
3. Setup Custom Image for Flask APP
4. Test Scenario : Case 1
   Flask App can connect to postgreSQL and user can insert data
5. Test Scenario : Case 2
   Admin can log in to container postgreSQL and ensure that the previously entered data has been   successfully inserted into the database.








