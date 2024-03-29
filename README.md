![cinema-app logo](readme.images/cinema-top.png)

### 📃 Description:
___

The project is a simple web application that showcases cinema functionality. It utilizes a multi-level architecture to ensure efficient task delegation and seamless interaction between different levels. This approach enhances logical separation, modularity, ease of maintenance, and scalability, providing a solid foundation for the application.

The application allows users to register and authenticate with different roles, each granting specific access levels. By leveraging HTTP requests, users can effectively manage the application by performing actions such as adding, editing, retrieving, and deleting data. This flexibility enables seamless data management and empowers users to interact with the application using various programs, such as Postman.

With its user-friendly interface and comprehensive functionality, the application offers an immersive experience for cinema management, facilitating tasks ranging from user registration and authentication to data manipulation through CRUD operations. Whether you're a cinema administrator or a movie enthusiast, this application provides a powerful tool for managing cinema-related information.

### 🔩 Functionalities:
___
- [X] login/register user
- [X] cinema-halls/add/getAll
- [X] movies/add/getAll
- [X] movie-sessions/add/findAvailableSessions/update/update
- [X] orders/completeOrder/getOrderHistory
- [X] shopping-carts/addToCart/getByUser
- [X] users/by-email

### 🏗️ Architecture:
___
- [X] DAO - data access layer
- [X] Service - application logic layer
- [X] Controllers - presentation layer

### 🎬 How to run this project:
___
Please make sure that Tomcat and MySQL (or any other relational database compatible with Hibernate) are installed and properly configured on your computer. You can find the official websites of these programs below:
- [X] <a href="https://tomcat.apache.org/">Tomcat: Official website</a></br>
- [X] <a href="https://www.mysql.com/">MySQL: Official website</a></br>

These tools are essential for the smooth running of the application. Before proceeding, make sure they are installed and configured correctly.
- [X] Clone the project from repository
- [X] Add a Tomcat configuration:
* tomcat server: local
* deployment: war exploded
* application context: ``/``
- [X] Configure [db.properties](src/main/resources/db.properties) with the following credentials:
* jdbc driver
* url
* username
* password
- [X] Add required maven dependencies in ``pom.xml`` file
- [X] Build the project using Maven command in terminal: ``mvn clean install``
- [X] The application has already registered 2 users with their own roles and access levels in [DataInitializer](src/main/java/cinema/config/DataInitializer.java): ``ADMIN and USER`` <br>
- [X] Alternatively, you have the option to manually add users and roles
- [X] Once the project is deployed, access the cinema app after authentication by opening http://localhost:8080 in your web browser

### 💻 Technologies:
___
- [X] [![Java](readme.images/technologies/java.png)](https://www.oracle.com/cis/java/technologies/downloads/) ``17``
- [X] [![Maven](readme.images/technologies/maven.png)](https://maven.apache.org/index.html) ``3.8.5``
- [X] [![Tomcat](readme.images/technologies/tomcat.png)](https://tomcat.apache.org/download-90.cgi) ``9.0.71``
- [X] [![MySQl](readme.images/technologies/mysql.png)](https://dev.mysql.com/downloads/installer/) ``8.0.22``
- [X] [![Spring](readme.images/technologies/spring.png)](https://plugins.jetbrains.com/plugin/20221-spring) ``5.3.20``
- [X] [![Hibernate](readme.images/technologies/hibernate.png)](https://plugins.jetbrains.com/plugin/20214-hibernate) ``5.6.14.Final``

<hr style="border: 2px solid lightgray;">

### 💬 Contacts:
___

```Oleksandr Chernetskiy:```<br>
- [X] [![Email](readme.images/contacts/email.png)](mailto:liero2d@gmail.com) <br>
- [X] [![Linkedin](readme.images/contacts/link.png)](https://www.linkedin.com/in/%D0%B0%D0%BB%D0%B5%D0%BA%D1%81%D0%B0%D0%BD%D0%B4%D1%80-%D1%87%D0%B5%D1%80%D0%BD%D0%B5%D1%86%D0%BA%D0%B8%D0%B9-05106a25b/)


