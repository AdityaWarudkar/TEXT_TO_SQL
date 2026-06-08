# Text-to-SQL Query Generator

A Text-to-SQL project that converts natural language questions into SQL queries, allowing users to interact with databases using simple English commands. This project is designed to make database querying easier for non-technical users by automatically generating SQL statements from user input.

## Project Overview

The Text-to-SQL Query Generator takes a natural language query such as:

```text
Show all customers from Sao Paulo
```

and converts it into an SQL query like:

```sql
SELECT * FROM customers WHERE city = 'Sao Paulo';
```

The project helps users retrieve information from structured databases without manually writing SQL queries.

## Features

* Converts natural language input into SQL queries
* Supports user-friendly database searching
* Handles common query patterns such as filtering, selection, and conditional search
* Useful for business users, analysts, and non-technical teams
* Can be extended with AI/LLM-based query generation
* Helps reduce dependency on manual SQL writing

## Tech Stack

* Python
* SQL
* SQLite / MySQL / PostgreSQL
* Natural Language Processing
* Streamlit / Flask / FastAPI
* Pandas

## How It Works

1. User enters a question in natural language.
2. The system understands the intent of the query.
3. The input is converted into a valid SQL query.
4. The SQL query is executed on the database.
5. The result is displayed to the user in a readable format.

## Example Queries

```text
Show all customers from Mumbai
```

```sql
SELECT * FROM customers WHERE city = 'Mumbai';
```

```text
Find the total sales in 2024
```

```sql
SELECT SUM(sales) FROM orders WHERE year = 2024;
```

```text
List employees with salary greater than 50000
```

```sql
SELECT * FROM employees WHERE salary > 50000;
```

## Use Cases

* Business data analysis
* Customer database search
* Sales and revenue reporting
* Internal company dashboards
* Non-technical database querying
* Quick SQL query generation

## Future Improvements

* Add support for complex joins
* Improve query accuracy using LLMs
* Add authentication for users
* Support multiple database connections
* Add query history
* Add visualization for query results
* Improve error handling for invalid questions

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/text-to-sql.git
```

Go to the project folder:

```bash
cd text-to-sql
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the project:

```bash
python app.py
```

or, if using Streamlit:

```bash
streamlit run app.py
```

## Author

**Aditya Warudkar**

GitHub: [AdityaWarudkar](https://github.com/AdityaWarudkar)

## License

This project is open-source and available for learning and development purposes.
