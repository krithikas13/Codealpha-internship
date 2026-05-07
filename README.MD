# Web Scraping & Data Analysis Project

## Project Overview
This project demonstrates the complete process of:
- Web Scraping
- Exploratory Data Analysis (EDA)
- Data Visualization

The dataset contains quotes and authors collected from the website:
https://quotes.toscrape.com/

---

# Task 1 – Data Visualization using Matplotlib

## Objective
To visualize the top 5 authors based on the number of quotes.

## Technologies Used
- Python
- Pandas
- Matplotlib

## Process
- Loaded the dataset using Pandas
- Counted author frequencies
- Created a bar chart for top 5 authors

## Output
A bar graph showing the authors with the highest number of quotes.

---

# Task 2 – Exploratory Data Analysis (EDA)

## Objective
To analyze the scraped dataset and extract useful insights.

## Technologies Used
- Python
- Pandas

## Process
- Displayed dataset information
- Checked missing values
- Counted unique authors
- Identified most frequent authors
- Generated statistical summaries

## Output
Basic dataset statistics and author insights.

---

# Task 3 – Web Scraping using BeautifulSoup

## Objective
To scrape quotes and author names from a website and store them in CSV format.

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas

## Process
- Sent HTTP request to the website
- Parsed HTML content using BeautifulSoup
- Extracted quotes and author names
- Stored data in a CSV file

## Output
A CSV file named `quotes.csv` containing:
- Quote
- Author

---

# Project Workflow

1. Scrape data from website  
2. Save data into CSV file  
3. Perform EDA on dataset  
4. Visualize important insights  

---

# Libraries Required

```bash
pip install pandas matplotlib beautifulsoup4 requests
```

---

# Conclusion
This project helped in understanding:
- Web Scraping
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization using Python

It is a beginner-friendly project for learning data analysis and web scraping concepts.
