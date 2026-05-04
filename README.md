# Toronto Rental Market Analysis

An exploratory data analysis project to identify the best Toronto neighbourhoods for residential rental investment, based on proximity to schools, universities, and public transit.

## Project Overview

This project was completed as part of the **IBM Data Science Professional Certificate** capstone. The goal was to help a hypothetical real estate investor narrow down Toronto neighbourhoods using data-driven clustering techniques.

## What's in this repo

| File | Description |
|------|-------------|
| `toronto_rental_analysis.ipynb` | Main analysis notebook — data collection, cleaning, feature engineering |
| `foursquare_api_exploration.ipynb` | Foursquare API calls to retrieve nearby venues per neighbourhood |
| `toronto_rental_analysis_report.pdf` | Final project report with methodology and results |

## Approach

- Scraped Toronto neighbourhood data from Wikipedia
- Retrieved nearby venue data using the Foursquare API
- Built scoring features: education access and transit accessibility
- Applied **k-Means clustering** (k=4, identified via elbow method) to group neighbourhoods
- Visualized clusters on an interactive Folium map

## Key Finding

**Cluster 3** neighbourhoods (e.g. Woburn, Parkwoods) offer the best combination of educational institutions and transit access — making them the top recommendation for rental investment.
