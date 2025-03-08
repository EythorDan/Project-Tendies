# Project-Tendies
T.E.N.D.I.E.S.: "Trading Engine for Neural-Driven Intelligent Equity Strategies"

Agent 1: Architect 


Agent 2: Analyst


Agent 3: Dave


Agent 4: Nostradamus



The database built on:



## 📂 Folder Structure

```
stock-analysis-project/
│── data/                   # Stores raw and processed data
│   ├── raw/                # Raw API responses (optional)
│   ├── processed/          # Processed data files (optional)
│── notebooks/              # Jupyter notebooks for prototyping & visualization
│── database/               # Database-related files
│   ├── migrations/         # Database schema migration scripts (if using Alembic)
│   ├── schema.sql          # SQL schema for initial setup
│   ├── seed_data.sql       # Sample seed data for testing
│   ├── db_config.py        # Database connection settings
│   ├── models.py           # ORM models (SQLAlchemy)
│   ├── queries.py          # SQL queries & functions
│   ├── db_utils.py         # Helper functions for database interaction
│── src/                    # Source code
│   ├── config/             # Configuration files (e.g., API keys, DB settings)
│   │   ├── config.py       # Configuration settings
│   │   ├── settings.py     # Environment settings loader
│   ├── data/               # Data retrieval and processing
│   │   ├── fetch_data.py   # API calls to Yahoo Finance & Polygon.io
│   │   ├── preprocess.py   # Data cleaning and structuring
│   ├── analysis/           # Stock analysis logic
│   │   ├── indicators.py   # Technical indicators (RSI, MACD)
│   │   ├── strategies.py   # Trading strategies
│   │   ├── backtesting.py  # Backtesting engine
│   ├── visualization/      # Visualization scripts
│   │   ├── charts.py       # Candlestick charts, trends, etc.
│   ├── utils/              # Utility functions
│   │   ├── helpers.py      # General helper functions
│   ├── main.py             # Entry point of the application
│── tests/                  # Unit tests
│   ├── test_fetch_data.py  # Tests for API fetch module
│   ├── test_db.py          # Tests for database interactions
│── requirements.txt        # List of dependencies
│── README.md               # Project documentation
│── .env                    # Environment variables (e.g., API keys, DB settings)
│── .gitignore              # Ignore unnecessary files (e.g., .env, __pycache__)
│── docker-compose.yml      # Optional: Docker configuration for PostgreSQL
│── alembic.ini             # Optional: Alembic migration config (if using)
```