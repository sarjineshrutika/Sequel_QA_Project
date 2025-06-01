                                     --* Sequel_QA_Project *--
 * Project Overview
This project integrates deep learning with SQL databases to build an intelligent question-answering system. It uses a state-of-the-art language model to understand natural language questions, generates SQL queries automatically, executes them on a MySQL database, and returns concise answers.

* Features
-- Natural language to SQL query generation using deep learning (Groq Gemma2-9b-it model)

-- Automated SQL query execution on a MySQL sales database

-- Clear, concise natural language answers based on query results

-- Modular and extensible code using LangChain framework

* Technologies Used
-- Python

-- Groq API (Gemma2-9b-it deep learning model)

-- LangChain

-- SQLAlchemy

-- PyMySQL

-- MySQL database

* How It Works
-- User inputs a natural language question.

-- The deep learning model interprets the question and generates a corresponding SQL query.

-- The SQL query is executed against the MySQL database.

-- The query result is processed, and a natural language answer is generated.

* Explanation of Key Libraries
-- SQLAlchemy: Simplifies database communication by managing connections and queries in Python.

-- PyMySQL: Acts as the connector between Python and MySQL, allowing Python to send SQL commands to the database.
