# Amazon Scraping With Python

A Python-based web scraping project that extracts product details from Amazon search result pages and saves them into a CSV file for further analysis.

> ⚠️ This project is for **educational purposes only**.

---

## 📌 Features

- Scrapes Amazon search result pages
- Extracts:
  - Product URL
  - Product title
  - Price
  - Rating
  - Number of reviews
  - ASIN
  - Product description
- Saves structured data into a CSV file
- Supports scraping multiple URLs using an input file

---

## 🛠 Tech Stack

- Python
- Requests
- BeautifulSoup (bs4)
- CSV module

---

## 📂 Project Structure

```bash
Amazon-Scraping-With-Python
│
├── amazon_scraping.py # Main scraping script
├── url.txt # Input file containing Amazon search URLs
└── out.csv # Output file with scraped product data
```
---

## ▶️ How It Works

1. Reads Amazon search URLs from `url.txt`
2. Sends HTTP requests with browser-like headers
3. Parses HTML using BeautifulSoup
4. Extracts product-level information
5. Writes the extracted data into `out.csv`

---

## 🚀 How to Run

### 1️⃣ Install Dependencies
```bash
pip install requests beautifulsoup4 lxml
```

2️⃣ Add URLs

Add Amazon search URLs (one per line) inside:
```bash
url.txt
```

3️⃣ Run the Script
```bash
python amazon_scraping.py
```

4️⃣ Output

Scraped data will be saved to:

```bash
out.csv
```

## 📄 Sample Output Columns

- Product Url

- Product Title

- Price

- Rating

- Number of Review

- ASIN

- Product Description

## ⚠️ Disclaimer

- Amazon may block requests if scraping is excessive

- Use delays responsibly (time.sleep)

- Follow Amazon’s Terms of Service

## 👤 Author

Built as a Python automation and web scraping practice project to understand real-world data extraction workflows.
