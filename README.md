# Web-Application-using-Cassandra-as-a-database
Developed a web application which uses Cassandra as a database

Outcome:
Track a vehicle by entering Date and Vehicle Id to retrieve the details and location in google maps.

I created an application using MVC architecture which uses Cassandra as a database.
 
I configured a Cassandra database and copied the vehicle data from a csv file into the cassandra cluster.

The data consists of the latitude and longitude of the vehicle on specific dates.

Using the above data we can locate a vehicle in a map on a specific day.

I used Cassandra datastax Java drivers to integrate Cassandra with Java application.

I used eclipse, Maven and Tomcat for the application.

I used Maven to retrieve all the jars from repository.

I used Cluster class from the datastax library which allows Java application to communicate with Cassandra.

I created a session object, used execute method to get the results using cqlsh

I used form to capture the details from front end and execute the query with the fetched details



