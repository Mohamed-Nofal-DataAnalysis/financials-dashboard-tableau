# 📊 Financials Dashboard — Tableau

An interactive financial analytics dashboard built with **Tableau Desktop**, connected to an Excel data source. The dashboard provides a comprehensive view of sales performance, profitability, discount distribution, and geographic revenue breakdown.

---

## 📁 Project Structure

```
financials-dashboard-tableau/
├── README.md
├── Dashboard.png               # Dashboard screenshot
├── Financials.xlsx             # Source data (Excel)
└── Financials_Dashboard.twbx  # Tableau packaged workbook
```

---

## 📌 KPIs Tracked

| KPI | Value |
|-----|-------|
| 💰 Total Sales | $118.73M |
| 📈 Gross Sales | $127.93M |
| 🏆 Profit | $16.89M |
| 📦 Avg. Units Sold | $1.61K |
| 🏷️ Avg. Discounts | $13.15K |

---

## 📊 Charts & Visualizations

### 1. Profit by Month
A line chart tracking monthly profit trends from **January 2013 to January 2014**, showing consistent growth over the fiscal year.

### 2. Discount Band Distribution
A pie chart breaking down sales by discount tier:
- **Medium** — 94.3%
- **High** — 165.0%
- **Low** — 42.1%
- **None** — 0.0%

### 3. Gross Sales by Country (Map)
An interactive geographic map displaying gross sales by country, with the top markets being:
- 🇺🇸 United States — $27.3M
- 🇨🇦 Canada — $26.9M
- 🇩🇪 Germany — $24.9M
- 🇲🇽 Mexico — $22.7M

### 4. Sales by Segment
A vertical bar chart comparing sales across business segments:
- Government — $52.5M
- Small Business — $42.4M
- Enterprise — $19.6M
- Midmarket — $2.4M
- Channel Partners — $1.8M

### 5. Units Sold by Product
A horizontal bar chart ranking products by units sold:
- Paseo — $0.34M (top seller)
- VTT — $0.17M
- Velo — $0.16M
- Amarilla — $0.16M
- Montana — $0.15M
- Carretera — $0.15M

### 6. Gross Sales by Country (Bar/Detail)
A detailed country-level gross sales breakdown complementing the map view.



---

## Dashboard Screenshots (Click to enlarge) :

<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Dashboard.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Gross%20Sales%20by%20Country.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Sales%20by%20Segment.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Units%20Sold%20by%20Product.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Discount%20Band%20Distribution.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/KPIS.png">
<img src="https://github.com/Mohamed-Nofal-DataAnalysis/financials-dashboard-tableau/blob/main/Profit%20by%20Month.png">

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau Desktop** | Dashboard design & visualization |
| **Microsoft Excel (.xlsx)** | Data source |
| **Mapbox / OpenStreetMap** | Geographic map layer |
---
## 🚀 How to Use

1. Clone or download this repository.
2. Open `Financials_Dashboard.twbx` in **Tableau Desktop** (version 2021.1 or later recommended).
3. The workbook is packaged with the data source — no additional setup needed.
4. To reconnect to the original Excel file, go to **Data → Edit Data Source** and point it to `Financials.xlsx`.

---

## 📂 Data Source

The data is sourced from a **Microsoft Excel file** (`Financials.xlsx`) containing the following fields:

- `Segment`, `Country`, `Product`
- `Discount Band`, `Units Sold`
- `Manufacturing Price`, `Sale Price`
- `Gross Sales`, `Discounts`, `Sales`
- `COGS`, `Profit`
- `Date`, `Month Number`, `Month Name`, `Year`

---

## 👨‍💼 Author
Mohamed Nofal
Data & Business Analyst  
Transforming raw data into actionable business insights.
> Built with ❤️ using Power BI
> Feel free to ⭐ the repo if you found it useful!
