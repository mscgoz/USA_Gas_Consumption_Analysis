# Natural Gas Consumption Analysis of United States of America

## 1. Introduction

This project explores detailed analysis of natural gas usage trends across U.S. states and consumption types. It may help energy analysts, policy makers, and utility planners understand:

- Seasonal demand shifts
- Sectoral comparison (e.g., residential vs commercial use)

The data includes:
- A total of **37,994 natural gas consumption records**
- Data is collected between 2014 and 2024

This dataset offers a robust foundation for analyzing trends in natural gas consumption in US over time.

## 2. Data Dictionary


| Column               | Example Value                                  | Description                                           |
| -------------------- | ---------------------------------------------- | ----------------------------------------------------- |
| `year`               | 2014                                           | Calendar year of measurement                          |
| `month`              | 1                                              | Month of the year                                     |
| `duoarea`            | SFL                                            | State abbreviation (custom-coded by EIA)              |
| `area-name`          | FLORIDA                                        | Full state name                                       |
| `product`            | EPG0                                           | Energy product (EPG0 = Natural Gas)                   |
| `product-name`       | Natural Gas                                    | Full name of the product                              |
| `process`            | VCS                                            | Process code (e.g. VCS = commercial consumption)      |
| `process-name`       | Commercial Consumption                         | Description of the consumption process                |
| `series`             | N3020FL2                                       | EIA’s internal series ID for data lineage             |
| `series-description` | Natural Gas Deliveries to Commercial Consumers | Full description of the time series                   |
| `value`              | 6605.0                                         | Volume of gas consumed (in MMCF – million cubic feet) |
| `units`              | MMCF                                           | Unit of measurement (Million Cubic Feet)              |



## 3. Source

- **Dataset**: Main dataset provided by [eia.gov]((https://www.eia.gov/)) is used strictly for educational purposes

This dataset was originally compiled by [@aking526](https://github.com/aking526) who:

1. Queried the relevant API between January 2014 and January 2024  
2. Converted the retrieved JSON data into annual CSV files  
3. Merged all years into a single CSV file  
4. Cleaned and adjusted some columns for usability

I am using the processed dataset as a base for exploratory analysis. Full credit to the original compiler. 🙏  

- **Resource**: King, A. (2024). *Natural gas usage (2014–2024)* [Data set]. Kaggle. U.S. Energy Information Administration (original source). https://www.kaggle.com/datasets/alistairking/natural-gas-usage/data


