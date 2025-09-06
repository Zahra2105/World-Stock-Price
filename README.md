# World-Stock-Price
Data analysis and visualization of worldwide stock prices using Google BigQuery and Looker Studio. Includes SQL for top trading volume brands, volatility trends, and geographic insights.

📂 Project Files
SQL Queries (.sql): /sql — BigQuery scripts for data extraction and calculations
Report PDF: World_Stock_Price.pdf — Static snapshot of interactive dashboard
Preview Images:
🧩 Data Modeling & Processing
BigQuery (SQL)
Preprocessing: filtering valid dates & symbols, aggregating by brand/ticker/country
Calculations:
Monthly % Change in Volume (MoM)
Daily Max Gain & Loss per Brand
Volatility over time by ticker
Top 40% brands (Pareto analysis)
Looker Studio
Imported BigQuery views into charts: line, bar, bubble, treemap, map
Applied conditional coloring, number formatting, and filters
📈 Dashboard Highlights
Trading Activity Trend: total volume per industry over time
MoM Volume Change: growth & drop patterns month-to-month
Top Volume Brands: Pareto-style scatter plot with bubble sizing
Geo Insights: share of companies and high-volume countries
Volatility Spikes: ticker-wise historical fluctuations
Gainers vs. Losers: max daily upward & downward moves
🛠 Stack
Google BigQuery (SQL queries, ETL logic)
Looker Studio (visual analytics)
CSV/Parquet datasets from public stock market sources


