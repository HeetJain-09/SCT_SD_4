# SCT_SD_4
Repository containing software development TASK 4

--------------------

## SkillCraft Technology Internship Task

This project was completed as part of my Software Development Internship at SkillCraft Technology. 

It involves scraping product data from an online bookstore and saving it in a structured CSV format.

-----------------------

## Task 04: E-commerce Product Information Scraper

This Python program extracts product information such as titles, prices, and star ratings from the e-commerce website books.toscrape.com. 

It parses the HTML content of product listing pages using BeautifulSoup and stores the collected data in a CSV file for easy analysis and reference.

-----------------------
## How It Works

- Fetches the product listing pages using requests.

- Parses the page content with BeautifulSoup to locate product elements.

- Extracts the product title, price (converted to a float), and star rating.

- Loops through specified pages to gather comprehensive data.

- Aggregates data into a list and converts it into a pandas DataFrame.

- Saves the final data to books.csv.

-------------------------
## Requirements
- Python 3

- Install required libraries:
pip install requests beautifulsoup4 pandas

## How to Run
- Ensure all dependencies are installed.

- Run the Python script or Jupyter notebook:

python webscrap.py
Or open and execute cells in webscrap.ipynb.

- The program will generate a books.csv file containing the scraped data.

## Output
- The CSV file (books.csv) contains:

    -Title: Name of the book.

    -Price: Price in GBP (converted to float).

    -Star Rating: Textual rating (e.g., "Three", "Five").

