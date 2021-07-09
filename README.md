# Advanced Java
### Table of contents
- General info
- Technologies
- Setup
- Things learned
- Commands


------------

### General info

This repository contains files and explanations of things learned in the Platzi's Advanced Java course.The course reinforced concepts and knowledge from the JadaSE course like abstract methods, classes and interfaces and nested classes. It algo taught how to connect to a data bases and obtaind iformation from it. The project in this repository basically intends to be an interface for watching movies, books and magazines and have a track of what has already been seen, so we can know wich materials we haven't seen by sending and requesting this information to a database. The author of this projects its anncode because it was requiered to donwload an existing project (made by anncode) to follow the course.


------------

### Technologies
- Eclipse 2021-06
- MySQL 8.0.25
- Xampp 8.0.7



------------

### Setup

###### Eclipse 2021-06
- Go to https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2021-06/R/eclipse-inst-jre-win64.exe and click the donwload button.
- Complete the installation process.

###### MySQL 8.0.25
- Go to https://dev.mysql.com/downloads/connector/j/ and click on "go to download page" button.
- Sign up on oracle and donwload the program.
- Download either web community or community program.
- Complete the installation process.


###### Xampp 8.0.7
- Go to https://www.apachefriends.org/es/index.html and click the download button of your OS.
- Complete the installation process.




------------
### Things learned
- Abstract class
- Interfaces
- Functional interfaces (SAM)
- Importance and utilization of Java Docs
- Nested classes (static and non static classes)
- Enumeratios
- How to handle erros using throwable.
- To use *try catch finally* to catch and error and know where it is. 
- JDBC
- How to interact with a database using: drivermanager, connection, statement, preparedstatement, resultset.
- DAO interface 
- How to use lambdas
- Introduction to Stream data and how to filter information
- Consumers and Predicates




------------
### Commands
|  Command | Function  |
| ------------ | ------------ |
| abstract | Defines something as abstract (methods, classes, interfaces) |
| try{}catch{}finally{} | Used fo code blocks that are vulnerable. |
| try with resources  | Closes the resource flow by his own.|
| INSERT | SQL syntax, used to inserto values into a table or column. |
| SELECT | SQL syntax, select the information to work with. |
| DriverManager | Creates an instance of the connection. |
| Connection | Generates the session and stores it. |
| Statement | Helps us to bring data from specific tables. |
| PreparedStatement | Receive parameters and help us to bring data from specific tables. |
| Resulset	 | Interface that will help us manage the data obtained by converting the data into objects. |
| Stream | Handle lambdas  |
| .filter() | Compares if a WHERE statement equals certain value or condition. |
| *parameter* -> {lambdas body} | Lambdas structure. |
| Predicate | Receives data and return a boolean. |
| Consumer | Receives data and returns no result |
