# Sales_Data_Scraper
Description:

This repository contains a Python script designed to automate the process of scraping sales summary data from a website, specifically for Lou Malnati's locations. The script interacts with the website using Selenium, extracts relevant data using XPath and CSS selectors, and processes the HTML content with BeautifulSoup. The scraped data is then formatted and sent via email.


Features:
Location Mapping: A dictionary that maps Lou Malnati's location names to their corresponding codes.
User Input: Functions to capture user input for dates and locations, with validation and default options.
Web Scraping: Uses Selenium to navigate to the target URL, extract data using CSS selectors, and handle dynamic content loading.
Data Processing: Processes HTML content with BeautifulSoup for further manipulation or display.
Email Notification: Automatically sends an email with the extracted sales data, using secure credentials.


Usage:
The script prompts the user for a start date, end date, and location.
If no location is provided, it defaults to Michigan Ave Lou Malnati's.
After navigating to the specified URL, the script scrapes the net sales value and sends it via email to the specified recipient.


Dependencies:
Python 3.x
Selenium
BeautifulSoup4
smtplib for email handling
