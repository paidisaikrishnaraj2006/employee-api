# Employee CRUD REST API

A production-ready RESTful API built using **Spring Boot**, **Spring Data JPA**, and an **H2 In-Memory Database**. This project includes fully implemented CRUD endpoints, Data Transfer Objects (DTOs), and input validation.

---

## 🚀 Features
* **Full CRUD Operations**: Create, Read, Update, and Delete employee profiles.
* **Data Validation**: Strict input validation using `jakarta.validation` (e.g., mandatory fields, proper email formatting).
* **In-Memory Database**: Uses H2 database for quick, zero-setup local execution.
* **Clean Architecture**: Follows the Controller-Service-Repository structural pattern.

---

## 🛠️ Tech Stack & Dependencies
* **Java 17**
* **Spring Boot 4.1.0**
* **Spring Web** (Rest Endpoints)
* **Spring Data JPA** (Database ORM)
* **H2 Database** (Runtime Storage)
* **Validation** (Input constraints)

---

## 🏃 How to Run the Project Locally

1. Clone this repository to your laptop.
2. Open your terminal/PowerShell in the project root folder.
3. Run the application using the Maven wrapper:

```powershell
.\mvnw.cmd spring-boot:run