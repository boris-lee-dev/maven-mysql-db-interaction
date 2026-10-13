# Maven MySQL Database Interaction

A Core Java application demonstrating database interaction using **JDBC** (Java Database Connectivity) and **MySQL**, managed via **Maven**.

## 🛠 Tech Stack
* **Java**
* **MySQL**
* **JDBC API** (`DriverManager`, `PreparedStatement`, `Statement`)
* **Maven** (Dependency management & build automation)
* **JUnit** (Unit testing)

## 🏗 Project Architecture
The project strictly follows layer separation standards:
* `model` — Data model entity (`User`).
* `dao` — Data Access Object layer for database operations.
* `service` — Business logic layer interacting with DAO.
* `util` — Database connection utility class.

## 🚀 Getting Started
1. Configure connection details via Environment Variables:
    * `DB_URL`
    * `DB_USER`
    * `DB_PASSWORD`
2. Run `Main.java` to execute the end-to-end database flow.