# 📄 Script Tag Web Scraper using Requests & BeautifulSoup

This project demonstrates a Python-based **web scraping technique that targets structured JSON data embedded within `<script>` tags** on modern web pages. Unlike traditional scrapers that extract data from visible HTML elements, this approach digs into hidden JavaScript `<script>` blocks to extract and parse data more reliably.

It uses **Requests** and **BeautifulSoup** to fetch and parse HTML content, then isolates JSON data within `<script>` tags. The parsed data is processed using Python's built-in **json** module and exported to **CSV, XLSX, or JSON** formats for analysis or integration into other tools.

---

## 🚀 Features

- 🔍 Extracts structured data hidden inside `<script>` tags
- 🧠 Parses embedded JSON objects from HTML using BeautifulSoup
- 🧼 Cleans and processes data using Python's `json` module
- 💾 Supports exporting to:
  - CSV
  - Excel (.xlsx)
  - JSON
- ⚡ Fast and lightweight (no browser automation required)

---

## ⚙️ Technologies Used

- **Python 3.x**
- **Requests** – for sending HTTP requests
- **BeautifulSoup (bs4)** – for parsing HTML content
- **JSON** – for processing embedded JSON data
- **Pandas** – for data transformation and export
- **OpenPyXL** – for Excel export

---

## 🛠 Installation & Setup

git clone https://github.com/safooralone/script-tag-webscraper.git
cd script-tag-webscraper

