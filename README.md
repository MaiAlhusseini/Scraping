# 📚 Books to Scrape - Catalog Web Scraper

## 📌 Project Overview
This project is an automated web scraping pipeline built in Python using **BeautifulSoup4** and **Requests**. It extracts the full book catalog (1,000 books across 50 pages) from [Books to Scrape](https://books.toscrape.com/) and exports the cleaned dataset for data analysis and warehousing.



## 📁 Repository Structure

DEPI_Technical/ ├── WS.ipynb # Main Python scraping script ├── books_catalog.xls # Processed Excel catalog |└── README.md # Documentation


---

## 🛠️ Extracted Data Fields
* **Book Name**: Full title extracted from the link `title` attribute.
* **Category**: Genre extracted from the detail page breadcrumb menu.
* **Rating**: Converted from CSS star classes into a numeric integer (1–5).
* **Price (£)**: Cleaned numeric price value.
* **Is_Available**: Boolean status (`True` if in stock, `False` otherwise).

---
