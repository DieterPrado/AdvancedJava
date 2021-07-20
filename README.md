# Advanced Java
### Table of contents
- [General info](#general-info)
- [Technologies](#technologies)
- [Setup](#setup)
- [Things learned](#things-learned)
>- Abstract methods and classes
>- Interfaces
>- Functional interfaces.
>- Documentation with java docs.
>- Enums.
>- Try-catch
>- JDBC methods.
>- Lambdas.
>- Stream.
>- Consumer and predicates.
- [Commands](#commands)


------------

### General info

This repository contains files and explanations of things learned in the Platzi's Advanced Java course.The course reinforced concepts and knowledge from the JavaSE course like abstract methods, classes and interfaces and nested classes. It algo taught how to connect to a data bases and obtaind iformation from it. The project in this repository basically intends to be an interface for watching movies, books and magazines and have a track of what has already been seen, so we can know wich materials we haven't seen by sending and requesting this information to a database. The author of this projects its anncode because it was requiered to donwload an existing project (made by anncode) to follow the course.


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
- Abstract methods and classes. Abstract is a non-access modifier in java applicable for classes, methods but not variables. It is used to achieve abstraction which is one of the pillar of Object Oriented Programming(OOP). We can't make an instance of an abstract class. Example: public **abstract** class ExampleClass{}. Abstract methods must be implemented by classes extending the origin class of the abstract methods.

- Interfaces. An interface is a completely "abstract class" that is used to group related methods with empty bodies. interface InterfaceExample{ public exampleMethod(){}}.

- Functional interfaces (SAM). Interfaces with only a single abstract method. It can also have several non-abstract methods but only one abstract member.The SAM interfaces can be implemented using lambda expressions or method references.

- Importance and utilization of Java Docs

- Nested classes (static and non static classes). It is a way of logically grouping classes that are only used in one place. Example:

```java
class OuterClass {
    ...
    class InnerClass {
        ...
    }
    static class StaticNestedClass {
        ...
    }
}
```

- Ennumearations for constant collections. An enum type is a special data type that enables for a variable to be a set of predefined constants. If it has a constructor method this must be private to prevent the creation of new objects.

- How to handle erros using throwable.

- To use *try catch* to catch and error and know where it is. The try statement allows you to define a block of code to be tested for errors while it is being executed. The catch statement allows you to define a block of code to be executed, if an error occurs in the try block.

- JDBC, its an API for Java that manages java connections to databases. Some methods are:

- How to interact with a database using: drivermanager, connection, statement, preparedstatement, resultset. These methods are:
- DriverManager.getConnection() - Establish and return a connection object.
- Connection.createStatement() - Returns a statement object to execute SQL statements.
- Statement.executeQuery() - Execute a SQL SELECT statement and returns a result set object.

- DAO interface 

- How to use lambdas. A lambda expression is a short block of code which takes in parameters and returns a value. Lambda expressions are similar to methods, but they do not need a name and they can be implemented right in the body of a method. They are functions. Example: (number -> number+1). 

- Introduction to Stream data and how to filter information. Stream is sequence of elements supporting sequential and parallel aggregate operations.

- Consumers and Predicates. Consumers receive input and returns no result. Predicates receive input and return a boolen type result.




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
