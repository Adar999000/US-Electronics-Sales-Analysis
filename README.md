# 📊 US Electronics Sales Analysis (Python)

## 📌 Project Overview
End-to-end Data Analysis project using Python (Pandas, Matplotlib). Analyzed over 186,000 sales records to identify seasonal trends, optimize ad timing, and discover product correlations (Market Basket Analysis).

**Role:** Data Analyst
**Tech Stack:** Python (Pandas, Matplotlib, Itertools), Google Colab Notebook.

## 🔍 Key Insights & Business Recommendations

### 1. 📅 Seasonality (Best Month)
* **Finding:** **December** was the strongest month with nearly **$4.6M** in sales (Holiday Season).
* **Recommendation:** Inventory for high-demand items needs to be stocked by late October to prevent Q4 shortages.

### 2. ⏰ Ad Timing Optimization
* **Finding:** Customer activity peaks at **12:00 PM** (Lunch break) and **7:00 PM** (After work).
* **Recommendation:** Launch paid ad campaigns 30 minutes prior to these peak windows (11:30 AM & 6:30 PM) to maximize CTR.

### 3. 🌎 Geographical Performance
* **Finding:** **San Francisco (CA)** is the top-performing city in terms of total revenue.
* **Recommendation:** Focus logistics improvements and "Same-Day Delivery" pilots in the SF Bay Area to leverage this strong customer base.

### 4. 🛒 Product Strategy (Market Basket)
* **Finding:** The most common pair bought together is **iPhone + Lightning Charging Cable**.
* **Recommendation:** Implement a distinct "Bundle Deal" at checkout for these items to increase Average Order Value (AOV).

### 5. 💰 Price vs. Quantity Strategy
* **Finding:** **AAA Batteries** drive the highest traffic (Volume), while **Macbook Pro** drives the highest revenue (Value).
* **Recommendation:** Use cheap, high-volume items (Batteries/Headphones) as "Loss Leaders" to acquire customers, then retarget them with high-ticket laptops.

## 🛠️ Technical Skills Demonstrated
* **Data Wrangling:** Merging 12 CSV files, handling Null values, parsing dates, and converting data types.
* **Feature Engineering:** Extracting City/State from addresses and parsing Hour/Month from timestamps.
* **Visualization:** Created Dual-Axis charts (Price vs. Volume), Horizontal Bar charts for product pairs, and Geospatial analysis using Matplotlib.
* **Advanced Analytics:** Implemented a combination algorithm (`itertools`) to identify product bundling opportunities.

## 📂 Data Source
* The dataset used in this analysis was originally provided by Keith Galli.
* https://github.com/KeithGalli/Pandas-Data-Science-Tasks

## 📬 Contact
* Created by **Adar Zilbershtein**
* https://www.linkedin.com/in/adar-zilbershtein/
* **Feel free to reach out for any questions or collaborations!**

## 🚀 Installation & How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/AdarZil/US-Electronics-Sales-Analysis.git](https://github.com/AdarZil/US-Electronics-Sales-Analysis.git)

2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib

3. Open the notebook:
  ```bash
  Launch Google Colab.
  Open the file Sales_Analysis_Project.ipynb.
  Run all cells to see the analysis and visualizations.




