🔌⚡ NH Residential Energy Plan Scraper & Data Pipeline
(A Python Web Scraper + Data Extraction Pipeline for Electricity Plans in New Hampshire)

This project automatically scrapes real-time residential electricity plan details from the New Hampshire Public Utilities Commission (PUC) website and structures them into clean, queryable Python dictionaries—optionally storing the final records in MongoDB.

It demonstrates web scraping, data extraction, regex-based parsing, structured data modeling, and database insertion.

🌟 Key Features

Automatically scrapes live electricity plan data
Extracts structured fields using BeautifulSoup & regex
Handles multiple utilities through dynamic URL generation
Stores results into MongoDB (residential collection)
Demonstrates data engineering workflow: scrape → parse → structure → store
Pure Python — no external drivers required

🚀 Tech Stack

Languages & Libraries:
Python 3
BeautifulSoup4 (HTML parsing)
Requests (HTTP requests)
Regex (re module)
pprint (pretty-printing extracted data)

pymongo (MongoDB driver)
