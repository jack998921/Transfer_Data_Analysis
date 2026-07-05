# Football Player Transfers - End-to-End Data Analysis Project

An end-to-end data analytics project that tracks, cleans, and visualizes football player transfer market data. The project covers the entire data pipeline: from web scraping raw data to building an interactive dashboard.

## 📊 Project Overview
This project analyzes football player transfers, financial expenditures, and market values across various international and local clubs (such as Liverpool, Al Ahly, Zamalek, and more). It highlights the highest-paid clubs, the most valuable players, and the volume of player movements (transfers, departures, and loans).

---

## 🛠️ Tools & Technologies Used

### 1. Data Collection (Web Scraping)
* **Python**: The core language used for data extraction.
* **Selenium**: Used to automate the web browser and scrape dynamic content from sports websites, successfully extracting over 1,000 rows of transfer data.

### 2. Data Cleaning & Analysis
* **Microsoft Excel**: Used for initial data inspection and core analysis.
* **Power Query (Excel)**: Used to build a clean data processing pipeline. Applied steps include:
  * Text cleaning (`Trimmed Text` and `Cleaned Text` to remove extra spaces).
  * Date cleaning and localization (`Changed Type with Locale`).
  * Handling missing values (`Removed Blank Rows`).
  * Standardizing and translating club names.
* **Pivot Tables**: Used to aggregate rows and analyze data distributions (e.g., counting player transfers per team).

### 3. Data Visualization
* **Power BI**: Used to design and build an interactive reporting dashboard.

---

## 🚀 Workflow & Steps Done

1. **Web Scraping:** Wrote a custom Python script using Selenium to automatically navigate and collect raw transfer records into a dataset.
2. **Data Cleaning (ETL):** Imported the raw data into Excel's Power Query. Handled inconsistent date formats, removed blank entries, cleaned up text spaces, and mapped English club names to standardized terms for consistency.
3. **Data Analysis:** Utilized Excel Pivot Tables to cross-verify counts, summarize financial figures, and find initial market trends.
4. **Data Visualization:** Developed a Power BI dashboard consisting of two main views:
   * **Financial Insights:** Analysis of Highest Paid Clubs, Most Valuable Players, and Money Earned by Club.
   * **Transfer Volumes:** Visualizing player movements using Treemaps to track total transfers, departures, and loans.

---

## 📈 Key Dashboard Features & Insights

* **Highest Paid Clubs:** Shows market spending where clubs like Liverpool lead the charts.
* **Most Valuable Players:** A breakdown of individual player market values.
* **Transfer Volume Distribution:** Treemaps that clearly illustrate which teams are most active in buying, selling, or loaning players (highlighting major activities for clubs like Al Ahly and Zamalek).
  
