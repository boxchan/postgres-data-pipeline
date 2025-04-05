# Postgres Data Pipeline

This project sets up a basic ELT pipeline using Docker, Python, and PostgreSQL.

## Components

- Docker Compose
- Source PostgreSQL
- Destination PostgreSQL
- Python script to handle data dump and load

## How to Run

1. Start containers:
   ```
   docker-compose up
   ```

2. Run the ELT script:
   ```
   python elt/your_script.py
   ```

