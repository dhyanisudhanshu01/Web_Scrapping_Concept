# Web Scraping Projects – BeautifulSoup & Selenium

This repository demonstrates practical web scraping concepts using two real-world projects.  
The goal is to showcase both static and dynamic web scraping techniques using **BeautifulSoup** and **Selenium**.

---

## 📌 Project 1: Tata IPL Auction 2026 Scraping (BeautifulSoup)

### 🔍 Objective
Scrape the Auction Overview Grid View from the Tata IPL Auction 2026 website.

### 🛠 Tools Used
- requests
- BeautifulSoup (bs4)
- pandas

### 📊 What This Project Does
- Sends HTTP request to the IPL Auction webpage
- Parses HTML using BeautifulSoup
- Extracts auction overview grid data
- Stores extracted data into a Pandas DataFrame
- Exports the structured dataset into a CSV file

### 📁 Data
- `IPL_Auction_2026.csv`

This project demonstrates scraping from a static webpage using pure HTML parsing.

---

## 📌 Project 2: Meesho Shoes Scraping (Selenium + BeautifulSoup)

### 🔍 Objective
Scrape the list of shoes from Meesho search results.

### 🛠 Tools Used
- Selenium
- BeautifulSoup
- pandas

### 📊 What This Project Does
- Automates browser using Selenium
- Loads dynamic content from Meesho search page
- Extracts product details such as:
  - Product Name
  - Price
  - Rating
  - Reviews
- Converts extracted data into a Pandas DataFrame
- Saves structured output into a CSV file

### 📁 Data
- `shoes.csv`

This project demonstrates scraping from a dynamically loaded website using browser automation.

---

## 🧠 Key Concepts Demonstrated

- Static vs Dynamic Web Scraping
- HTML Parsing
- DOM Inspection
- Handling Dynamic Content
- Working with DataFrames
- Exporting Data to CSV
- Managing Relative File Paths
- Handling Selenium Sessions

---

## 📂 Project Structure
WEB-SCRAPING/
│
├── data/
│ ├── IPL_Auction_2026.csv
│ ├── shoes.csv
│ └── shoes.html
│
├── notebook/
│ ├── BeautifulSoup_IPL.ipynb
│ └── Selenium_Meesho.ipynb
│
├── requirements.txt
└── README.md


---

## 🚀 Learning Outcomes

- Understand when to use BeautifulSoup vs Selenium
- Learn how to scrape structured grid data
- Automate scraping for dynamic e-commerce websites
- Build clean, exportable datasets
- Apply web scraping in real-world scenarios

---

## ⚠ Disclaimer

This project is for educational purposes only.  
Please respect website terms of service and robots.txt policies before scraping any website.

