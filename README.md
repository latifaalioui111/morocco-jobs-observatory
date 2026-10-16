# Morocco Jobs Observatory

A data pipeline that scrapes, stores, analyzes and visualizes **DevOps, Cloud and Cybersecurity** job offers in Morocco.

> Work in progress: a learning project built step by step.

## Goals

- Build a complete data pipeline: collection, cleaning, storage, analysis, visualization and a chatbot.
- Understand the Moroccan job market for DevOps, Cloud and Cybersecurity.
- Learn Python, web scraping, SQL, Power BI and Streamlit by building a real project.

## Questions this project answers

- Which domain recruits the most: DevOps, Cloud or Cybersecurity?
- Which cities have the most job offers?
- Which skills and certifications are most requested?
- Which contract types are offered (permanent, internship, freelance...)?

## Pipeline

Job website -> Scraper (Python) -> Raw CSV -> Cleaning (pandas) -> SQLite database -> SQL analysis -> Power BI dashboard + Streamlit chatbot

## Tech stack

- Python (requests, BeautifulSoup, pandas)
- SQLite and SQL
- Power BI
- Streamlit
- Git and GitHub

## Project structure

- `scraper/`: scripts that collect job offers
- `cleaning/`: data cleaning scripts
- `database/`: database creation and loading
- `sql/`: SQL schema and analysis queries
- `app/`: Streamlit chatbot
- `powerbi/`: dashboard file and screenshots
- `data/`: raw, clean and exported data
- `docs/`: diagrams and documentation


## Ethics

The scraper respects each site's `robots.txt` and terms of use, waits between requests, and collects no personal data.


