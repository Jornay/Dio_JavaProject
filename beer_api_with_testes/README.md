<h2>Digital Innovation: Expert class - Development of unit tests to validate a beer inventory management REST API.</h2>

In this live coding, we will learn how to test, unitarily, a REST API for managing beer stocks. We will develop unit tests to validate our beer inventory management system, as well as introduce the main concepts and advantages of creating unit tests with JUnit and Mockito. In addition, we will also show you how to develop our API functionality through TDD practice.

During the session, the following topics will be covered:

* Download a project via Git to develop our unit tests.
* Testing Conceptual Presentation: The Test Type Pyramid, as well as the importance of each test type during the development cycle.
* Focus on unit tests: show why it is important to develop these types of tests as part of the software development cycle.
* Main frameworks for unit testing in Java: JUnit, Mockito and Hamcrest. 
* Development of unit tests for validation of basic functionalities: creation, listing, query by name and exclusion of beers.
* TDD: presentation and practical example in 2 important functionalities: increase and decrease in the number of beers in stock.

To run the project on the terminal, type the following command:

```shell script
mvn spring-boot:run 
```

To run the test suite developed during live coding, just run the following command:

```shell script
mvn clean test
```

After executing the above command, just open the following address and view the project execution:

```
http://localhost:8080/api/v1/beers
```

The following prerequisites are necessary for the execution of the project developed during the class:

* Java 14 or higher versions.
* Maven 3.6.3 or higher versions..
* Intellj IDEA Community Edition or your favorite IDE.
* GIT version control installed on your machine.
* Willing to learn and share knowledge :)

Below, there are some nice links about topics mentioned during the class:

* [SDKMan! for managing and installing Java and Maven](https://sdkman.io/)
* [Intellij IDEA Community Reference, Downloadable](https://www.jetbrains.com/idea/download)
* [Intellij Command Shortcut Palette](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Spring's official website](https://spring.io/)
* [JUnit 5 official website](https://junit.org/junit5/docs/current/user-guide/)
* [Mockito official website](https://site.mockito.org/)
* [Hamcrest official website](http://hamcrest.org/JavaHamcrest/)
* [References - testing in general with Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Reference to the REST architectural standard](https://restfulapi.net/)
* [Test Pyramid Reference - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

[On this Link](https://drive.google.com/file/d/1KPh19mvyKirorOI-UsEYHKkmZpet3Ks6/view?usp=sharing), follow the slides presented as the roadmap used for the development of our session project.

<h3>
This project was produced by Digital Innovation One 🔧<h3>
<h3>This project was developed by Lucas de Abreu(Jornay) ⚒ <h3>

