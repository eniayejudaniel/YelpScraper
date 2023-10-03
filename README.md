# Yelp Website Scraper and Email Extractor

This repository contains Python scripts for scraping business website information from Yelp and extracting email addresses from the collected websites.

# Overview
This project combines two Python scripts to gather and process data related to businesses listed on Yelp:

**Yelp Website Scraper:** A web scraping script built with Scrapy that extracts website information from Yelp search results for businesses in New York, NY, USA.

**Email Extractor:** A script that takes a list of website URLs and attempts to extract email addresses from those websites, including the homepage, "contact" page, and "contact us" page.

# Yelp Website Scraper
**Description**
The Yelp Website Scraper script is designed to collect website information from businesses listed on Yelp in New York, NY. It utilizes Scrapy, a web crawling and web scraping framework, to extract data. The extracted website information is saved in JSON format.

**Getting Started**
To use the Yelp Scraper, follow these steps:

- **Prerequisites:** Ensure you have Python and Scrapy installed on your system.

- **Clone the Repository:** Clone this GitHub repository to your local machine.
```bash
git clone https://github.com/eniayejudaniel/YelpScraper.git
```
- **Navigate to the Project Directory:** Change your working directory to the project folder.
```bash
cd YelpScraper
```
- **Run the Yelp Website Scraper:** Execute the Scrapy spider to start scraping Yelp data.
```bash
scrapy crawl WebsiteScraper
```

# Email Extractor
**Description**
The Email Extractor script takes a list of website URLs as input and attempts to extract email addresses from those websites. It follows a predefined set of URLs to increase the chances of finding contact information.

**Getting Started**
To use the Email Extractor, follow these steps:

- **Prerequisites:** Ensure you have Python installed on your system.

- **Clone the Repository:** Clone this GitHub repository to your local machine.
```bash
git clone https://github.com/eniayejudaniel/YelpScraper.git
```
- **Navigate to the Project Directory:** Change your working directory to the project folder.
```bash
cd YelpScraper
```
- **Run the Email Extractor Script:** Execute the Email Extractor script to start extracting email addresses from websites.
```bash
python EmailScraper.py
```
# Data
The extracted data is stored in JSON format and TXT  file. It can be found in the repository:

[WebsiteOutput.json](https://github.com/eniayejudaniel/YelpScraper/blob/main/WebsiteOutput.json): Contains website information collected by the Yelp Scraper script.

[EmailOutput.txt](https://github.com/eniayejudaniel/YelpScraper/blob/main/EmailOutput.txt): Contains email addresses extracted by the Email Extractor script.

# Contributing
Contributions to this project are welcome! If you have any improvements, bug fixes, or additional features to suggest, please feel free to submit a pull request.

# License
This project is licensed under the [MIT License](License).
