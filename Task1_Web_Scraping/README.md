**Task 1: Web Scraping Project
**
 **Overview**
This project is part of the CodeAlpha Data Analytics Tasks.  
The goal of this task is to extract data from a website using Python web scraping techniques and convert it into a structured dataset.

 **Objective**
- Extract quotes and author information from a public website
- Handle HTML structure using BeautifulSoup
- Create a structured dataset (CSV format)
- Store data for further analysis

**Data Source
**Website used:
- http://quotes.toscrape.com

** Tools & Libraries Used
**- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- Google Colab

 **Process**

 1. Send Request
Used `requests` library to fetch webpage content.

 2. Parse HTML
Used BeautifulSoup to extract required elements:
- Quote text
- Author name

3. Handle Pagination
Scraped multiple pages using a loop until no data was left.

4. Create Dataset
Stored data into a structured DataFrame using Pandas.

5. Export Data
Saved final dataset as CSV file:
