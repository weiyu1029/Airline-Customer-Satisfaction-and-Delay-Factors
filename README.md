# Airline Data Analysis

This repository contains a Python project that analyzes airline data to explore factors affecting customer satisfaction and flight delays. The analysis includes data wrangling, correlation analysis, custom functions, and visualizations. The project was built to demonstrate proficiency in data handling, function creation, and visualization.

## Project Overview

In this project, we analyze synthetic airline data to identify relationships between flight delays and customer satisfaction. The analysis covers:

- Data ingestion from CSV
- Management of different data types
- Custom functions for correlation and average delay calculations
- Visualization of delays by airline and satisfaction level
- Data wrangling to classify flight durations

## Repository Contents

- **airline_analysis.py**: Main script containing the Python code for data analysis and visualization.
- **airline_data.csv**: Synthetic dataset generated for this project, including fields such as `FlightID`, `DepartureDelay`, `ArrivalDelay`, `CustomerSatisfaction`, and more.
- **Output Visualizations**: Charts and visualizations generated by the analysis script (optional, if saved separately).
- **README.md**: Project documentation.

## Dataset

The dataset used in this analysis, `airline_data.csv`, includes the following columns:

- `FlightID`: Unique identifier for each flight.
- `DepartureDelay`: Delay in minutes at departure.
- `ArrivalDelay`: Delay in minutes upon arrival.
- `CustomerSatisfaction`: Customer satisfaction rating from 1 (lowest) to 5 (highest).
- `FlightDuration`: Total flight duration in minutes.
- `Airline`: Name of the airline.
- `Destination`: Destination city for the flight.
- `FlightDate`: Date of the flight.

This data is used to analyze the relationship between delays and customer satisfaction, as well as to compare performance across airlines.

## Code Structure

The analysis script covers the following steps:

1. **Importing Libraries**: Imports necessary libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn`.
2. **Data Ingestion**: Loads data from the CSV file (`airline_data.csv`).
3. **Data Type Management**: Converts columns to appropriate data types, including datetime and categorical.
4. **Custom Analysis Functions**: Defines functions to analyze correlation between delays and satisfaction, and to calculate average delays by airline and flight duration.
5. **Data Visualization**: Creates visualizations for delay analysis across airlines and customer satisfaction levels.
6. **Data Wrangling**: Cleans and processes data, creating a new column to classify flights based on duration.
7. **Output Generation**: Displays correlation results, summary tables, and plots.

## Example Usage

To run the analysis, ensure you have Python installed along with the required libraries. Install dependencies (e.g., using pip) as follows:

```bash
pip install pandas numpy matplotlib seaborn scipy