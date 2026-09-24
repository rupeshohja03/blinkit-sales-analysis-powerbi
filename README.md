# 🛒 Blinkit Sales Analysis — Power BI Dashboard

An end-to-end Power BI project analyzing **Blinkit's** sales performance, customer satisfaction, and inventory distribution — built to identify actionable business insights through interactive KPIs and visualizations.

SCREENSHOTS: (<img width="1155" height="672" alt="Blinkit_Dashboard png" src="https://github.com/user-attachments/assets/cf8742c6-ebff-419e-966d-6b27b3180c2d" />
)
---

## 📌 Project Overview

Blinkit ("India's Last Minute App") needed a consolidated view of sales performance across outlets, item categories, and store formats. This dashboard brings together sales, inventory, and customer-rating data into a single interactive Power BI report to support data-driven decisions on inventory allocation, outlet strategy, and category management.

**Business Requirement:**
> To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

---

## 🧰 Tools & Technology

- **Power BI Desktop** — data modeling, DAX, and report development
- **Power Query** — data connection, transformation, and cleaning
- **DAX (Data Analysis Expressions)** — calculated measures and KPIs

---

## 🔑 KPIs

| KPI | Description | Value |
|---|---|---|
| Total Sales | Overall revenue generated from all items sold | **$1.20M** |
| Average Sales | Average revenue per sale | **$141** |
| Number of Items | Total count of different items sold | **8,523** |
| Average Rating | Average customer rating for items sold | **3.9** |

---

## 📊 Charts & Visualizations

| # | Chart | Type | Objective |
|---|---|---|---|
| 1 | Total Sales by Fat Content | Donut Chart | Impact of fat content on total sales |
| 2 | Total Sales by Item Type | Bar Chart | Performance of item types by total sales |
| 3 | Fat Content by Outlet for Total Sales | Stacked Column Chart | Compare sales across outlets segmented by fat content |
| 4 | Total Sales by Outlet Establishment | Line Chart | Influence of outlet age on total sales |
| 5 | Sales by Outlet Size | Donut / Pie Chart | Correlation between outlet size and total sales |
| 6 | Sales by Outlet Location | Bar Chart (Tier-wise) | Geographic distribution of sales |
| 7 | All Metrics by Outlet Type | Matrix / Table Card | Comprehensive KPI view by outlet type |

**Interactive slicers:** Outlet Location Type · Outlet Size · Item Type

---

## 🛠️ Project Workflow

1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Layouting
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation

---

## 💡 Key Insights

- **Supermarket Type1** drives the majority of revenue (~$787.55K, 5,577 items), far outperforming Grocery Stores and Supermarket Type2/3, which each contribute under $152K.
- **Fruits and Vegetables** and **Snack Foods** are the top-selling categories at $0.18M each, followed by Household ($0.14M) and Frozen Foods ($0.12M).
- **Regular fat content** items outsell Low Fat items overall ($776.32K vs $425.3K).
- **Tier 3 and Tier 2** locations account for roughly **71.3%** of total revenue combined, with Tier 1 contributing the smallest share.
- **Medium-sized outlets** generate the highest sales ($507.90K), ahead of Small ($444.79K) and High ($248.99K) formats.
- Sales by outlet establishment year **peaked around 2018** (~$0.20M), with most other years holding steady near $0.13M.
- Average customer rating stays **consistently around 3.9–3.93** across all outlet types, indicating stable satisfaction regardless of format.

---

## 📁 Repository Structure

```
├── assets/
│   └── dashboard.jpg          # Dashboard screenshot
├── Blinkit_Dashboard.pbix     # Power BI project file
├── docs/
│   └── Blinkit_Dashboard_Documentation.docx   # Full project documentation
└── README.md
```

---

## 🚀 Getting Started

1. Clone this repository
2. Open `Blinkit_Dashboard.pbix` in **Power BI Desktop**
3. Refresh the data connection if prompted
4. Explore the dashboard using the slicers on the left panel

---

## 📄 Documentation

Full project documentation (requirements, methodology, and detailed insights) is available in [`docs/Blinkit_Dashboard_Documentation.docx`](docs/Blinkit_Dashboard_Documentation.docx).

---

## 📬 Contact

Have questions or suggestions? Feel free to open an issue or reach out.
