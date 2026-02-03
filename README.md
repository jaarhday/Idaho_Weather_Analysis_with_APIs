# Weather API Challenge

## Overview

**you may need to download the HTML file to view the project**

This project demonstrates an end-to-end data ingestion and analysis workflow using real-world weather data. The goal is to collect geographic data for cities in Idaho, retrieve historical and forecast weather data from a public API, and process the results into a structured format suitable for analysis.

The project emphasizes API usage, data wrangling, and scalable data processing techniques commonly used in data engineering and analytics roles.

## Features

* Web scraping to collect city and geographic data
* Integration with the Open-Meteo Weather API (JSON responses)
* Retrieval of multi-year historical and forecast weather data
* Data transformation and cleaning using Python
* Storage and analysis using Spark DataFrames
* Exploratory analysis and basic visualization

## Technologies Used

* Python
* Databricks
* Open-Meteo Weather API
* Requests
* Pandas / Polars
* Apache Spark
* Jupyter Notebook


## Data Pipeline

1. Scrape city and location data for Idaho cities
2. Query the Open-Meteo API for weather data using latitude and longitude
3. Parse and normalize JSON responses
4. Load processed data into Spark DataFrames
5. Perform analysis and generate visualizations

## Purpose

This project was completed as a technical challenge to demonstrate practical skills in API consumption, data processing, and working with large datasets. It reflects real-world tasks common in data engineering, analytics, and machine learning workflows.

## Author

Alec Day
