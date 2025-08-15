# flaskapi-project


This project is a simplified demonstration of a Flask API used to perform Create, Read, Update, and Delete (CRUD) operations on a MariaDB database.
Originally, this API was part of an internal automation project for Emirates Group IT to securely transfer newly encrypted data from a repository into the queries database in MariaDB.
For confidentiality, all sensitive data and connections have been replaced with hardcoded JSON sample data in this public version.

Tech Stack
- Python
- Flask – Web framework for building the REST API
- MariaDB – Relational database (mocked with local JSON in this demo)
- Flask-MySQL Connector / SQLAlchemy (depending on implementation)

Features
- GET – Retrieve data records from the database
- POST – Add new records to the database
- DELETE – Remove records from the database
- Modular code structure for easy extension and integration with larger systems

Notes
- In the original Emirates project, this API pulled encrypted data from a secure repository and inserted it into MariaDB tables for operational use.
- This version uses mock data and excludes all proprietary business logic, credentials, and configurations.
