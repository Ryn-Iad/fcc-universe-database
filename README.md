# 🌌 Celestial Bodies Database

A PostgreSQL relational database modeling the universe, built as part of the freeCodeCamp Relational Database Certification.

## Technologies
- PostgreSQL 12
- Git / GitHub

## Database Structure
Galaxy → Star → Planet → Moon → Comet

## How to Run
1. Clone the repository
2. Restore the database
```bash
   psql -U postgres < universe.sql
```
3. Connect
```bash
   psql --username=freecodecamp --dbname=universe
```
