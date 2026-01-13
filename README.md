# Data Scraper Project

Professional Python data scraping pipeline.

## Tech Stack
- Python 3.12
- Pipenv
- requests
- BeautifulSoup4
- pandas
- pytest

## Setup
```bash
pip install pipenv
pipenv --python 3.12
pipenv install requests beautifulsoup4 pandas
pipenv install --dev pytest
pipenv shell
```

## Dynamic Scraping (Playwright)
This project uses Playwright to scrape JavaScript-rendered job listings.

```bash
pipenv install playwright
pipenv run playwright install
```
