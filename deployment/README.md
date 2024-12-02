## Deployment - Bank Project v2.0

[GitHub Repository](https://github.com/Back-end-Project/Bank-Project)

High-Level Overview
* Purpose:
    * A web application simulating banking operations.
    * Allows users to:
        * Manage accounts.
        * View transactions.
        * Perform deposits, withdrawals, and fund transfers.
* Target Users:
    * Individuals seeking a digital platform for banking activities, including:
        * Checking balances.
        * Transferring funds.
        * Viewing transaction history.
* Job Formation:
    * Provides an efficient alternative to physical bank visits.
    * Streamlines financial management for users.
* Inspiration:
    * Derived from the growing demand for digital banking solutions.
    * Designed as a simple yet effective educational tool to mimic real banking functionalities.

Important Features
* Account Management:
    * Create, view, and manage bank accounts.
* Transaction History:
    * View detailed records of transactions.
* Deposit and Withdrawal:
    * Perform basic banking transactions securely.
* Fund Transfer:
    * Transfer funds between accounts easily.

STAR Interview Breakdown
Situation
* The project aimed to simulate real banking functionalities for digital financial management.
* A robust deployment process was critical to ensure accessibility and reliability.
Task
* Deployment structure included:
    * Docker: For containerization.
    * GitHub Actions: For CI/CD automation.
    * Render: For hosting the application.
Action
* Containerization:
    * Created a Dockerfile defining the application environment and dependencies.
* CI/CD:
    * Set up GitHub Actions workflows to automate:
        * Testing.
        * Building.
        * Deployment.
* Deployment:
    * Used Render to host the application, ensuring stability and real-time availability.
Result
* Enabled rapid iteration and seamless updates.
* Ensured that the application remained stable and accessible.
* Screenshots of CI/CD pipelines and the app running on Render highlight its effectiveness.

Technologies Used
Containerization:
* Docker:
    * Packaged the application and dependencies into portable containers.
CI/CD:
* GitHub Actions:
    * Automated testing, building, and deployment processes.
Deployment:
* Render:
    * Hosted the application and managed the production environment.
Back-end:
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

Competencies
1. Deployment Management:
    * Situation:
        * Deployed the Bank Project to ensure reliability and ease of updates.
    * Actions:
        * Used Docker for containerization and defined a Dockerfile.
        * Automated CI/CD pipeline with GitHub Actions for testing and deployment.
    * Results:
        * Improved release efficiency and maintained a deployable application state.
    * Connection to Project:
        * Managed and streamlined deployment processes for the Bank Project.
2. Containerization:
    * Situation:
        * Ensured consistency across development and production environments.
    * Actions:
        * Created Docker images and defined a Dockerfile.
        * Configured the environment, dependencies, and application for deployment.
    * Results:
        * Achieved reliable deployments with minimal discrepancies between environments.
    * Connection to Project:
        * Containerization was essential for the Bank Project’s deployment strategy.
