# Analyzing the Impact of Recession on Automobile Sales

**IBM Data Visualization with Python (DV0101EN) - Final Capstone Project**

## Project Overview
The objective of this project is to analyze the impact of economic recessions on automobile sales using historical data for **XYZ Automotives**. By leveraging data analysis, visualization techniques, and statistical modeling, this project uncovers patterns and trends in consumer purchasing behavior during recessionary periods to support data-driven decision-making for business strategies.

## Project Structure
* **`DV0101EN-Final-Assign-Part-1-Questions.ipynb`** (or `Final_Assignment_Part_1.ipynb`): Jupyter Notebook containing static data visualizations developed with **Matplotlib**, **Seaborn**, and **Folium** (Tasks 1.1 through 1.10).
* **`DV0101EN-Final-Assign-Part-2-Questions.py`** (or `Automobile_Sales_Dashboard.py`): Interactive analytics web dashboard built with **Plotly** and **Dash** (Tasks 2.1 through 2.6).
* **`RecessionReportgraphs.png`**: Screenshot of dashboard output when *Recession Period Statistics* is selected.
* **`YearlyReportgraphs.png`**: Screenshot of dashboard output when *Yearly Statistics* is selected.
* **`historical_automobile_sales.csv`**: Historical automobile sales dataset.
* **`us-states.json`**: GeoJSON boundaries for United States choropleth mapping.

## Key Insights
1. **Sales Contraction**: A drastic drop in average automobile sales occurred during all major recession periods (1980, 1981-82, 1991, 2000-01, 2007-09, 2020).
2. **Vehicle Type Preferences**: High-cost vehicles (Sports cars and Executive cars) suffered the sharpest percentage drops during economic downturns, whereas more economical cars (Supperminicar and Smallfamilycar) demonstrated greater resilience.
3. **Advertising Spend**: XYZ Automotives allocated ~79% of its advertising expenditure to non-recession periods and ~21% during recessions.

## How to Run the Dashboard
1. Install dependencies:
   ```bash
   pip install dash plotly pandas
   ```
2. Run the application:
   ```bash
   python DV0101EN-Final-Assign-Part-2-Questions.py
   ```
3. Open your browser and navigate to `http://127.0.0.1:8050/`.
