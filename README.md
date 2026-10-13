# Chicago Socioeconomic & Crime Data Analysis Pipeline

An end-to-end Python and SQL data pipeline that ingests, stores, and analyzes multi-source public datasets from the City of Chicago (Census data, Public Schools progress reports, and Crime statistics) using SQLite and Pandas.

## Project Overview
This project was developed as part of the IBM *Databases and SQL for Data Science with Python* coursework. It demonstrates proficiency in relational database management, data loading, and complex SQL querying to extract meaningful socio-economic insights and safety metrics across Chicago community areas.

## Datasets Used
The analysis integrates three core datasets sourced from the Chicago Data Portal:
1. **Socioeconomic Indicators in Chicago**: Contains community-area public health indicators and hardship indexes (2008–2012).
2. **Chicago Public Schools**: Shows school-level performance data, facility metrics, and safety scores for the 2011–2012 school year.
3. **Chicago Crime Data**: Reflects recorded incidents of crime in Chicago from 2001 to the present.

## Key Features & Technical Tasks
* **Data Ingestion**: Utilized Python (`Pandas`) to read cleaned dataset subsets from cloud storage and load them into relational data frames.
* **Database Setup**: Programmatically established a connection to an SQLite database (`FinalDB.db`) and structured raw data into dedicated tables (`CENSUS_DATA`, `CHICAGO_PUBLIC_SCHOOLS`, `CHICAGO_CRIME_DATA`).
* **Advanced SQL Querying**: Executed complex SQL queries leveraging:
  * Aggregate functions and grouping (`SUM`, `AVG`, `COUNT`).
  * Multi-table `JOIN` operations to correlate crime rates with community socioeconomics.
  * Sub-queries and database views to isolate peak crime-prone areas and highest hardship indices.

## Tech Stack
* **Language**: Python
* **Libraries**: Pandas, SQLite3, Prettytable
* **Database**: SQLite (`FinalDB.db`)
* **Environment**: Jupyter Notebook

## Author
**Nsreen Nashaat Abdo**
