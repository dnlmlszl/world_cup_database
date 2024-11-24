# World Cup Database Project

This project is part of the [FreeCodeCamp Relational Database Tutorial](https://www.freecodecamp.org/learn/) and focuses on creating and querying a PostgreSQL database to track World Cup games. The goal is to set up a relational database with two main tables, `teams` and `games`, and write a Bash script to populate these tables with data from a CSV file.

## Project Setup

1. **Database and Table Creation**: Use PostgreSQL to create a `worldcup` database with two tables:
   - `teams`: Stores unique team names.
   - `games`: Stores game details, including the year, round, winner, and opponent.

2. **Script for Data Import**:
   - Write an `insert_data.sh` script to import unique team names and game data from `games.csv`.
   - Ensure that each team is added only once to avoid duplicates.

3. **Queries**:
   - Write SQL queries to retrieve information about teams, games, and statistics, including specific criteria like games played in certain years, teams with specific win records, etc.

## Instructions

1. Clone this repository and navigate to the project folder.
2. Run the SQL setup commands to create the tables.
3. Execute `insert_data.sh` to populate the database.
4. Run the queries provided in `queries.sql` or directly within PostgreSQL to answer specific questions about World Cup games.

## Example Queries

Example queries in this project include:
- Listing teams with one or more wins in the tournament.
- Finding games played in a particular year.
- Displaying teams with a high win-loss ratio.

## Resources

- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [FreeCodeCamp Relational Database Curriculum](https://www.freecodecamp.org/learn/)
