# 📊 Tesla and GameStop Stock Data Analysis

This project extracts, analyzes, and visualizes stock data for **Tesla (TSLA)** and **GameStop (GME)** using Python.  
It combines data extraction via the **yFinance API** and **web scraping (BeautifulSoup + pandas)** to compare historical stock prices and revenue trends.

---

## 🧠 Project Overview

The goal of this project is to:
1. Extract stock data for Tesla and GameStop using `yfinance`.
2. Scrape company revenue data from MacroTrends.
3. Clean and structure the extracted data using `pandas`.
4. Visualize the stock performance using `matplotlib`.

---

## 🧩 Technologies Used
- Python 🐍  
- yFinance  
- BeautifulSoup  
- Requests  
- Pandas  
- Matplotlib  

---

## 🚀 Tasks Breakdown

### **Question 1:** Extract Tesla Stock Data  
Used `yfinance` to download Tesla stock history and displayed the first five rows.

### **Question 2:** Extract Tesla Revenue Data  
Web scraped Tesla’s revenue data from MacroTrends using BeautifulSoup and Pandas.

### **Question 3:** Extract GameStop Stock Data  
Downloaded GameStop stock history using `yfinance`.

### **Question 4:** Extract GameStop Revenue Data  
Web scraped GameStop’s revenue data from MacroTrends.

### **Question 5 & 6:** Plot Stock Graphs  
Used a custom function `make_graph()` to visualize stock closing prices for both companies.

---

## 📊 Visualization Example

The plots generated show the **closing prices over time** for both:
- Tesla (TSLA)
- GameStop (GME)

---

## 🧰 Installation

Before running the notebook, install the required packages:

```bash
pip install yfinance pandas matplotlib beautifulsoup4 lxml requests
