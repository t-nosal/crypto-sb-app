<h1>How to run</h1>
To run the application you need to create the resulting .jar file using the mvn clean package command.

Then launch the application using the command java -jar crypto-sb-app-0.0.1-SNAPSHOT.jar

By default, the application is exposed to http://localhost:8084/top5

The database is exposed on port: http://localhost:8084/h2-console
Credentials to the DB: 
<p>driver class: org.h2.Driver</p>
<p>JDBC URL: jdbc:h2:mem:planner</p>
<p>username: db_user</p>
<p> password: db_pass</p>
![image](https://user-images.githubusercontent.com/9469220/199693415-03053dd9-5a2e-43f8-a469-3c60922dcd6c.png)


