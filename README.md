# messenger
Messenger console application using JAVA-JRE 1.8 and mySQL-connector 8.0.13

This application was created to demonstrate how to perform simple C.R.U.D. functions in JAVA using a mySQL schema and allow users to 
create Log files to store their messages.

Its basic funtion is to allow users to send messages between them.
Users can login with a specific username and password. Each user has a specified type given by the ADMIN that provides them with specific
privilleges when using the application. 
The ADMIN's credentials are username: admin password: admin.
When the application starts it creates a single MASTER_LOG txt file that stores all the messages contained inside the database.
Inside the project a database schema is set to be created if does not already exist inside mySQL.

