# Spring_MVC

This project is a simple Spring MVC application that demonstrates user authentication and registration using a MySQL database.
## Features
**Login**
**Register** 
**Database Integration** 
## Technologies Used :
**Spring MVC:** Framework for building Java-based enterprise applications.
**MySQL:** Database management system for data storage.
**HTML, CSS, Bootstrap:** Front-end technologies for a clean and responsive user interface.
## Project Setup:
1. **Database Configuration**:
    - Update the database connection details in `Dbconnection.java`.
2. **Run the Application:**
    - Use an IDE like IntelliJ or Eclipse to run the application.
3. **Access the Application:**
    - Open a web browser and navigate to `http://localhost:8080` to access the login form.
## Usage:
- Visit the login page to log in with existing credentials.
- Click on the registration link to create a new account.
 
## Difficulties Faced:
1. **Class Not Found Exception - MySQL Driver:**
 
    - The application encountered a `Class Not Found Exception: com.mysql.cj.jdbc.Driver`.
    - We added the MySQL Connector/J library to the project dependencies. Ensure that the correct version of the MySQL Connector/J is included in the project's build path.
2. **Database Connection Issues:**
 
    - Establishing a connection to the MySQL database was not successful.
    - Double-check the database connection URL, username, and password specified in the `Dbconnection.java` class. Ensure that the MySQL server is running and accessible.
3. **Styling and UI Design:**
 
    -  Achieving an aesthetically pleasing and responsive design using Bootstrap.
    -  Experiment with Bootstrap classes and custom styles to enhance the user interface. Consider seeking inspiration from Bootstrap documentation and examples.
4. **User Authentication Logic:**
 
    -  Creating robust user authentication logic.
    -  Refactor the authentication logic in the `AuthController` and `UserDao` classes. Consider incorporating Spring Security for a more comprehensive solution.
5. **Error Handling:**
 
    - Improving error handling and providing meaningful error messages to users.
    - Enhance error messages and implement proper exception handling in controllers and DAO classes.
