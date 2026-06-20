# CodeAlpha Web Scraping Project

## Overview

This project was developed as part of the CodeAlpha Data Analytics Internship.

The objective of this project is to collect book data from the Books to Scrape website using Python web scraping techniques and store the extracted information in a structured CSV format for further analysis.

## Project Objectives

* Extract data from a website using Python.
* Parse HTML content using BeautifulSoup.
* Store collected data in a structured dataset.
* Prepare data for exploratory data analysis and visualization.

## Technologies Used

* Python
* Requests
* BeautifulSoup
* Pandas
* Jupyter Notebook

## Dataset Information

The dataset contains information about books available on the Books to Scrape website.

Extracted attributes:

* Book Title
* Price
* Availability Status

Total Records Collected:

* Approximately 1000 books
* 50 pages scraped automatically

## Project Workflow

### Step 1: Data Collection

* Sent HTTP requests to website pages.
* Retrieved HTML content.

### Step 2: Data Extraction

* Parsed HTML using BeautifulSoup.
* Extracted title, price, and availability information.

### Step 3: Data Storage

* Converted extracted data into a Pandas DataFrame.
* Exported the dataset to CSV format.

## Files Included

* WebScraping.ipynb — Jupyter Notebook containing the complete source code.
* books_1000.csv — Scraped dataset.
* README.md — Project documentation.

## Sample Output

| Title                | Price | Availability |
| -------------------- | ----- | ------------ |
| A Light in the Attic | 51.77 | In stock     |
| Tipping the Velvet   | 53.74 | In stock     |

## Learning Outcomes

Through this project, I learned:

* Web Scraping fundamentals
* HTML parsing using BeautifulSoup
* Data collection automation
* Data cleaning using Pandas
* Exporting structured datasets

## Future Enhancements

* Scrape additional book information such as ratings and categories.
* Build interactive dashboards.
* Perform Exploratory Data Analysis (EDA).
* Create advanced visualizations.

## Author

Developed as part of the CodeAlpha Data Analytics Internship Program.
# CodeAlpha_WebScraping
