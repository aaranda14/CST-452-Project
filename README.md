The N-Layer Ecommerce Application with Spring Boot project aimed to develop a robust ecommerce platform
using Java, Spring Boot, and related technologies. The project involved the implementation of a multi-layer
architecture, including presentation, business services, and persistence layers. Leveraging Spring Boot and Spring
MVC, we aimed to achieve rapid development and deployment of the application. The project also focused on
implementing security features using Spring Security and ensuring responsive design using Bootstrap. This report
documents the design and implementation details of the project, including technical approaches, key design
decisions, and known risks.

Design Introduction
My proposed solution entails the development of a comprehensive N-Layer Ecommerce
Application utilizing Spring Boot. The application aims to provide users with a seamless
shopping experience while ensuring scalability, maintainability, and security.
Presentation Layer: The user interface will be designed using Spring MVC with Thymeleaf
templates, offering dynamic and responsive web pages.
Persistence Services Layer: Spring JDBC will be utilized for database access, ensuring efficient
data storage and retrieval. Pseudocode snippets have been included to outline the logic for
interacting with the database and performing CRUD operations on relevant entities. 

Detailed High-Level Solution Design:
In the proposed design for the N-Layer Ecommerce Application, the system architecture is
structured to accommodate the various layers and components effectively.
System Diagrams: I have created UML Component and UML Deployment diagrams to logically
and physically depict the system. These diagrams provide a visual representation of how
different components interact within the system and how they are deployed across various
hardware resources.
Solution Configuration Changes: The proposed solution requires configuration changes to align
with the technical environment and meet functional and non-functional requirements. This
includes setting up database connections, configuring security settings using Spring Security, and
defining application properties for flexibility and customization.
Approach for Non-Functional Requirements: To assure non-functional requirements such as
security and performance, the solution incorporates industry best practices and utilizes Spring
Security for authentication and authorization. Additionally, performance optimization techniques
will be employed, such as caching and database indexing, to ensure optimal system performance. 

Install Instructions:
Our project can be cloned from this link https://github.com/aaranda14/CST-451-Project and
import the project into your IDE and run as a Spring Boot App. Our project is a Maven project
but have not done a Maven build yet to run a compiled .jar program. Java 17 and the latest
 © 2020. Grand Canyon University. All Rights Reserved. 7
version of Maven should be installed on your desktop so you can run the appropriate
commands from a terminal program to run our E-Commerce application.
General Technical Approach:
Our approach for this project is to develop an N-Layer Ecommerce Application using the Spring
Boot framework. The application will have a presentation layer, business services layer, and
persistence services layer. We will leverage Spring MVC compliant pages with Thymeleaf
templates for the presentation layer. Bootstrap framework will be used to ensure a responsive
design. Spring JDBC or Spring Data JDBC will be utilized for database access. We will implement
proper exception handling, error handling, and data validation on all form fields. The
application will be secured using Spring Security with form-based authentication and API
authentication.
Key Technical Design Decisions:
 Use of Spring Boot framework for rapid application development.
 Spring MVC with Thymeleaf templates for the presentation layer.
 Spring JDBC or Spring Data JDBC for database access.
 Bootstrap framework for responsive design.
 Spring Security for authentication and authorization.
