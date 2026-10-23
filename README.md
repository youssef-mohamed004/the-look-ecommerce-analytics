# THE LOOK | E-Commerce Fashion Inventory & Sales Analysis

**Turning fashion e-commerce data into actionable business insights using Microsoft Excel.**

An end-to-end data analytics project exploring business performance, customer journeys, revenue trends, forecasting, inventory efficiency, and product returns through five interactive Excel dashboard pages.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Dashboard Gallery](#-dashboard-gallery)
- [Key Business Insights](#-key-business-insights)
- [Tools & Technical Skills](#-tools--technical-skills)
- [Analytical Approach](#-analytical-approach)
- [Business Recommendations](#-business-recommendations)
- [Important Data Note](#-important-data-note)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Author](#-author)

---

## 🎯 Project Overview

The Look is a fashion e-commerce analytics project built using Microsoft Excel to transform raw business data into meaningful insights that support data-driven decision-making.

The project investigates key business questions:

- How is the business performing in terms of revenue, orders, and profitability?
- Where do sessions drop off throughout the browsing-to-purchase journey?
- Which traffic sources, product categories, and countries contribute most to performance?
- What historical trends and seasonal patterns can help forecast revenue and demand?
- How much inventory cost is tied up in unsold products?
- How do product returns and distribution center performance affect inventory efficiency?

The project brings these analytical perspectives together in five dashboard pages, combining KPI monitoring, interactive filtering, historical analysis, forecasting, and operational insights.

---

## 📊 Dashboard Gallery

### 01 — Home Page

![The Look Home Page](Dashboards/01%20%E2%80%94%20Home%20Page.png)

The main landing page introduces the project's visual identity and provides navigation to the analytical dashboards.

**Highlights**
- Centralized dashboard navigation.
- Fashion-inspired visual design using burgundy, black, and beige tones.
- A unified starting point for exploring business performance and operations.

### 02 — Executive Overview

![Executive Overview Dashboard](Dashboards/02%20%E2%80%94%20Executive%20Overview.png)

Provides a high-level view of business performance, including revenue growth, profitability, order volume, and category and geographic contributions.

**Key Metrics**
- Total Revenue
- Total Orders
- Average Order Value (AOV)
- Total Cost
- Gross Profit
- Profit Margin
- Total Items Sold

**Key Questions**
- How has revenue evolved over time?
- Which product categories and countries contribute most to revenue?
- How does order volume compare with Average Order Value?
- How is revenue distributed by gender?

### 03 — Funnel & Traffic Analysis

![Funnel and Traffic Analysis Dashboard](Dashboards/03%20%E2%80%94%20Funnel%20%26%20Traffic%20Analysis.png)

Examines the customer journey from browsing sessions to cart activity and purchase sessions, highlighting potential conversion bottlenecks and opportunities to improve marketing effectiveness.

**Key Metrics**
- Browsing Sessions
- Bounce Rate
- Session-to-Cart Rate
- Cart-to-Purchase Rate
- Cart Abandonment Rate
- Overall Conversion
- Revenue at Risk

**Key Questions**
- How many browsing sessions progress to cart activity?
- How many cart sessions fail to reach a purchase?
- How do traffic sources compare in browsing volume and conversion?
- How has cart abandonment changed over time?
- Does conversion vary by day of the week?

### 04 — Forecasting & Time Intelligence

![Forecasting and Time Intelligence Dashboard](Dashboards/04%20%E2%80%94%20Forecasting%20%26%20Time%20Intelligence.png)

Explores historical revenue patterns, monthly performance, seasonality, and forecasted revenue and demand.

**Key Analytical Areas**
- Monthly Revenue: Actual vs. Forecast
- Revenue Forecast with 95% Confidence Bounds
- Net Items Sold and Demand Forecast
- Monthly Revenue and Month-over-Month Growth

**Key Questions**
- What do historical revenue trends reveal about business growth?
- Are there recurring monthly seasonal patterns?
- Which months show stronger or weaker performance?
- What do the forecasts suggest about future revenue and demand?

### 05 — Supply Chain & Inventory

![Supply Chain and Inventory Dashboard](Dashboards/05%20%E2%80%94%20Supply%20Chain%20%26%20Inventory.png)

Analyzes inventory efficiency, unsold stock, product returns, and distribution center performance to identify opportunities to improve stock allocation and inventory management.

**Key Metrics**
- Return Rate
- Returned Items
- Returned Revenue
- Total Inventory Cost
- Unsold Inventory Cost
- Unsold Inventory Cost %
- Sell-Through Rate

**Key Questions**
- What proportion of inventory cost is tied up in unsold stock?
- Which product categories have the highest unsold inventory cost?
- How do returns vary across categories and years?
- Which distribution centers handle the highest volumes of sold and unsold units?
- Where could inventory allocation be improved?

---

## 🔍 Key Business Insights

The following findings were identified during the analysis.

### 1. Business Performance

- Revenue increased approximately **23× between 2019 and 2023**.
- The reported profit margin remained around **52%**.
- Average Order Value stayed relatively stable at approximately **$86**.
- China, the United States, and Brazil collectively contributed approximately **71% of revenue**.

**Business implication:** Growth appears to be primarily volume-driven, creating an opportunity to explore strategies that increase order value while maintaining profitability.

### 2. Customer Journey & Conversion

| Metric | Result |
|---|---:|
| Browsing Sessions | 681,759 |
| Cart Sessions | 432,146 |
| Purchase Sessions | 181,759 |
| Session-to-Cart Rate | 63.39% |
| Cart-to-Purchase Rate | 42.06% |
| Cart Abandonment Rate | 57.94% |
| Overall Conversion | 26.66% |

**Business implication:** The cart-to-purchase stage represents a potential improvement opportunity. Further analysis could investigate checkout friction, unexpected costs, payment issues, and other possible barriers to completing a purchase.

*Note: These funnel metrics are session-based and should not be interpreted as unique customer counts.*

### 3. Revenue & Demand Forecasting

- Historical revenue shows substantial growth through 2023.
- February displays recurring revenue declines in the analyzed historical periods.
- March shows a recurring rebound in the seasonal pattern.
- Forecasting visuals provide projected revenue and demand alongside confidence bounds.

**Business implication:** Forecasts can help inform inventory planning and operational preparation ahead of expected seasonal changes.

### 4. Inventory Efficiency

| Metric | Result |
|---|---:|
| Total Inventory Cost | $14,063,107.79 |
| Unsold Inventory Cost | $8,854,752.58 |
| Unsold Inventory Cost % | 62.96% |
| Sell-Through Rate | 37.04% |
| Returned Items | 18,232 |
| Returned Revenue | $1,097,306.74 |
| Return Rate | 28.56% |

**Business implication:** A substantial share of inventory cost is associated with unsold stock. Investigating slow-moving categories, stock allocation, and product returns could help reduce inventory exposure and improve operational efficiency.

---

## 🛠️ Tools & Technical Skills

### Tools

- **Microsoft Excel** — Dashboard development and data analysis.
- **Power Query** — Data preparation, cleaning, and transformation.
- **Power Pivot** — Data modeling and relationship management.
- **DAX** — Measures and business calculations.
- **PivotTables & PivotCharts** — Interactive analysis and visualization.

### Technical Skills Demonstrated

- Data Cleaning & Transformation
- Data Modeling & Relationships
- KPI Development
- DAX Measure Creation
- Time Intelligence
- Revenue & Demand Forecasting
- Funnel Analysis
- Inventory & Returns Analysis
- Interactive Dashboard Design
- Business Insight Generation
- Data Storytelling

---

## 🔄 Analytical Approach

The project followed a structured analytics workflow:

1. **Data Preparation** — Prepare and transform data using Power Query.
2. **Data Modeling** — Organize tables and relationships to support consistent calculations.
3. **Business Logic** — Define KPIs and measures aligned with business questions.
4. **Exploratory Analysis** — Investigate revenue, customer journeys, demand, inventory, and returns.
5. **Visualization** — Build interactive dashboard pages with KPIs, charts, and filters.
6. **Insight Generation** — Translate analytical findings into business implications and recommendations.

A key focus throughout the project was validating the logic behind the metrics and ensuring that the data model supported meaningful analysis.

---

## 💡 Business Recommendations

Based on the findings, the following areas deserve further investigation:

- **Improve cart conversion:** Investigate why cart sessions do not progress to purchase and test potential checkout improvements.
- **Increase average order value:** Explore product bundles, complementary product recommendations, and category-specific promotions.
- **Optimize inventory allocation:** Review slow-moving products and compare stock availability with demand across distribution centers.
- **Plan for seasonality:** Use historical trends and forecasts to support inventory and demand planning ahead of seasonal changes.
- **Investigate returns:** Analyze return patterns by category and period to identify opportunities to improve product information, quality, and customer expectations.
- **Monitor key markets:** Evaluate performance across major revenue-contributing countries to identify opportunities for sustainable growth.

These recommendations are potential actions derived from the observed metrics; additional analysis would be required to validate their expected impact.

---

## ⚠️ Important Data Note

**2024 data represents January only** in the dashboard reporting. Comparisons between 2024 and full prior years should therefore be interpreted carefully.

Forecasts are estimates based on historical patterns and should not be treated as guaranteed future results. Forecast assumptions and confidence bounds should be considered when using projections for planning.

---

## 📁 Project Structure

```text
the-look-ecommerce-analytics/
│
├── README.md
│
└── Dashboards/
    ├── 01 — Home Page.png
    ├── 02 — Executive Overview.png
    ├── 03 — Funnel & Traffic Analysis.png
    ├── 04 — Forecasting & Time Intelligence.png
    └── 05 — Supply Chain & Inventory.png
```

*The structure above reflects the dashboard screenshots currently uploaded to the repository. Add the Excel workbook to the repository if you want visitors to download and explore the interactive dashboards.*

---

## 🚀 Getting Started

To explore the project:

1. Open the dashboard screenshots in the `Dashboards` folder.
2. Review the dashboard descriptions and key findings in this README.
3. If the Excel workbook is added to the repository, download it and open it in Microsoft Excel.
4. Navigate through the dashboard pages using the built-in navigation buttons.
5. Explore available filters and slicers to investigate different business dimensions.

**Recommended:** Use a desktop version of Microsoft Excel for the best interactive experience when working with the workbook.

---
## 📥 Download the Excel Project

The complete Excel dashboard and data model are available here:

[Download The Look Analytics Project](https://docs.google.com/spreadsheets/d/1QYQhjvtCdsTfJzRqKXj_EthW9PG0O_5I/edit?usp=sharing&ouid=101856304224110568452&rtpof=true&sd=true)

**File size:** 190 MB
**Tools:** Excel, Power Query, Power Pivot, and DAX
---

---

## 👤 Author

**Youssef Mohamed**

Aspiring Data Analyst interested in Business Intelligence, Data Visualization, and Data-Driven Decision-Making.

This project represents hands-on practice in applying Excel analytics techniques to a fashion e-commerce business scenario.

- **GitHub:** [@youssef-mohamed004](https://github.com/youssef-mohamed004)
- **Project Repository:** [the-look-ecommerce-analytics](https://github.com/youssef-mohamed004/the-look-ecommerce-analytics)
- **LinkedIn:** [Youssef Mohamed](https://www.linkedin.com/in/youssef-mohamed-6038092b2/).

---

## 🙏 Acknowledgments

Special thanks to my instructor and mentor for their guidance, feedback, and support throughout this learning journey.

---

⭐ If you find this project interesting, feel free to explore the dashboards and share your feedback!
