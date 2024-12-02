## Back End Wallet Wizzard

[GitHub Repository](https://github.com/Back-end-Project/Bank-Project)


Give a high-level overview of the project purpose
- Questions to consider:
    - What are the users?
      - The users are customers seeking a secure and reliable solution to manage their finances.
    - What job does it form for them?
      - It is a web-based bank that enables customers to deposit, withdraw, and transfer money seamlessly between accounts.
    - What inspired you to make it?
      - I was inspired by the work we do at Amex and aimed to recreate it on a much smaller scale.
    - What features are the most important?
      - The difference between user types: Admin and Customer
      - The ability to transfer funds from one account to another

## Technologies
Containerization:
* Docker:
    * Packaged the application and dependencies into portable containers.
CI/CD:
* GitHub Actions:
    * Automated testing, building, and deployment processes.
Deployment:
* Render:
    * Hosted the application and managed the production environment.
*Back-end:
    * Spring Boot (v3.2.7): For building the RESTful API.
    * Java (v17): For application logic.
Database:
    * PostgreSQL: For persistent data storage.
    * H2 Database: For in-memory testing.
Dependencies:
    * Spring Boot Starter Data JPA: For database access.
    * Spring Boot Starter Security: For authentication and authorization.
    * Spring Boot Starter Web: For building web applications.
    * JJWT: For JWT handling.
    * Lombok: For reducing boilerplate code in models.
    * Spring Boot Starter Test: For testing.


## Competencies
### JF 3.6
Can implement a RESTful API
* The project itself is a backend consisting of a RESTful API which is created with Java and Springboot.
* The controllers are the API Endpoints that correspond to a specific function HTTP Methods and we use DI & Services to implement service classes to interact with the database

### JF 3.7
Can implement authentication and authorization to an API.
* To ensure there is an auth where we integrate if they are a student or teacher we use JWT and Identity and Auth 
* The routes are protected with authorization to restrict access to the methods

### JF 3.8
Can encrypt sensitive data via hashing
* Used a hashing algorithm provided by packages such as the PasswordHasher and created an example out of it
