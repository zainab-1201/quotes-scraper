# Project Name: Quotes Web Scraper

### 1. Project Overview
* **Target Website:** https://quotes.toscrape.com
* **Data Fields Extracted:** Quote, Author, Tags
* **Tools Used:** Python, requests, BeautifulSoup4, pandas

### 2. Setup Instructions
1. Clone this repo: `git clone https://github.com/zainab-1201/quotes-scraper`
2. Install dependencies: `pip install -r requirements.txt`
3. Run script: `python scraper.ipynb`

### 3. Challenges & Solutions
* **Challenge:** The site has multiple pages and all quotes needed
  to be collected across all of them using pagination.
* **Solution:** Used a while loop that increments the page number
  and stops automatically when no more quotes are found on a page.
