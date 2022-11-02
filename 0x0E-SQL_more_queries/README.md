# 0x0E. SQL - More queries

Project on learning the following. 
* How To Create a New User and Grant Permissions in MySQL
* How To Use MySQL GRANT Statement To Grant Privileges To a User
* MySQL constraints
* SQL technique: subqueries
* Basic query operation: the join
* SQL technique: multiple joins and the distinct keyword
* SQL technique: join types
* SQL technique: union and minus
* MySQL Cheat Sheet
* The Seven Types of SQL Joins
* MySQL Tutorial
* SQL Style Guide
* MySQL 8.0 SQL Statement Syntax

## Learning Objectives :house:
### General

* How to create a new MySQL user
* How to manage privileges for a user to a database or table
* What’s a PRIMARY KEY
* What’s a FOREIGN KEY
* How to use NOT NULL and UNIQUE constraints
* How to retrieve datas from multiple tables in one request
* What are subqueries
* What are JOIN and UNION

## Requirements :page_with_curl:

* Allowed editors: vi, vim, emacs
* All your files will be executed on Ubuntu 20.04 LTS using MySQL 8.0 (version 8.0.25)
* All your files should end with a new line
* All your SQL queries should have a comment just before (i.e. syntax above)
* All your files should start by a comment describing the task
* All SQL keywords should be in uppercase (SELECT, WHERE…)
* A README.md file, at the root of the folder of the project, is mandatory
* The length of your files will be tested using wc

## Task :heavy_check_mark:

All the following are the tasks with the files and description.

| Filename | Description |
| -------- | ----------- |
| `0-privileges.sql` | Lists all privileges of the MySQL users `user_0d_1` and `user_0d_2` on your server. |
| `1-create_user.sql` | Creates the MySQL server user `user_0d_1` |
| `2-create_read_user.sql` | Creates the database `hbtn_0d_2` and the user `user_0d_2` |
| `3-force_name.sql` | Creates the table `force_name` on your MySQL server |
| `4-never_empty.sql` | Creates the table `id_not_null` on your MySQL serve |
| `5-unique_id.sql` | Creates the table `unique_id` on your MySQL server |
| `6-states.sql` | Creates the database `hbtn_0d_usa` and the table `states` (in the database `hbtn_0d_usa`) |
| `7-cities.sql` | Creates the database `hbtn_0d_usa` and the table `cities` (in the database `hbtn_0d_usa`) |
| `8-cities_of_california_subquery.sql` | Lists all the cities of California that can be found in the database `hbtn_0d_usa` |
| `9-cities_by_state_join.sql` | Lists all cities contained in the database `hbtn_0d_usa` |
| `10-genre_id_by_show.sql` | Lists all shows contained in `hbtn_0d_tvshows` that have at least one genre linked |
| `11-genre_id_all_shows.sql` | Lists all shows contained in the database `hbtn_0d_tvshows` |
| `12-no_genre.sql` | Lists all shows contained in `hbtn_0d_tvshows` without a genre linked |
| `13-count_shows_by_genre.sql` | Lists all genres from `hbtn_0d_tvshows` and displays the number of shows linked to each |
| `14-my_genres.sql` | Uses the `hbtn_0d_tvshows` database to lists all genres of the show `Dexter` |
| `15-comedy_only.sql` | Lists all Comedy shows in the database `hbtn_0d_tvshows` |
| `16-shows_by_genre.sql` | Lists all shows, and all genres linked to that show, from the database `hbtn_0d_tvshows` |
| `100-not_my_genres.sql` | Uses the `hbtn_0d_tvshows` database to list all genres not linked to the show `Dexter` |
| `101-not_a_comedy.sql` | Lists all shows without the genre `Comedy` in the database `hbtn_0d_tvshows` |
| `102-rating_shows.sql` | Lists all shows from `hbtn_0d_tvshows_rate` by their rating |
| `103-rating_genres.sql` | Lists all genres in the database `hbtn_0d_tvshows_rate` by their rating |

## Author
* Dibor Solomon
