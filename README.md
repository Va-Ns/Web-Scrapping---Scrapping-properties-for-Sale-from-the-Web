Web Scrapping - Scraping Properties for Sale from the Web
=========================================================

Description:
-------------
This repository contains code and data for scraping real estate property listings from the web, 
specifically focused on properties for sale in Rock Springs, WY and other locations. 
The project demonstrates how to use Python and BeautifulSoup to extract property data 
from HTML pages and store it in a CSV file.

Contents:
----------
1. Web Scrapping.ipynb
   - A Jupyter Notebook containing Python code for web scraping using requests and BeautifulSoup.
   - Includes code to fetch, parse, and display real estate listings from online sources.

2. real_estate.csv
   - A CSV file containing sample real estate property data.
   - Columns include price, address, city/state/zip, number of bedrooms, bathrooms, square footage, and additional features.

3. .gitattributes
   - Git configuration file for handling line endings and text file normalization.

Usage:
-------
- Open `Web Scrapping.ipynb` in Jupyter Notebook or Visual Studio Code to view and run the scraping code.
- The notebook demonstrates how to fetch HTML content, parse it, and extract relevant property information.
- The extracted data can be saved or compared with the sample data in `real_estate.csv`.

Requirements:
--------------
- Python 3.x
- requests
- beautifulsoup4
- Jupyter Notebook (for running the .ipynb file)

How to Run:
------------
1. Install required Python packages:
   pip install requests beautifulsoup4

2. Open the notebook:
   jupyter notebook Web\ Scrapping.ipynb

3. Run the cells to perform web scraping and view the results.
