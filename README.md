# Celestial Bodies Database

## Description
This project is a relational database built using PostgreSQL. It was created as part of the freeCodeCamp Relational Database certification. The database models a universe consisting of galaxies, stars, planets, moons, and asteroids, utilizing strict primary and foreign key relationships, specific data types, and table constraints.

## Technologies Used
* PostgreSQL
* SQL
* Bash / Command Line

## Database Structure
The `universe` database contains 5 interconnected tables:
* `galaxy`: Contains information about various galaxies.
* `star`: Contains stars, referencing the galaxy they belong to.
* `planet`: Contains planets, referencing their host star.
* `moon`: Contains moons, referencing the planet they orbit.
* `asteroid`: Contains a standalone list of notable asteroids.

## How to Rebuild the Database
To rebuild this database locally, ensure you have PostgreSQL installed, then run the following command in your terminal:

```bash
psql -U postgres < universe.sql