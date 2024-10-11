# World Cup Database Analysis

This project is a comprehensive database setup and analysis tool for World Cup data using PostgreSQL. The scripts and SQL files included in this repository allow users to set up a database, populate it with historical World Cup data, and run a series of queries to gain insights into matches, teams, and performance statistics.

## Features

- **Database Setup**: Creates a PostgreSQL database named `worldcup`, with tables for storing game and team data.
- **Data Insertion**: Bash scripts automate the process of reading and inserting data from a CSV file into the database.
- **Data Analysis**: SQL queries and Bash scripts provide insights into World Cup statistics, including:
  - Total goals scored by winning teams
  - Average goals per game
  - Champions of different years
  - Unique teams that participated
- **Bash Automation**: Use of conditional logic in Bash to handle team insertion and game population efficiently.

## Prerequisites

- **PostgreSQL**: Ensure PostgreSQL (version 12.9 or compatible) is installed.
- **Bash Shell**: Scripts are designed for Unix-based systems.
