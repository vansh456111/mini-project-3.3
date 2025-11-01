# Online Student Management System Using Spring and Hibernate

## Objective
To develop a Spring and Hibernate-based mini project demonstrating:
- Dependency Injection using Spring Java-based configuration
- CRUD operations using Hibernate ORM
- Transaction Management for fee payment and refund operations
- Integration of Spring + Hibernate for real-world data management

## Project Overview
This project is a comprehensive Student Management System built with Spring Framework and Hibernate ORM. It showcases enterprise-level Java application development practices, including dependency injection, object-relational mapping, and transactional operations for managing student records and fee transactions.

## Features
- **Student CRUD Operations**: Create, Read, Update, and Delete student records
- **Spring Dependency Injection**: Java-based configuration for managing application components
- **Hibernate ORM Integration**: Seamless database operations without writing SQL queries
- **Transaction Management**: Reliable fee payment and refund processing with rollback support
- **H2 Database**: Embedded database for easy setup and testing
- **Real-world Data Management**: Practical implementation of student information and financial transactions

## Technologies Used
- **Spring Framework**: For dependency injection and application configuration
- **Hibernate ORM**: For database operations and object-relational mapping
- **Java**: Core programming language
- **Maven**: Build automation and dependency management
- **H2 Database**: In-memory database for development and testing

## Requirements
- **Java**: JDK 8 or higher
- **Maven**: 3.6.0 or higher
- **H2 Database**: Included as Maven dependency

## How to Build and Run

### Build the Project
```bash
mvn clean install
```

### Run the Application
```bash
mvn exec:java -Dexec.mainClass="com.studentmanagement.Main"
```

### Access H2 Console (if configured)
1. Open browser and navigate to: `http://localhost:8080/h2-console`
2. Use JDBC URL: `jdbc:h2:mem:testdb`
3. Default credentials: username `sa`, password (leave empty)

## Project Structure
```
mini-project-3.3/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/studentmanagement/
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.md
```

## Configuration
The project uses Java-based Spring configuration to define beans and manage dependencies. Hibernate is configured to work with H2 database for development purposes.

## Contributing
Feel free to fork this repository and submit pull requests for any improvements or bug fixes.

## License
This project is open source and available for educational purposes.
