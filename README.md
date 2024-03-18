# Web Scraper and data cleaning for Books

This Python script demonstrates a web scraper and data cleaning for the Books To Scrape: https://books.toscrape.com website. It was created to test my understanding of web scraping techniques and explore my current knowledge in this area.

Overview

The web scraper is designed to extract the following information from the book pages and also clean the clean the scrapped data for further analysis:

- Book Name
- Book Details (e.g., Product Type, Price, Tax, etc.)
- Book Image URL
The scraped data is collected and returned as a list of dictionaries, where each dictionary represents the information of a single book.

Code Structure
The project consists of the following main functions:

- `parse_url(url)`: Sends a GET request to the given URL and returns the parsed HTML content as a BeautifulSoup object.
- `get_page_url(base_url, relative_url)`: Constructs the full URL for a page by combining the base URL and the relative URL.
- `scrape_book_info_page(soup)`: Extracts book information from a single book page.
- `scrape_books(base_url, start_page=1)`: Scrapes book information from the website, starting from the specified page number.

Suggestions and contributions to improve this code are always welcome
