# messenger
Messenger console application using JAVA-JRE 1.8 and mySQL workbench 8.

***HOW TO RUN(for newbies).***
mySQL-connector 8.0.13.jar is needed to be added inside the projects library 'build path'. Extract it and save at your Desktop.
Find the mySQL-connector 8.0.13.jar file and add it inside the build path of your project using your IDE to allow connection to the database.

Open the messenger.sql script using mySQL workbench to create the schema needed for the application. (Its usefull to know that inside the project a database schema is set to be created if does not already exist inside mySQL).

This project connects to the database by using the default mySQL connection instance. Before running make sure the following information located inside the messenger-->src-->messenger.dao-->SqlMethods.class is correct in order to connect. You will most likely need to change the PASSWORD value. Open SqlMethods.class with your IDE to change the values if needed.
  HOST = "localhost";
	PORT = "3306";
	USER = "root";
	PASSWORD = "134561";

This application was created to demonstrate how to perform simple C.R.U.D. functions in JAVA using a mySQL schema and allow users to 
create Log files to store their messages.

Its basic funtion is to allow users to send messages between them.
Users can login with a specific username and password. Each user has a specified type given by the ADMIN that provides them with specific
privilleges when using the application. 
The ADMIN's credentials are username: admin password: admin.
When the application starts it creates a single MASTER_LOG txt file that stores all the messages contained inside the database.


