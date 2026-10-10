# Web Scraping and Book Price Analysis

## Project Overview
This project collects book information from the Books to Scrape website, cleans the dataset, analyzes book prices and ratings, and creates visualizations using Python.

## Objectives
- Scrape book titles and prices.
- Collect book ratings and availability.
- Save data in CSV format.
- Clean and analyze the collected data.
- Visualize book price patterns.

## Technologies Used
- Python
- Requests
- Beautiful Soup
- Pandas
- Matplotlib
- Google Colab

## Dataset Columns
- `title`: Book title
- `price_gbp`: Price in British pounds
- `rating`: Rating from 1 to 5
- `availability`: Availability information
- `product_url`: Product page URL

## Project Files
- `web_scraping_book_analysis.ipynb` — Python notebook
- `data/books_dataset.csv` — Raw dataset
- `data/books_cleaned.csv` — Cleaned dataset
- `charts/price_distribution.png` — Price distribution chart
- `charts/price_by_rating.png` — Average price by rating chart
- `requirements.txt` — Required Python libraries

## Data Source
https://books.toscrape.com/

This is a practice website intended for web scraping.

## How to Run
1. Open the notebook in Google Colab.
2. Run the installation cell.
3. Run the scraping and data-cleaning cells.
4. Generate and review the charts.

## Results
The notebook produces a book dataset, a cleaned CSV file, summary statistics, and visualizations.

## Limitations
Results depend on the website content and successful execution of the scraper.

## Purpose
Educational project for learning Python web scraping and data analysis.
