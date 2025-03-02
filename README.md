# JSP, Servlet, and PostgreSQL User Management System

Welcome to the JSP, Servlet, and PostgreSQL User Management System repository! This project facilitates the management of user information through a web-based interface using JavaServer Pages (JSP), Servlet, and PostgreSQL for database storage.

## Features

- **CRUD Operations for Users:**
  - Create, read, update, and delete user information.
- **Web Interface:**
  - User-friendly web pages created with JSP for seamless interaction.
- **Database Integration:**
  - Utilizes PostgreSQL for robust and persistent data storage.

## Getting Started

### Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Apache Tomcat](http://tomcat.apache.org/)
- [PostgreSQL Database](https://www.postgresql.org/download/)

### Installation

1. **Set up the database:**

    - Execute the SQL scripts in the `/db` directory to initialize the PostgreSQL database.

2. **Configure the database connection:**

    - Update the database connection details in `/src/com/example/util/DBUtil.java` file.

3. **Deploy the application:**

    - Deploy the application on your Apache Tomcat server.

4. **Access the application:**

    - Open your web browser and navigate to `http://localhost:8080/ServletHub`.

## Usage

1. **Manage Users:**
   - Perform CRUD operations to manage user information.

    - **Create User:**
      - Access the user creation page and fill in the required details.

    - **Read User:**
      - View a list of users and their details.

    - **Update User:**
      - Edit user information through the update page.

    - **Delete User:**
      - Remove a user from the system.

## License

This project is licensed under the MIT License.
