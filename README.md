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

## 📁 Project Structure

Web_Scraping/
├── scraper.py # Main script to scrape and export data
├── Output.csv # Final output file (generated after running script)
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Web_Scraping.git
   cd Web_Scraping
Install Dependencies:
bash
Copy
Edit
pip install requests beautifulsoup4 pandas
Run the Script:

bash
Copy
Edit
python scraper.py
Output: A CSV file named Output.csv will be saved to:

swift
Copy
Edit
C:/Users/kusha/OneDrive/Desktop/Projects/Python/Web_Scraping/
✅ Features
Automatically fetches the most recent data from Wikipedia.
Parses and cleans the HTML table content.
Converts it into a structured CSV file.
Easily customizable for other Wikipedia tables.

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

