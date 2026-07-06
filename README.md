One important caveat: there is no single universal list of “all SQL functions” because SQL differs by database engine (for example MySQL, PostgreSQL, MS SQL Server, SQLite, Oracle Database, Google BigQuery,  Snowflake, all implement slightly different functions).
Examples:
•	STRFTIME() → common in SQLite
•	DATE_TRUNC() → common in PostgreSQL / Snowflake / BigQuery
•	FORMAT() → common in SQL Server
•	NVL() → common in Oracle
•	IFNULL() → common in MySQL

So instead of listing vendor-specific duplicates, here is the comprehensive master framework of SQL functions used across most SQL systems.
