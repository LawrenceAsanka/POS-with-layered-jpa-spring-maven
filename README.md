# POS System

In this **POS System** has all the functionalities of a POS system, like customer adding,item management,order placing,order viewing and order searching.It consists of five main parts;

    * Manage customers
    * Manage items
    * Placeorders
    * View orders
    * Search orders

Further this POS System has implemented by using various technologies and frameworks.Click the above link to check those implementations.

[Different Implementations of POS System](https://github.com/LawrenceAsanka/Point-of-Sale-System/blob/master/README.md)    

## Prerequisites

* Before use this application you must need to install [JAVA](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) runtime environment and [MYSQL](https://www.mysql.com/) database management services.

## Configurations

Find the resource directory from src/main/resources/application.properties and config the below properties with your dialect,database name,user name and password.

`hibernate.dialect=org.hibernate.dialect.<dialect>
 hibernate.connection.url=jdbc:mysql://localhost:3306/<database name>?createDatabaseIfNotExist=true
 hibernate.connection.username=<user name>
 hibernate.connection.password=<password>
`

## Dependencies

* [JFoenix](https://mvnrepository.com/artifact/com.jfoenix/jfoenix) - is an open source Java library, that implements Google Material Design using Java components.
* [MySQL Connector](https://mvnrepository.com/artifact/mysql/mysql-connector-java) - MySQL Connector/J is the official JDBC driver for MySQL.
* [Hibernate](https://mvnrepository.com/artifact/org.projectlombok/lombok) - Hibernate ORM is an object-relational mapping tool for the Java programming language. It provides a framework for mapping an object-oriented domain model to a relational database.
* [Lombok](https://mvnrepository.com/artifact/org.hibernate/hibernate-core) - Project Lombok is a java library that automatically plugs into your editor and build tools, spicing up your java.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate.

## License

Distributed under the MIT License. See [License](LICENSE) for more information.
