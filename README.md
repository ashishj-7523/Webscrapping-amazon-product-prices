# Amazon Product Price Extraction using Selenium

## Overview

This mini project demonstrates how to extract product prices from Amazon using Selenium for web scraping. The script navigates to the Amazon website, searches for a specific product, and collects the prices of the listed products on the search results page. If a product price is not available, it captures an alternate piece of information (such as availability status) to ensure complete data collection.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- Selenium
- Google Chrome
- ChromeDriver
- pandas

## Setup

1. **Install Python Packages**

   Install the required Python packages using pip:

   ```bash
   pip install selenium pandas

2. **Download ChromeDriver**

   Download the ChromeDriver that matches your version of Google Chrome from here and place it in a directory included in your system's PATH.

## Script Description
#### The script performs the following steps:

- Initialize WebDriver: Set up Selenium WebDriver for Chrome.
- Open Amazon and Search for a Product: Navigate to Amazon's website and perform a search for a specified product.
- Extract Product Prices: Scrape the prices of products listed on the search results page. If a price is not available, capture an alternate piece of information (e.g., availability status).
- Store Data in a DataFrame: Convert the collected data into a pandas DataFrame.
- Display the DataFrame: Print the DataFrame to verify the results.

## Usage
- Modify the Search Term: Update the search_term variable in the script to search for a different product.
- Run the Script: Execute the script in your Python environment.

## Conclusion
This project provides a basic example of using Selenium for web scraping and demonstrates how to extract and process product information from Amazon. This can be extended to handle more complex scraping tasks and to interact with other elements on the webpage.
