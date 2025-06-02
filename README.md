# 📊 Business Intelligence 360 Dashboard

## 🎯 Project Overview
AtliQ Hardware has experienced rapid growth and decided to implement comprehensive Data Analytics using Power BI to outperform competitors and enable data-driven decision making. This dashboard addresses stakeholder questions across Finance, Sales, Marketing, and Supply Chain operations.

## 🔗 Live Report Link
[View Interactive Dashboard](#)

## 🛠️ Technology Stack
- **Database**: SQL
- **Visualization**: Power BI Desktop
- **Data Processing**: Excel
- **Analytics**: DAX Language
- **Optimization**: DAX Studio
- **Documentation**: Project Charter

## 📚 Power BI Skills Implemented

### 🔧 Core Development
- Pre-project stakeholder requirement analysis
- Calculated columns and DAX measures creation
- Comprehensive data modeling architecture
- Visual switching with bookmarks
- Interactive page navigation systems

### 📈 Advanced Features
- Zero division error prevention using DIVIDE function
- M language date table generation
- Dynamic filtering-based titles
- KPI performance indicators
- Conditional formatting with icons and colors
- Data validation frameworks

### ☁️ Power BI Services
- Report publishing and deployment
- Personal Gateway configuration for auto-refresh
- Power BI App development
- Workspace collaboration and access management

## 💼 Business Terminology

| Term | Description |
|------|-------------|
| **Gross Price** | Initial product pricing |
| **Pre-Invoice Deductions** | Discounts before invoicing |
| **Post-Invoice Deductions** | Adjustments after invoicing |
| **Net Invoice Sale** | Final invoice amount |
| **Gross Margin** | Revenue minus direct costs |
| **COGS** | Cost of Goods Sold |
| **YTD/YTG** | Year to Date/Year to Go |

## 🏢 Company Background
AtliQ Hardware operates globally through three distribution channels:
- 🏪 **Retailers**: Third-party retail partners
- 🎯 **Direct**: Company-owned sales channels  
- 🚚 **Distributors**: Wholesale distribution network

The company faced significant losses from data-poor expansion decisions, prompting this analytics transformation initiative.

## 🗂️ Data Architecture

### 📊 Dataset Structure
**Dimension Tables** (Static Reference Data)
- `dim_customer`: 75 customers across 27 markets
- `dim_market`: Geographic segmentation (APAC, EU, LATAM)
- `dim_product`: Product hierarchy and categories

**Fact Tables** (Transaction Data)
- `fact_forecast_monthly`: Demand forecasting data
- `fact_sales_monthly`: Actual sales transactions
- Supporting cost and pricing tables

## 📁 Dashboard Architecture & Analytics

### 1. 🏠 Navigation Hub
* Developed centralized **dashboard navigation system** with sectioned access to all analytical views
* Implemented **Info & Support modules** using Power BI bookmarks
* Integrated dataset documentation and schema references for user guidance

### 2. 💰 Financial Analytics
**Visualization Components:**
* KPI cards with conditional formatting: Net Sales, Gross Margin %, Net Profit % (vs Target/Previous Year)
* P&L statement matrix displaying Current Year, Previous Year/Target, Change metrics, % variance
* Product and customer performance rankings by profitability
* Time-series area charts for trend analysis

**Business Intelligence:**
* **140–354% Net Sales expansion** across 2019-2022 period
* **Negative net profit margins** post-2019 attributed to **elevated operational expenses** from market expansion strategy

### 3. 📈 Sales Performance Analytics
**Visualization Components:**
* Dynamic scatter plot: Net Sales vs Gross Margin % with toggle functionality
* Percentage breakdown donuts: Net Sales, Gross Margin, Invoice Deductions, COGS distribution
* Customer and product profitability matrix with drill-down capabilities

**Business Intelligence:**
* **Notebook category** captured **42.5% market share** in 2022 sales
* **Amazon partnership** generated **$496.88M revenue**, while **Relief** demonstrated superior margin performance

### 4. 📢 Marketing Intelligence
**Visualization Components:**
* Toggle-enabled scatter analysis: Gross Margin % or Net Profit % vs Net Sales
* Waterfall visualization: Gross Margin flow to Net Profit through operational expenses
* Market segment and regional performance matrices

**Business Intelligence:**
* **Universal negative profitability** across all regions in 2022 due to **operational expenses exceeding gross margins**

### 5. 🚚 Supply Chain Analytics
**Visualization Components:**
* Forecast accuracy KPI cards: Forecast Accuracy %, Net Error, Absolute Error metrics
* Customer and product-level forecast performance matrices
* Forecast trend visualizations with error analysis

**Business Intelligence:**
* **December 2021** recorded **highest forecast deviation** with **81.5% accuracy rate**
* **FY2021** experienced **peak absolute forecast error (~$10M)**

### 6. 🧑‍💼 Executive Dashboard
**Visualization Components:**
* Composite KPI cards with color-coded growth indicators
* Multi-chart trend analysis: Column, Line, Area, Ribbon, Bar combinations
* Sub-regional performance matrices with top/bottom performer rankings

**Business Intelligence:**
* **Retail channel dominance** at **70.5% revenue contribution**; **P&A Division** represents **49.9% of business**
* **6% market share achievement** by 2022 despite operational losses, validating strategic growth approach

## 🛠️ Technical Implementation

### 🔗 Data Engineering
* Established **MySQL-Power BI connectivity** with local database integration
* Executed data quality assurance, cleansing protocols, and **fact/dimension table architecture**
* Engineered fiscal calendar dimension with Fiscal Year/Month calculations
* Implemented **data validation frameworks** including cross-tabulation and user acceptance testing

### ⚙️ Data Architecture
* Constructed **snowflake schema** with optimized one-to-many relationships
* Performance-tuned model by disabling unnecessary data loads
* Developed YTD/YTG analytical columns for sales progression tracking

### 📐 Advanced Analytics (DAX)
**25+ Custom Measures Including:**
* Core KPIs: `Net Sales`, `Gross Margin`, `Net Profit`, `Forecast Accuracy`, `Net Error`, `ABS Error`
* P&L Analytics: `P&L YoY Change %`, `Operational Expense`, `Revenue Contribution %`
* Comparative Analysis: `vs Previous Year`, `vs Target` variants
* UX Enhancement: Dynamic titles, slicer labels, toggle measures, quarter calculations

### 🧰 Power BI Advanced Features
* **DAX Studio**: Model optimization and performance enhancement
* **Bookmark System**: Toggle functionality, info panels, visual interactivity
* **Dynamic Filtering**: Benchmark comparisons, product/customer segmentation
* **Power BI Service**: Report deployment, gateway configuration, automated refresh, app workspace management

### 📈 Visualization Techniques
* Waterfall, Ribbon, Area, and Line chart implementations
* Conditional formatting KPI cards
* Dynamic matrix with responsive column naming
* Custom tooltips for detailed metric exploration

## 🎯 Technical Competencies Gained
* **Stakeholder Simulation**: End-to-end business intelligence project lifecycle management
* **Performance Optimization**: Power BI data modeling, query optimization, and visual design best practices
* **Advanced DAX Mastery**: Complex business metric calculations and interactive dashboard functionality


## 🎯 Business Impact
This comprehensive analytics solution enables:
- **Data-Driven Decisions**: Replace intuition-based choices with factual insights
- **Performance Monitoring**: Real-time tracking across all business functions
- **Strategic Planning**: Informed expansion and investment decisions
- **Competitive Advantage**: Analytics-powered market positioning

---

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-FF6B35?style=for-the-badge&logoColor=white)

**⭐ Star this repository if you found it helpful!**

</div>
