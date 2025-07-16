# 📈 Extracting and Visualizing Stock Data

This repository contains the final project for the **IBM Python Project for Data Science** course. The goal of the assignment is to extract, clean, and visualize financial data for two prominent companies — **Tesla (TSLA)** and **GameStop (GME)** — using Python libraries and techniques including **web scraping**, **data wrangling**, and **interactive graphing**.

---

## 🧠 Project Description

Extracting essential data and displaying it visually is a key part of data science. In this project, I:

- Extracted historical stock data using the `yfinance` API.
- Scraped quarterly revenue data from HTML tables using `requests` and `BeautifulSoup`.
- Cleaned and structured the data into Pandas DataFrames.
- Built interactive graphs using `Plotly` and `Dash`.
- Exported visualizations as `.png` files to fulfill course submission requirements.

---

## 🛠️ Technologies Used

- **Python 3.x**
- `yfinance` – for stock data
- `requests` & `BeautifulSoup` – for web scraping
- `pandas` – for data manipulation
- `plotly` – for interactive visualization
- Jupyter Notebook – for development and documentation


---

## 📊 Key Tasks

### ✅ Define a Graphing Function
- A reusable Plotly-based function (`make_graph`) was defined to display stock price and revenue trends.

### ✅ Tesla Data (TSLA)
- Stock data collected via `yfinance`
- Revenue data scraped from an IBM-hosted HTML table

### ✅ GameStop Data (GME)
- Stock data collected via `yfinance`
- Revenue data scraped using similar HTML parsing logic

### ✅ Final Output
- Two interactive graphs, rendered in Jupyter and saved as `.png` images:
  - **Tesla Stock Price & Revenue**
  - **GameStop Stock Price & Revenue**

---

## 🚀 How to Run the Notebook

1. Clone the repository.
2. Open the notebook in Jupyter or VS Code.
3. Make sure the following packages are installed:
   ```bash
   pip install yfinance bs4 plotly pandas requests
   
