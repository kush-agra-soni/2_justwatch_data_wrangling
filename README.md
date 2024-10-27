# 2_justwatch_data_wrangling

This project involves data scraping and wrangling of movie data from JustWatch. It focuses on extracting details of movies released after 2020 with ratings between 7 and 10, organizing the data into a structured dictionary, and exporting it to a CSV file for further analysis.

## Project Overview
Objective: Scrape movie data for titles released after 2020 with ratings from 7 to 10.
Data Source: JustWatch (web scraping)
Output: Dictionary format with all movie details, exported as a CSV file.

## Movie Details Collected
Title
Genre
Release Year
Rating
Cast
Additional Details (e.g., director, runtime, etc.)

## Prerequisites
Python 3.x

## Required Libraries:
requests
BeautifulSoup (for HTML parsing)
pandas (for data organization and CSV export)

Install the libraries:

`
pip install requests beautifulsoup4 pandas
`
## Installation
Clone the repository:
`
git clone https://github.com/yourusername/2_justwatch_data_wrangling.git
cd 2_justwatch_data_wrangling
`

## Usage
Run the Script: Execute the scraping and data wrangling code to collect movie data.
`
python scrape_justwatch.py
`
Export to CSV: The script saves the collected data to movies_data.csv in the project directory.

## License
This project is licensed under the MIT License.
