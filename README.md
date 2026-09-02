# ☕ Advanced Java

A practical collection of **Advanced Java programs and examples** covering JDBC, database connectivity, APIs, and Java-based application development.

This repository contains hands-on programs created while learning and practicing Advanced Java concepts.

---

# 📚 About This Repository

The purpose of this repository is to understand how Java applications interact with:

* Databases
* JDBC APIs
* SQL
* External resources
* Application-level components

The repository focuses on practical programming rather than only theoretical concepts.

---

# 🧠 Topics Covered

## 1. JDBC

Java Database Connectivity examples covering:

* JDBC Basics
* Database Connection
* JDBC Driver
* `Connection`
* `Statement`
* `PreparedStatement`
* `CallableStatement`
* `ResultSet`
* `ResultSetMetaData`
* CRUD Operations
* INSERT
* UPDATE
* DELETE
* SELECT
* SQL Queries
* Database Transactions
* Stored Procedures
* Functions
* Cursors
* Try-with-Resources
* Properties File Configuration

---

## 2. Database Connectivity

Examples demonstrating how Java applications communicate with relational databases.

Topics include:

```text
Java Application
       ↓
      JDBC
       ↓
  JDBC Driver
       ↓
   Database
```

Programs demonstrate database connection and execution of SQL operations from Java.

---

# 3. JDBC Statements

### Statement

Used for executing simple SQL statements.

### PreparedStatement

Used for parameterized SQL queries and helps prevent SQL injection.

### CallableStatement

Used for calling stored procedures and database functions.

---

# 4. CRUD Operations

Examples covering:

```text
CREATE
  ↓
READ
  ↓
UPDATE
  ↓
DELETE
```

Programs demonstrate how Java applications perform database operations using JDBC.

---

# 5. ResultSet

Examples covering:

* Reading database records
* Navigating records
* Retrieving column values
* Processing query results

---

# 6. Database Metadata

Examples covering:

* ResultSet Metadata
* Column information
* Database information
* Query result structure

---

# 7. Properties File Configuration

Database configuration can be maintained using properties files.

Example:

```text
connectioninfo.properties
driverinfo.properties
```

This helps separate configuration information from Java source code.

> **Security Note:** Do not store real database passwords or credentials in GitHub. Use local configuration or environment variables for sensitive information.

---

# 8. API Examples

The `api` package contains examples related to Java APIs and practical Java programming.

---

# 📂 Project Structure

```text
Advance_Java/
│
├── src/
│   ├── connectioninfo.properties
│   ├── driverinfo.properties
│   │
│   └── com/
│       └── adv_java/
│           │
│           ├── api/
│           └── jdbc/
│
├── .gitignore
├── .classpath
├── .project
└── README.md
```

---

# 🛠️ Technologies & Tools

* **Java**
* **Advanced Java**
* **JDBC**
* **SQL**
* **Oracle Database**
* **JDBC Driver**
* **Eclipse IDE**
* **Git**
* **GitHub**

---

# ▶️ How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/anand24raj/Advance_Java.git
```

## 2. Open in Eclipse

Import the repository as an **Existing Java Project**.

## 3. Navigate to

```text
src/com/adv_java/
```

## 4. Select a Program

Choose the Java class containing:

```java
public static void main(String[] args)
```

## 5. Run the Program

Right-click:

```text
Run As
   ↓
Java Application
```

---

# 🗄️ JDBC Configuration

Before running JDBC programs, make sure:

1. Database server is installed and running.
2. Required database is created.
3. Required JDBC driver is available.
4. Connection URL is configured.
5. Username and password are configured locally.

Do **not** commit real passwords or database credentials to GitHub.

---

# 🎯 Learning Path

```text
Core Java
    ↓
JDBC Fundamentals
    ↓
Database Connectivity
    ↓
Statement
    ↓
PreparedStatement
    ↓
CallableStatement
    ↓
ResultSet
    ↓
CRUD Operations
    ↓
Transactions
    ↓
Stored Procedures
    ↓
Practical Applications
```

---

# 🎓 Learning Goals

This repository aims to help develop practical skills in:

* Advanced Java programming
* JDBC
* Database connectivity
* SQL integration
* CRUD operations
* Database programming
* Java application development
* Exception handling
* Practical problem solving
* Java developer interview preparation

---

# 📌 Repository Type

This is primarily an **Advanced Java learning and practice repository**.

The examples are organized by topic so that individual programs can be studied and executed independently.

---

# 👨‍💻 Author

**Anand Raj**

MCA | Java Developer

---

⭐ If you find this repository useful, consider giving it a **star**.
