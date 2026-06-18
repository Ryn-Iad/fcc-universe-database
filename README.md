# 🌌 Celestial Bodies Database

A PostgreSQL relational database modeling the universe, built as part of the freeCodeCamp Relational Database Certification.

## Technologies
- PostgreSQL 12
- Git / GitHub

## Database Structure
Galaxy → Star → Planet → Moon → Comet

## How to Run
1. Clone the repository
```bash
   git clone https://github.com/Ryn-Iad/fcc-universe-database.git
```

2. Restore the database
```bash
   psql -U postgres < universe.sql
```

3. Connect to the database
```bash
   psql --username=freecodecamp --dbname=universe
```
