# ****Taxi-Service****

**The presented project "Taxi service" is my first practical work on creating 
a 3-tier web-application. It was created for the convenience of accounting 
for a taxi fleet, storing information about drivers and their vehicles in a 
database.**

**A quick overview of the project structure:**
1. Controller - user interaction level
2. Service - the level at which all the business logic of the project is concentrated
3. DAO - the level of work with the database.

**To first run the application**
1. It is necessary to add the TomCat configuration to the project (I used version 9.0.56)
2. Using the instruction in the "init_db.sql" file from the "resource" folder for create a schema in MySQL WorkBench.
3. In the "ConnectionUtil" file from the folder "util" an initializait
   fields to connect to your database.

**Technologies used**
1. Java 11 
2. MySQL 8.0.27
3. Javax Servlet API
4. Tomcat 9.0.55
