# Airbnb Market Trends

## Overview

This project analyzes Airbnb listing data from New York as part of a DataCamp
data analysis project.

The objective is to investigate the short-term rental market, with a particular
focus on private room listings.

## Questions

The analysis answers four questions:

1. What are the earliest and most recent review dates?
2. How many listings are private rooms?
3. What is the average listing price for all rooms?
4. How can these results be combined into a single tibble?

## Data

The project uses three datasets:

- `airbnb_price.csv` — Airbnb listing prices
- `airbnb_room_type.xlsx` — Airbnb room types
- `airbnb_last_review.tsv` — Airbnb review dates

## Tools

- Importing and Cleaning Data in R
- Tidyverse
- dplyr

## Results

The final results are stored in a one-row tibble called `review_dates` with
the following columns:

- `first_reviewed`
- `last_reviewed`
- `nb_private_rooms`
- `avg_price`

## Key Insights

- **Review Timeline:** Analyzed reviews ranging from early 2019 to mid-2019.
- **Private Room Demand:** Identified over 11,000+ private room listings across NYC neighborhoods.
- **Average Market Price:** Derived the baseline nightly listing price ($141.78) after accounting for pricing skewness and outliers.