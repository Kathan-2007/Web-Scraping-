# 📚 Book Data Web Scraping Project

A Python-based web scraping project that extracts book information from the **Books to Scrape** website and stores it into a structured CSV file.

---

## 🚀 Project Description

This project focuses on collecting and organizing book-related data by scraping multiple web pages. The goal is to automate data extraction and create a clean dataset for further analysis.

The script processes multiple pages and extracts key details for each book.

---

## 📊 Extracted Data

The following information is collected for every book:

* 📖 Title
* 💰 Price
* ⭐ Rating
* 📦 Availability

All extracted data is stored in:

```id="3kxt8c"
Book_data.csv
```

---

## ⚙️ Working Process

* Read HTML content of multiple pages (up to 50 pages)
* Parse the HTML using **BeautifulSoup**
* Locate book elements using tags and classes
* Extract required fields (title, price, rating, availability)
* Store the data in a structured format
* Export the final dataset into a CSV file

---

## 🛠️ Technologies Used

* Python
* BeautifulSoup (bs4)
* HTML Parsing
* CSV Module

---

## 📂 Output

The final output is a CSV file containing all scraped book data, ready for:

* Data analysis
* Visualization
* Machine learning projects

---

## ✨ Features

* Scrapes data from multiple pages
* Handles structured extraction efficiently
* Clean and organized dataset generation
* Simple and readable code

---

## 📌 Conclusion

This project demonstrates how web scraping can be used to efficiently collect real-world data and convert it into a usable format for further processing.

---

⭐ Feel free to explore and enhance the project!
