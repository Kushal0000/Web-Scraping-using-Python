# 📊 Web Scraping: Largest U.S. Companies by Revenue

This Python project scrapes the table of the largest companies in the United States by revenue from Wikipedia, structures the data using `pandas`, and exports it into a CSV file.

---

## 🌐 Source URL
[Wikipedia: List of Largest U.S. Companies by Revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

---

## 🧰 Technologies Used

- `Python 3.x`
- `requests` – to fetch webpage content
- `BeautifulSoup` – to parse and extract HTML content
- `pandas` – to clean and export data to CSV

---


📦 Installation and Setup
1. Install Required Dependencies
Ensure you have Python installed, then run the following command in your terminal to install the necessary packages:

bash
Copy
Edit
pip install requests beautifulsoup4 pandas
2. Run the Script
Execute the scraping script with:

bash
Copy
Edit
python scraper.py
3. Output Location
After successful execution, the script will generate a file named Output.csv, saved at:

swift
Copy
Edit
C:/Users/kusha/OneDrive/Desktop/Projects/Python/Web_Scraping/
✅ Key Features
Real-Time Data Extraction: Automatically retrieves the latest table of top U.S. companies by revenue from Wikipedia.
Clean Data Parsing: Efficiently processes HTML content and extracts structured data.
CSV Export: Saves the data in a clean, analysis-ready .csv format.
Flexible Design: Easily adaptable for scraping other structured Wikipedia tables or similar web sources.



📌 Sample Output Columns
Rank
Name
Industry
Revenue (USD millions)
Profit (USD millions)
Employees
Headquarters

🧠 Use Cases
Academic projects
Market research
Data analysis & visualization
Investment insights

