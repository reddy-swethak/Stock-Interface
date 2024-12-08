
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

---

## Usage

1. Start the app using the command above.
2. Use the sidebar to:
   - Select a date range.
   - Filter by sector or search for specific companies.
   - Choose the companies for analysis.
3. Click **Submit Selection** to fetch stock data.
4. View the analysis through the EDA components selected in the sidebar.

---

## File Structure

```plaintext
nse-stock-data-viewer/
├── app.py               # Main Streamlit application script
├── requirements.txt     # Required Python libraries
├── nse_companies.py     # NSE company data grouped by sector
├── README.md            # Project documentation
└── data/                # (Optional) Directory for storing fetched data
```

---

## Future Enhancements

- Add real-time data fetching and live updates.
- Include additional EDA components like moving averages or Bollinger Bands.
- Provide options for exporting analyzed data to CSV or Excel.
- Optimize performance for handling larger datasets.

---

## Contributions

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

---

## Acknowledgements

- **[Streamlit](https://streamlit.io/):** For the seamless app-building experience.
- **[yFinance](https://pypi.org/project/yfinance/):** For fetching stock data effortlessly.
- **[Seaborn](https://seaborn.pydata.org/):** For beautiful and informative visualizations.
