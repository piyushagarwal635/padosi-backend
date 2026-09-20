# PADOSI - Backend Application

Welcome to the backend repository of **PADOSI** - A hyperlocal neighbourhood platform built on the principle of controlled trust.

## 🚀 Technologies Used
- **Java 26**
- **Spring Boot 3.x**
- **Spring Data JPA**
- **Spring Security**
- **PostgreSQL**
- **Maven**
- **Lombok**

---

## 🛠️ Getting Started for Developers

If you are a new developer joining the team and want to run this backend on your machine, follow these steps:

### 1. Prerequisites
- **Java JDK (v26)**: Make sure you have Java 26 installed. (Java 21 LTS is also compatible if adjusted in pom.xml).
- **PostgreSQL**: Install PostgreSQL on your machine and ensure it's running on port 5432.
- **IDE**: IntelliJ IDEA (recommended), Eclipse, or VS Code.

### 2. Clone the Repository
Open your terminal and clone the repository:
\\\ash
git clone <YOUR_BACKEND_GITHUB_REPO_URL>
cd padosi-backend
\\\

### 3. Database Setup
Before running the application, you must configure your local database:
1. Open pgAdmin or your terminal and create a database named padosi_db.
2. Open src/main/resources/application.properties in this project.
3. Update the spring.datasource.username and spring.datasource.password to match your local PostgreSQL credentials.

### 4. Run the Application
You can run the application directly using the Maven wrapper included in the project:
\\\ash
./mvnw spring-boot:run
\\\
*Or simply open the project in IntelliJ IDEA, wait for it to sync, and run the main application class.*

The server will start by default on http://localhost:8080.

Happy Coding! 🚀
