# Web Scraping Books Data

## Project Description
This project demonstrates **web scraping of books data** from [Books to Scrape](http://books.toscrape.com) using **Python**. The goal was to practice extracting structured information from web pages and organizing it into a tabular format for analysis.

Two approaches were used:
1. **Requests + BeautifulSoup** for scraping static HTML pages.
2. **Playwright** for handling pages dynamically (simulating browser behavior).

## Tasks Performed
- Sent HTTP GET requests using `requests` with proper headers.
- Parsed HTML pages using `BeautifulSoup` to extract:
  - Book title
  - Price
  - Image URL
  - Rating
- Used `Playwright` to scrape dynamic content and navigate pages if needed.
- Cleaned and formatted extracted data.
- Stored data in a **Pandas DataFrame** for further analysis.

## Skills 
- **Python programming** for web scraping tasks.
- Using **requests** to fetch web pages and **BeautifulSoup** to parse HTML.
- Automating browser interactions using **Playwright**.
- Handling **dynamic content** and multiple page scraping.
- Data cleaning and preparation using **Pandas**.
- Exporting structured data to **CSV/Excel**.

## Dataset Output
The final dataset includes:
- Book Title
- Price
- Rating
- Image URL
