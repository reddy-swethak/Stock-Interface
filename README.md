# NSE Stock Data Viewer

An interactive web application for analyzing NSE stock data by sector, leveraging **Streamlit**, **yFinance**, and **Seaborn** for data visualization and exploration.

---

## Features

- **Stock Filtering:**
  - Select stocks by sector.
  - Search for specific companies.
  - Multi-select option for analyzing multiple stocks at once.

- **Date Range Customization:**
  - Flexible range selection based on days, weeks, months, or years.
  - Option to manually pick start and end dates.

- **Exploratory Data Analysis (EDA):**
  - Summary statistics for the selected stocks.
  - Visualizations like percentage change histograms, closing price trends, pair plots, and heat maps.

- **Data Storage:**
  - Data fetched using `yFinance` is stored for further analysis during the session.

---

## Installation

### Prerequisites
- Python 3.8 or later
- Required libraries: `streamlit`, `yfinance`, `seaborn`, `matplotlib`, `pandas`

Usage
* Start the app using the command above.
* Use the sidebar to:
  - Select a date range.
  - Filter by sector or search for specific companies.
  - Choose the companies for analysis.
* Click Submit Selection to fetch stock data.
* View the analysis through the EDA components selected in the sidebar.


File Structure

nse-stock-data-viewer/
├── app.py               # Main Streamlit application script
├── requirements.txt     # Required Python libraries
├── nse_companies.py     # NSE company data grouped by sector
├── README.md            # Project documentation
└── data/                # (Optional) Directory for storing fetched data
