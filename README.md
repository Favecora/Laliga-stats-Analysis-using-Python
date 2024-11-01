
# La Liga Stats Analysis (2019/2020 - 2023/2024 Seasons)

This repository contains Python code for data analysis of La Liga standings data from the 2019/2020 season through the 2023/2024 season. It includes code for both the analysis of the dataset and the web scraping script used to gather the data from the source website.

## Project Overview

The primary goal of this project is to analyze team performance trends across multiple La Liga seasons. Key insights derived include team ranking changes, win-loss statistics, goal differentials, and other performance metrics.

## Repository Contents

- **`Laliga_Stats_Eda.ipynb`**: A Jupyter Notebook containing Python code for loading, cleaning, merging, and analyzing La Liga data across seasons.
- **`Web_scraping2.ipynb`**: Python code used to scrape data from the source website to gather seasonal standings data.


## Data Analysis Process

1. **Data Collection**: Using `web_scraping_script.py`, data was collected from the specified source website.
2. **Data Cleaning & Merging**: Datasets for each season were cleaned, standardized, and merged into one comprehensive file, `merged_laliga_standings.csv`.
3. **Analysis**: Various analyses were conducted to identify trends in team performances, rank changes, and goal statistics over the seasons.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  - `pandas`
  - `numpy`
  - `requests`
  - `BeautifulSoup` (for web scraping)
  - `matplotlib` and `seaborn` (optional, for data visualization)

Install these libraries using:

pip install pandas numpy requests beautifulsoup4 matplotlib seaborn


### Usage

1. Run `WebScraping2.ipynb` to scrape the data.
2. Use `Laliga_stats_Eda.ipynb` to load, clean, and analyze the data.



## Acknowledgments

Special thanks to the data source for providing publicly accessible data, which enabled the completion of this project.
