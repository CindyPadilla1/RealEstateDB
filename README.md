# Real Estate Database Project

## Overview
This project is a Real Estate Database application built as part of a coursework assignment.  
It demonstrates how to collect real estate listings via **web scraping**, store them in a **MySQL database**, and interact with the database using **JDBC** in Java.

The goal of this project was to practice database design, data ingestion, and basic backend programming.

## Technologies Used
- Java (JDBC)
- MySQL
- HTML / CSS / JavaScript (for web scraping)
- JSoup (or other library used for web scraping)
- SQL scripts for table creation and sample data

## Project Structure
- `src/` – Java source code, including database connection and scraping logic
- `sql/` – SQL scripts to create tables, insert sample data, or define stored procedures
- `README.md` – project overview and instructions

## Features
- Scrapes real estate listings from a website (or sample site for homework purposes)
- Stores scraped data in a MySQL database
- Queries the database using JDBC
- Implements basic database operations such as insert, update, and select

## Notes
- This is a coursework project; some dependencies may be outdated
- The project was designed for learning and demonstration purposes
- Web scraping respects website limitations; for real deployment, legal and ethical considerations apply

## How to Run (Optional)
1. Install dependencies:
   - MySQL server
   - Java JDK
   - JSoup (or other scraping library)
2. Run the SQL scripts in the `sql/` folder to set up the database
3. Compile and run Java files in the `src/` folder
4. The application will connect to the database and populate it with scraped data

## What I Learned
- Web scraping basics using Java
- JDBC database connectivity and CRUD operations
- Designing and interacting with relational databases
- Handling real-world data and storing it for analysis
