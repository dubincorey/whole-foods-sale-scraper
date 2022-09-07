# Whole Foods Sale Scraper

A web scraper in which I extrapolate Whole Foods deals and measure their value against an Amazon Prime membership.

## Goals for this project

- 🥗 **Access** Whole Foods' current on-sale items via Selenium
- 🐼 **Collect** hundreds of those items and store them in a DataFrame using Pandas
- 📊 **Analyze** and assess the discounts on these items (with and without) Amazon Prime's additional discount
- 💵 **Deduce** the value of Amazon Prime depending on how much a person shops at Whole Foods as well as the break-even point when paying for Prime

## Installation

I created this on Firefox, but if you're using Chrome you'll need to adjust [this line](https://github.com/dubincorey/whole-foods-sale-scraper/blob/ea16abacb53bca503335426fedfd49db088e6a20/scrape.ipynb?short_path=4846951#L44) to be

```
driver = webdriver.Chrome()
```

This notebook requires that you store your zip code in an `env` file as something like

```
ZIP = 12345
```

You'll need a multitude of Python libraries including

- Pandas
- BeautifulSoup
- Selenium
- Dotevnv
- re
