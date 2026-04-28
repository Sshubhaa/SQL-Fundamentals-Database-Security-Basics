# SQL-Fundamentals-Database-Security-Basics

## About This Project
This project is part of my hands-on cybersecurity learning journey as I transition into the field.

It is based on the SQL Fundamentals lab from TryHackMe, focusing on database structure, querying, and security implications.

## Objectives
- To understand database structure
- Write basic SQL queries

## Tools & Technologies
- SQL
- Relational databases

## Key Concepts Covered
- SELECT statements
- WHERE clauses
- Filtering and sorting data
- Pattern matching using LIKE

## Practical Tasks Performed
- Queried database tables
- Filtered results using conditions
- Extracted specific datasets

## Example Queries
CREATE DATABASE Name;
SHOW DATABASES;
SELECT * FROM users;
SELECT username FROM users WHERE id = 1;
SELECT * FROM products WHERE price > 100;
SELECT * FROM users WHERE username LIKE 'admin%';

## Key Learnings
Databases are a critical target in cyber attacks
Poor query handling can lead to vulnerabilities like SQL injections 
Understanding SQL is essential for both defense and testing

## Challenges Faced
Syntax errors in queries
Improved through repetition and debugging

## Real-World Relevance
Helps understand SQL injection attacks
Important for web security and penetration testing

## Source
TryHackMe SQL Fundamentals lab


  
