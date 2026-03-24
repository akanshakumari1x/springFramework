Spring Framework:-



Spring is a lightweight, open-source framework for building enterprise-level Java applications. It simplifies development by providing support for dependency injection (DI), aspect-oriented programming (AOP), transaction management and integration with various frameworks.



Key Features of Spring Framework:-



1.Dependency Injection: Dependency Injection is a design pattern where the Spring container automatically provides the required dependencies to a class, instead of the class creating them itself. This promotes loose coupling, easier testing and better maintainability by decoupling the object creation and usage.



2.Aspect-Oriented Programming (AOP): AOP allows developers to separate cross-cutting concerns (such as logging, security and transaction management) from the business logic.



3.Transaction Management: Spring provides a consistent abstraction for managing transactions across various databases and message services.



4.Spring MVC: It is a powerful framework for building web applications that follow the Model-View-Controller pattern.



5.Spring Security: Spring Security provides comprehensive security features including authentication, authorization and protection against common vulnerabilities.



6.Spring Data: Spring Data is a part of the Spring Framework that simplifies database access by providing easy-to-use abstractions for working with relational and non-relational databases.



7.Spring Batch: Spring Batch is a framework in Spring for handling large-scale batch processing, such as reading, processing and writing data in bulk.



8.Integration with Other Frameworks: Spring integrates seamlessly with other technologies like Hibernate, JPA, JMS and more, making it versatile for various enterprise applications.





**Spring beans definition:-**



There are two ways the object of class Title can be instantiated.

1\.    Using no-argument constructor followed by setter method

2\.    Using constructor with argument.



Example:-

// Creating the title of the book

// Step 1: Instantiate the object by calling no-argument constructor

Title bookTitle = new Title();

// Step 2: Call the setter method to set title value

bookTitle.setTitleValue("My First Spring Book"); // Setter method



// Creating the titles of the chapters by calling one-argument constructor

Title chapter1Title = new Title("Spring framework - Chapter 1");

Title chapter2Title = new Title("Spring framework - Chapter 2");



**Notice:-**  The objects of class Title are depended on titleValue. Without a titleValue, the object of Title class does not have any meaning. Thus titleValue is the dependency for classTitle. When we instantiated the object of class Title with a no argument constructor and then called the setter method to set the value of titleValue, it is known as injecting the dependencies using setter method.  When we instantiated the object of class Title by calling the one-argument constructor, it is known as injecting the dependencies using constructor.





