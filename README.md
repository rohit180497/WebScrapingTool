# WebScrapingTool

**Version: 1.2**

## Overview

**WebScrapingTool** is a Python package designed to simplify the installation of essential web scraping libraries. With just one command, you can have access to all the major libraries needed to build and run web scrapers efficiently. This toolkit is ideal for both beginners and advanced users who want to quickly set up their web scraping environment.

## Features

- Install essential web scraping libraries in one go
- Supports asynchronous scraping, headless browsers, and dynamic page rendering
- Works across various Python versions (>= 3.6)
- Open-source and licensed under MIT

## Installation

To install the package, simply run:

```bash
pip install WebScrapingTool
```

## Libraries Included

- pandas: Data manipulation and analysis
- numpy: Support for large, multi-dimensional arrays and matrices
- webdriver_manager: Utility for managing web drivers (Selenium)
- beautifulsoup4: HTML and XML parsing
- scrapy: Powerful web scraping framework
- requests: Easy-to-use HTTP library for making requests to web pages
- lxml: Fast parsing of HTML and XML documents
- parsel: Data extraction library (commonly used in Scrapy)
- httpx: HTTP client with async capabilities
- fake-useragent: Random user-agent generator to simulate different browsers
- cchardet: Faster character encoding detection
- aiohttp: Asynchronous HTTP client
- pyppeteer: Headless browser automation (alternative to Puppeteer)
- selenium: Web browser automation, great for dynamic pages
- tqdm: Progress bars for your web scraping tasks

## Usage

After installing the package, you can start using the libraries in your scraping projects. Here’s a simple example of using BeautifulSoup and requests to scrape a webpage:

```bash
import requests
from bs4 import BeautifulSoup

# Get the webpage
response = requests.get('https://example.com')

# Parse the HTML
soup = BeautifulSoup(response.text, 'html.parser')

# Extract data
title = soup.title.string
print(f"Page Title: {title}")


```

## Contributing
Feel free to contribute to this package by submitting issues or pull requests on GitHub.

Fork the repository from GitHub.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your changes to your forked repository.
Submit a pull request to the main repository.
Please ensure your code adheres to our coding standards and passes all tests before submitting a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Author
- Rohit Kosamkar

## GitHub
Email: rohitkosamkar97@gmail.com