# WorldCup Database

![](WorldCup.jpeg)

## Project Goal
Create a Bash script that enters information from World Cup games.csv file into PostgreSQL, then query the database for useful statistics.

:copyright: [freeCodeCamp](https://www.freecodecamp.org/learn/relational-database/) Relational Database Course

## Instructions
You need to do three things for this project: <br/>
Part 1: Create the database <br/>
- Create database `worldcup`, and tables `teams` and `games` on PostgreSQL.
- Add appropriate constraints `primary` and `foreign` keys required to relate two tables.
  ![Tables Diagram](ERD.png)

Part 2: Insert the data <br/>
- Complete the `insert_data.sh` script to correctly insert all the data from `games.csv` into the database.

Part 3: Query the database <br/>
Complete the empty echo commands in the `queries.sh` file to produce output that matches the `expected_output.txt` file.

## Data Files
[games.csv](games.csv) <br/>
[insert_data.sh](insert_data.sh) <br/>
[expected_output.txt](expected_output.txt) <br/>





