# SQL Learning & Examples

This repository contains a collection of SQL scripts and examples covering various SQL concepts, commands, and features. It's intended as a personal reference and learning resource for database management and SQL programming.

## Table of Contents

- [About](#about)
- [Contents](#contents)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## About

This collection serves as a practical guide to understanding and utilizing SQL for database operations, data manipulation, and advanced programming concepts. Each folder or file aims to demonstrate specific SQL functionalities.

## Contents

This repository includes examples and scripts related to:

* *Database Objects & DDL (Data Definition Language):*
    * create_alter_truncate (CREATE, ALTER, TRUNCATE statements for tables, etc.)
    * views (Creating and managing views)
* *Data Manipulation Language (DML):*
    * insert_select_update_delete (INSERT, SELECT, UPDATE, DELETE statements)
* *Constraints:*
    * constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, CHECK, DEFAULT constraints)
    * foreignkey (Specific examples for foreign key relationships)
* *Joins:*
    * joins (INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN examples)
* *Functions & Operators:*
    * builtin_numeric (Built-in numeric functions)
    * function (User-defined functions, if any, or general function usage)
    * functions (More examples of functions)
    * operators (Arithmetic, comparison, logical, and other operators)
    * string (String functions and operations)
    * string_date (String and date/time functions)
* *Grouping & Aggregation:*
    * group by (GROUP BY clause with aggregate functions like COUNT, SUM, AVG, MIN, MAX)
* *Transactions:*
    * commit_savepoint_rollback (Examples of COMMIT, SAVEPOINT, ROLLBACK)
* *Control Flow & Advanced Concepts:*
    * cursors (Using cursors for row-by-row processing)
    * plsql1 (Likely examples of PL/SQL, Oracle's procedural extension for SQL)
* *Specific SQL Dialects/Versions:*
    * sql2 (Possibly SQL-92 standard or specific version examples)
    * sql3 (Possibly SQL-99 standard or specific version examples)

## How to Use

To utilize these SQL scripts:

1.  *Clone the repository:*
    bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    
2.  *Choose a SQL file:* Navigate to the specific .sql file you want to explore.
3.  *Execute the script:*
    * Open your preferred SQL client (e.g., MySQL Workbench, pgAdmin, SQL Server Management Studio, Oracle SQL Developer, DBFiddle, etc.).
    * Connect to a database.
    * Open and execute the SQL script. Ensure you understand the potential impact (e.g., data modification) before running on critical databases.
    * You might need to create a sample database and tables first, as defined in some of the scripts, to run the examples successfully.

## Contributing

If you have suggestions for improvements, find issues, or would like to add more SQL examples, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
