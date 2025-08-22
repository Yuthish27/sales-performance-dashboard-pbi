# Sales Performance Dashboard (Power BI)

An interactive Power BI dashboard to monitor key sales metrics—total sales, average sales, category trends, and regional performance.

## 🚀 Features
- Power Query for cleaning and shaping data
- Data model with relationships
- DAX measures (Total Sales, Average Sales, YoY Growth, etc.)
- Slicers, drill-through, and conditional formatting

## 📂 Files
- `Sales_Performance_Dashboard.pbix` – main report
- `assets/screenshots/` – key visuals

## 🧠 DAX (examples)
- **Total Sales**: `Total Sales = SUM(Sales[SalesAmount])`
- **Average Sales**: `Avg Sales = AVERAGE(Sales[SalesAmount])`
- **YoY Sales**: `YoY Sales = CALCULATE([Total Sales], DATEADD('Date'[Date], -1, YEAR))`

## 🖼️ Screenshots
![KPI](assets/screenshots/kpi.png)
![Trend](assets/screenshots/trend.png)

## 🎥 Demo
Unlisted video: <YOUR_YOUTUBE_LINK>

## 🔧 How to Open
1. Download the `.pbix` file.
2. Open in **Power BI Desktop** (Microsoft Store or standard version).

## 📊 Data
- Source: <briefly describe or anonymize>
- Rows/Columns: <optional>
- Refresh: Manual (file-based)

## 🗂️ Folder Structure
