# 🕸️ Web Scraper: Top U.S. Companies by Revenue

This Python-based web scraper extracts the latest list of the **largest companies in the United States by revenue** from Wikipedia. It parses the table data, structures it into a clean format, and exports it to a `.csv` file for further analysis or reporting.

---

## 📁 Project Overview

- **Source:** [Wikipedia - Largest U.S. Companies by Revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)  
- **Output:** A CSV file containing company data such as rank, name, industry, revenue, and more  
- **Use Cases:** Data analysis, reporting, automation, and business intelligence

---

## 🚀 Features

- 🔄 **Live Scraping:** Automatically fetches the most recent data from Wikipedia  
- 🧹 **Clean Parsing:** Uses BeautifulSoup to parse and sanitize HTML table contents  
- 📊 **Data Structuring:** Transforms raw data into a structured pandas DataFrame  
- 💾 **CSV Export:** Saves output to a clean `.csv` file  
- 🛠️ **Customizable:** Easily extendable to scrape other tables with similar structures

---

## ⚙️ Installation

### Prerequisites

Make sure you have Python 3.x installed on your system.

### Install Dependencies

```bash
pip install requests beautifulsoup4 pandas
▶️ How to Run
Clone or download the repository

Navigate to the project directory

Run the script using:

bash
Copy
Edit
python scraper.py
After execution, the output will be saved as:

swift
Copy
Edit
C:/Users/kusha/OneDrive/Desktop/Projects/Python/Web_Scraping/Output.csv

📂 Output Structure
The output CSV may include the following columns (based on current Wikipedia data):

Rank
Name
Industry
Revenue
Employees
Headquarters

🛠️ Customization Tips
To scrape a different Wikipedia table, update the url and the table index
Modify column parsing logic to fit new structures





