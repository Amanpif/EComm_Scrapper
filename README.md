# EcommScrapper

## 📌 Overview
EcommScrapper is a Python-based multi-vendor e-commerce scraper designed to extract product details from major Indian online marketplaces. It combines the power of **Selenium** and **BeautifulSoup** to handle both dynamically loaded and static content.

Supported vendors include:
- Amazon
- Flipkart
- Myntra
- Meesho
- Jiomart
- Bigbasket
- Croma

With a single function call, you can scrape multiple platforms and consolidate the data into a structured dataset.

---

## ✨ Features
- Scrapes **product name, price, ratings, discount, delivery time, description, and product link**.
- Works across multiple platforms in one execution.
- Handles dynamic content using Selenium and static HTML using BeautifulSoup.
- Outputs data as Python lists or Pandas DataFrames for easy export.
- Customizable search keywords and optional pin code support for localized results.

---

## 📦 Requirements
Install the following Python packages before running the scraper:

```bash
pip install requests beautifulsoup4 selenium webdriver-manager numpy pandas
