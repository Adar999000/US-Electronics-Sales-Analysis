# 📊 US Electronics Sales Analysis (Python)

## 📌 Project Overview
End-to-end Data Analysis project using Python (Pandas, Matplotlib). Analyzed over 186,000 sales records to identify seasonal trends, optimize ad timing, and discover product correlations (Market Basket Analysis).

**Role:** Data Analyst
**Tech Stack:** Python (Pandas, Matplotlib, Itertools), Jupyter Notebook.

## 🔍 Key Insights & Business Recommendations

### 1. Seasonal Trends
* **Insight:** December is the peak sales month (Holiday Season).
* **Recommendation:** Inventory levels should be maximized by late October to prevent stockouts.

### 2. Ad Timing Optimization
* **Insight:** Peak order volumes occur at **12:00 PM** (Lunch) and **7:00 PM** (After work).
* **Recommendation:** Schedule paid advertising campaigns 30 minutes prior to these windows to capture high-intent users.

### 3. Product Strategy (Market Basket Analysis)
* **Insight:** The most frequent purchase pair is **iPhone + Lightning Charging Cable**.
* **Recommendation:** Implement a dynamic "Add to Cart" popup suggesting the cable whenever an iPhone is added, to increase Average Order Value (AOV).

### 4. Pricing Strategy
* **Insight:** Validated a strong inverse correlation between Price and Quantity.
* **Recommendation:** Use high-volume/low-margin items (AAA Batteries) as "loss leaders" to drive traffic, then upsell to high-margin items (Monitors, Laptops).

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
  Launch Jupyter Notebook or Google Colab.
  Open the file Sales_Analysis_Project.ipynb.
  Run all cells to see the analysis and visualizations.




