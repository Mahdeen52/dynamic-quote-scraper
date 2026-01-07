# Dynamic Quote Scraper

This project scrapes quotes from a website and cleans the data for analysis.

## Features

- Scrapes quotes dynamically using Selenium and BeautifulSoup.
- Cleans and processes the data into a CSV file.
- Uses Jupyter Notebook for easy execution and visualization.

## Requirements

- Python 3.13.7
- Jupyter Notebook
- Libraries: selenium, beautifulsoup4, pandas, lxml, webdriver-manager

Install the required libraries with:

```
pip install selenium beautifulsoup4 pandas lxml webdriver-manager
```

## Usage

1. Open the `main.ipynb` file in Jupyter Notebook.
2. Run the cells to scrape and clean the quotes.
3. The cleaned data will be saved as `quotes_scraped_cleaned.csv`.

## Data

- `quotes_scraped_cleaned.csv`: Contains the scraped and cleaned quotes data.

## Notes

Ensure the webdriver is set up correctly for Selenium. The script uses webdriver-manager to handle this automatically.
