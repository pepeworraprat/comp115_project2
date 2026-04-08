# BC Housing Affordability and Rental Subsidies Analysis

## Description
This Python project analyzes BC Census 2016 housing data to explore housing affordability and rental subsidization patterns across British Columbia.

The program identifies CHSA areas where more than 50% of renters spend 30% or more of their income on shelter costs and compares rental subsidization rates across the five PHA regions.

It also calculates averages, ranks the most unaffordable areas, and creates bar charts for visualization.

## Features
- Reads housing data from a CSV file
- Identifies high housing-cost burden areas
- Sorts areas from highest to lowest burden
- Displays the top 5 most unaffordable areas
- Calculates average rent, income, and subsidization rates
- Compares subsidization across PHA regions
- Generates bar charts using matplotlib

## Dataset
File used:
`BC Census 2016 data.csv.`

Includes:
- CHSA area
- PHA region
- Subsidized rental rate
- % of renters spending 30%+ income on shelter
- Rent costs (mean & median)
- Income (mean & median)

## Requirements
- Python 3
- matplotlib

# How to Install
1. Make sure Python 3 is installed
2. Install matplotlib (pip3 install matplotlib in terminal)
3. Put the "BC Census 2016 data.csv" file in the same folder as python file
4. Run

# Output 
The program prints:
	•	Dataset overview
	•	Task 1 analysis (high-burden areas)
	•	Top 5 most unaffordable areas
	•	Task 2 comparison of PHA regions
	•	Bar chart (subsidized rates by region, 30%+ shelter cost rates by region)


## Authors 
Worraprat Wuttisan and Caroline Wong
  
