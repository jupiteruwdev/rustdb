# Rdb

Rdb is a relational database implemented in Rust. Unlike databases like PostgreSQL and SQLite, Rdb does not operate on a client-server model. Instead, it is a stand-alone library that allows it to be used with zero dependencies. 

## Features

- Creating databases
- Creating and accessing existing tables
  - Accessing rows from tables
    - By row ID
    - By value (eg: find all rows where foo = bar)
  - Parse specfiles for type safe columns
- Accessing rows
  - Getting columns from rows
  - Setting columns in rows
