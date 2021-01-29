# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) SQL Basics

#### Where In The World Is Carmen Sandiego?

We're going to use what we've already learned about searching with SQL commands and apply it to chase down and capture an elusive and world-renowned thief: Carmen Sandiego. Follow the clues, use the interweb, write down both the SQL commands/queries you used and your answers to the clues, and figure out where Carmen is headed so we can catch her.

## Setup

- Fork and clone this repo.
- Go inside the folder you just cloned
- From the command line, let's create a new database called `carmen` and populate it with the SQL found in `world.sql`.

```sh
# Enter psql
psql

# Create database
CREATE DATABASE carmen;

# Connect to carmen
\c carmen
\i world.sql

# To exit the psql terminal use the command
\q
```
Now your database is ready!!!! good luck detective :shipit: :mag: 

## Exercise

- O the file [find_carmen.sql](find_carmen.sql) use the clues to create the appropriate SQL queries to help you find Carmen. Tell us where she's heading!
- For each clue solved do a commit :wink:
- Create a pull request to submit your work.



