 StudentDB-Sytem
StudentDB System is a Java JDBC-based application that stores, retrieves, and manages student details (name, age, course) from a MySQL database.

 📚 StudentDB System

 📌 Project Overview
**StudentDB System** is a console-based Java application designed to perform basic **CRUD operations** (Create, Read, Update, Delete) on student records stored in a **MySQL database**.  
The project follows a **layered architecture** using **DTO, DAO, DAO Implementation, Service, and DB Connection layers**, which is commonly used in real-world Java applications.

---

 🚀 Features
- Insert new student details
- Fetch student details by ID
- Fetch all student records
- Update existing student information
- Delete student records
- Uses JDBC for database connectivity
- Follows clean and modular architecture

---

 🛠️ Technologies Used
- **Java**
- **MySQL**
- **JDBC**
- **VS Code**
- **MySQL Workbench**

---

 🧱 Project Architecture
The project follows **DAO + DTO + Service Layer Architecture**:

```

Main
↓
Service
↓
DAO (Interface)
↓
DAOImpl (SQL Logic)
↓
DBConnection
↓
MySQL Database

```

---

 📂 Project Structure
```

StudentDB-System/
│
├── main/
│   └── MainApp.java
│
├── service/
│   └── StudentService.java
│
├── dao/
│   └── StudentDAO.java
│
├── daoimpl/
│   └── StudentDAOImpl.java
│
├── dto/
│   └── StudentDTO.java
│
├── db/
│   └── DBConnection.java
│
└── mysql-connector-j.jar

````

---
 🗄️ Database Details

 Database Name
```sql
studentdb
````

 Table Structure

```sql
CREATE TABLE student (
    id INT PRIMARY KEY,
    name VARCHAR(50),
    age INT,
    course VARCHAR(50)
);
```

---

 ▶️ How to Run the Project

1. Install **Java (JDK 17 or above)**
2. Install **MySQL Server & MySQL Workbench**
3. Create the database and table as shown above
4. Add **MySQL JDBC Connector JAR** to the project classpath
5. Update database credentials in `DBConnection.java`
6. Run `MainApp.java`

---

🎯 Learning Outcomes

* Understanding JDBC and database connectivity
* Implementing CRUD operations
* Applying DAO and DTO design patterns
* Structuring a real-world Java application
* Hands-on experience with MySQL

---
 👨‍💻 Author

**Ebin Jacob**
CSE – 6th Semester


