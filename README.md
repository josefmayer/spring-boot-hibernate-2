## Spring Boot Hibernate

### Technologies
JPA, Hibernate, MySQL, H2, Spring Boot <br />


### Data Model
Entities: <br />
City, Hotel, Review <br />

Relations: <br />
City:Hotel = 1:n <br />
Hotel:Review = 1:n <br />

Tables in Database: <br />
city, hotel, review  <br />

Database tables are created at application start <br />
Insert of data via file 'import.sql' <br />


### Steps
##### MySQL
Start MySQL server, create database <br />

##### Build and Run Application
via spring-boot-maven-plugin: <br /> 
*mvn clean compile*  <br />
*mvn spring-boot:run*  <br />

##### Build jar, Run jar
*mvn package* <br />
*java -jar target/jar-name.jar* <br />

##### Access Application
*http://localhost:8080*


### Original Source:
https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples


