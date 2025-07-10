# PhonePe Transaction Insights

## Overview
This project analyzes PhonePe transaction data to explore user trends, payment categories, insurance data, and geographical patterns.  
It combines Python (scripts & notebooks), PostgreSQL for data storage and querying, and Streamlit for building an interactive dashboard.

## What I Used
- Python (.py scripts and .ipynb notebooks)
- Streamlit (for dashboard)
- PostgreSQL (for storing and querying data)
- Git (for version control)

## Project Features
- Store and manage data using PostgreSQL
- Use SQL queries to extract and analyze data
- Visualize data trends with Python (charts and maps)
- Build an interactive Streamlit dashboard to explore insights

## About
This project helps to understand transaction patterns, top states/districts, insurance trends, and provides business insights for better decision-making.

## Prepare the dataset

- [PhonePe Pulse Dataset](https://github.com/PhonePe/pulse)


- Download the JSON data files you need and place them into your project folder (e.g., data/)

## Set up PostgreSQL

- Install and run PostgreSQL

- Create a database (e.g., phonepe_pulse)

- Update connection details in your Python scripts

## Load data
- Run your ETL scripts to parse JSON and populate PostgreSQL tables.

## Launch the dashboard
- streamlit run phonepe_dashboard.py

## What You Can Explore
- Payment trends by state, district, and pin code

- Top states/districts and transaction categories

- Insurance transactions and user metrics

- Interactive dashboard with charts, maps, and filters
