# Banking System using Hibernate

## Table of Contents
- [Project Overview](#project-overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
- [Database Setup](#database-setup)  
- [How to Run](#how-to-run)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)  

## Project Overview  
This is a simple Banking System implemented in Java using Hibernate ORM. It provides basic bank account management functionality like creating accounts, managing banks, and performing operations via a controller.  

## Features  
- Create and manage bank entities  
- Create and manage account entities  
- Perform CRUD operations (Create, Read, Update, Delete)  
- Use of Hibernate for persistence  
- Clear layer separation (DAO layer, entity layer, controller)  

## Technologies Used  
- Language: Java  
- ORM: Hibernate  
- Database: (e.g., MySQL / H2 / any relational DB)  
- Build Tool: (if applicable)  
- IDE: (e.g., Eclipse, IntelliJ)  

## Getting Started  

### Prerequisites  
- JDK 8 or higher  
- [Hibernate](https://hibernate.org/) configured  
- A relational database and JDBC driver  
- (Optional) Maven or Gradle if build tool used  

### Database Setup  
1. Create a database (e.g., `bank_db`) in your relational database server.  
2. Configure Hibernate’s `hibernate.cfg.xml` (or equivalent) with database URL, username, password, dialect, driver.  
3. Ensure entities are mapped correctly.  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/ATULHIRAY/Banking-System.git  

Open the project in your preferred IDE.

Update database configuration as per your environment.

Build the project and run the main controller class (e.g., BMSController.java).

Use the console or GUI (if provided) to interact with the banking system.
![bug](https://github.com/ATULHIRAY/Banking-System/blob/main/Screenshot%202025-11-26%20160219.png?raw=true)
