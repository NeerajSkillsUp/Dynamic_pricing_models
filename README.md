# Dynamic Parking Pricing Simulation

## Overview

This project implements dynamic pricing models for parking lots based on real-time demand and competition. It simulates three different pricing strategies to optimize parking revenue while maintaining customer satisfaction.

## Tech Stack

1. Python 3
2. Pandas (Data manipulation)
3. NumPy (Numerical operations)
4. Bokeh (Interactive visualizations)
5. Pathway (Data processing)
6. Google Colab Notebook (Development environment)

![architecture_diagram](https://github.com/user-attachments/assets/4b6b9a21-97a0-4101-b14b-b85e15c77527)

## Project Architecture and Workflow

  1. Data Ingestion:
    -Load parking occupancy data from CSV files
    -Parse timestamps and clean data
  
  2. Pricing Models:
    -Model 1: Basic linear pricing based on occupancy rate
    -Model 2: Advanced demand-based pricing considering multiple factors:
      Current occupancy
      Queue length
      Traffic conditions
      Special events
      Vehicle type
    -Model 3: Competitive pricing that considers nearby parking lots' prices and availability
  
  3. Simulation:
    -Run all three models on historical data
    -Generate comparative pricing over time
    -Analyze price vs occupancy relationships

  4. Visualization:
    -Interactive time series plots showing all models' prices
    -Scatter plots showing price vs occupancy rate
    -Hover tools for detailed inspection

## Key Features

  1. Realistic simulation of dynamic parking pricing
  2. Multiple pricing strategies for comparison
  3. Interactive visualizations for analysis
  4. Configurable parameters for each model
  5. Geographic consideration in competitive pricing

## Usage

  1. Install dependencies: pip install pathway bokeh pandas numpy
  2. Run the colab notebook: colab notebook CapstoneProject.ipynb
  3. Modify the parking lot ID to analyze different locations
  4. Adjust model parameters in the configuration sections

## Results Interpretation

The visualizations show:
  1. How each model responds to changing demand
  2. Price sensitivity to different factors
  3. Competitive positioning relative to nearby lots
  4. Occupancy-rate relationships

## Conclusion :- 
The competitive model (Model 3) provides the most balanced approach, considering both demand and market conditions.

