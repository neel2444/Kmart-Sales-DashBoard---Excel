🛒 Kmart Sales Dashboard


An interactive Microsoft Excel Sales Dashboard built to analyse Kmart's retail performance across online and in-store channels over the 2023–2025 financial years.


📊 Dashboard Overview


The dashboard contains 9 interactive charts controlled by slicers (Type, Financial Year, State, Category), allowing dynamic filtering across all visuals simultaneously.

KPI Summary Cards
MetricValueTotal Sales$3,186,258Avg Sales per Transaction$707Top SuburbFrankstonTop BuyerBruce CurranTop ManagerRachael Long



📈 Charts Included

Total Sales Over Time — Area chart showing monthly online vs in-store sales trends
Average Sales Over Time — Line chart comparing average transaction value by channel
Sales By Category — Horizontal bar chart ranking 10 product categories
Sales By Suburb (Top 10) — Stacked bar chart of highest performing suburbs
Online vs Store Proportion — Donut chart (79% Store / 21% Online)
Sales By Manager — Clustered bar chart comparing manager performance
Sales By Buyers — 100% stacked bar showing online vs store split per buyer
State Sparklines — Mini trend lines with total sales per Australian state
Sales By State Map — Choropleth map of Australia showing sales concentration

![WhatsApp Image 2026-04-13 at 9 45 21 AM](https://github.com/user-attachments/assets/1c571f9d-d872-415c-bd8e-cac36e51262c)



🗂️ Dataset Summary
The raw dataset (Data sheet) includes transactional sales records with the following fields:

Date — Transaction date (Jan 2023 – Dec 2024)
Type — KMART ONLINE or KMART STORE
Financial Year — 2023, 2024, 2025
State — All 8 Australian states/territories
Suburb — Customer suburb location
Category — 10 product categories (Clothing & Fashion, Home & Living, Toys & Outdoor Play, Footwear, Beauty & Personal Care, Baby & Nursery, Electronics & Entertainment, Accessories, Stationery & Office Supplies, Party & Gift Wrap)
Sales — Transaction value in AUD
Buyer — Customer name
Manager — Store/region manager name


🔧 Tools & Techniques

Microsoft Excel
Pivot Tables & Pivot Charts
Slicers & Timeline Filters
Sparklines
Donut, Bar, Line & Area Charts
Australia Map Chart
Dashboard Layout & Design
Data Aggregation & Cleaning


📁 File Structure
📦 Kmart-Sales-Dashboard
 ┣ 📊 KMART_Sales_Dashboard_Data.xlsx
 ┃ ┣ 🗂️ Data              ← Raw transaction data
 ┃ ┣ 📋 Main Dashboard     ← Interactive dashboard
 ┃ ┣ 📈 Total Sales Over Time
 ┃ ┣ 📈 Average Sales Over Time
 ┃ ┣ 📊 Sales By Category
 ┃ ┣ 📊 Sales By Suburb
 ┃ ┣ 🍩 Online vs Store
 ┃ ┣ 📊 State Sparkline
 ┃ ┗ 🗺️ Map - Sales
 ┗ 📄 README.md

🚀 How to Use

Download the .xlsx file
Open in Microsoft Excel (2016 or later recommended for map chart support)
Use the slicers on the left panel to filter by Type, Financial Year, State, or Category
All 9 charts will update dynamically


📌 Key Insights

NSW is the highest performing state at $1.16M in sales
Kmart Store accounts for 79% of total revenue vs 21% online
Clothing & Fashion and Home & Living are the top two categories
Frankston leads all suburbs in sales volume
Sales peaked in August 2024 driven by in-store activity

