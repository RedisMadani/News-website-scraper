# Financial News Scraper

This scraper is developed using BeautifulSoup4 in Python and is specifically designed for extracting news from moneycontrol.com. The scraper provides the ability to extract news from multiple pages, following the website's pagination.

## Usage

1. The main page to start scraping from is: [https://www.moneycontrol.com/news/technical-call-221.html](https://www.moneycontrol.com/news/technical-call-221.html).

2. The program scrapes news from subsequent pages by extracting the website link from the "Next" buttons on each page.

3. The resulting data is stored in a JSON file, which includes the news heading, date, and image link. The data is indexed by the page number.

Please note that if you need to scrape news from different sources or websites, you can create separate scrapers tailored for those websites and submit a pull request to add them to the project.