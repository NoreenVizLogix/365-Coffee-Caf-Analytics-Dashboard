<div align="center">

# ☕ 365 Coffee Café Analytics Dashboard

### 📊 Excel-Based Coffee Shop Performance Analytics

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power_Query-217346?style=for-the-badge&logo=powerbi&logoColor=white)]()
[![Pivot Tables](https://img.shields.io/badge/Pivot_Tables-FF6B6B?style=for-the-badge)]()
[![Slicers](https://img.shields.io/badge/Slicers-0176D3?style=for-the-badge)]()

**An interactive Excel dashboard for analyzing coffee shop performance, transaction patterns, and product category insights using Pivot Tables - no DAX required!**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Architecture](#-architecture) • [Insights](#-key-insights) • [Author](#-author)

</div>

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Key Highlights](#-key-highlights)
- [Tech Stack](#-tech-stack)
- [Dataset Information](#-dataset-information)
- [Features](#-features)
- [Business Problem](#-business-problem)
- [Dashboard Goal](#-dashboard-goal)
- [Architecture](#-architecture)
- [Dashboard Walkthrough](#-dashboard-walkthrough)
- [Key Insights](#-key-insights)
- [Business Impact](#-business-impact)
- [Installation & Setup](#-installation--setup)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [File Specifications](#-file-specifications)
- [Screenshots](#-screenshots)
- [Troubleshooting](#-troubleshooting)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 📌 Project Overview

The **365 Coffee Café Analytics Dashboard** is a comprehensive Excel-based analytics solution that helps coffee shop owners and managers analyze business performance, transaction patterns, product popularity, and category contributions.

Built as a **single-file Excel solution**, this project combines raw data, Power Query transformations, Pivot Tables, and interactive visualizations into one cohesive `.xlsx` file - **using only Pivot Tables, no DAX measures required!**

The dashboard transforms coffee shop transaction data into actionable business insights through:
- Monthly revenue tracking
- Product category analysis
- Transaction pattern analysis
- Hourly and daily trends
- Store location performance
- Product type revenue analysis

**Designed for:**
- ☕ Coffee Shop Owners
- 📊 Café Managers
- 💼 Retail Operations Teams
- 📈 Business Analysts
- 🍽️ Hospitality Industry Professionals
- 📚 Data Analytics Students

---

## 🌟 Key Highlights

| Highlight | Details |
|-----------|---------|
| 📁 **Single File Solution** | Data + Dashboard in one `.xlsx` file |
| 📊 **Comprehensive Dataset** | Transaction-level coffee shop data |
| 📊 **Pivot Table Based** | All analysis using Pivot Tables - No DAX |
| 📈 **12+ Visualizations** | Charts, heatmaps, trend analysis |
| ☕ **Multiple Product Categories** | Coffee, Tea, Bakery, Branded items |
| 🏪 **Store Locations** | Multi-store performance analysis |
| 📅 **Monthly Analysis** | January - June 2023 trends |
| 📊 **CAGR Analysis** | 15.31% monthly growth rate |
| 🎛 **Interactive Slicers** | Dynamic filtering capabilities |

---

## 🛠 Tech Stack

This project was built using the following Microsoft Excel technologies:

| Technology | Purpose |
|------------|---------|
| 📊 **Microsoft Excel** | Main platform for dashboard |
| 🔄 **Power Query** | Data cleaning & transformation |
| 📊 **Pivot Tables** | Data summarization and analysis |
| 🎛 **Slicers** | Interactive filtering |
| 🎨 **Conditional Formatting** | Dynamic visual indicators |
| 📈 **Pivot Charts** | Data visualization |
| 📁 **File Format** | `.xlsx` (Excel 2016+) |

> ✅ **No DAX or Power Pivot Required!** This dashboard uses only Pivot Tables and works on standard Excel versions.

---

## 📂 Dataset Information

The dashboard uses a coffee shop transaction dataset with 11 columns for comprehensive analysis.

### Dataset Schema (11 Columns)

| # | Column Name | Data Type | Description | Example |
|---|-------------|-----------|-------------|---------|
| 1 | `Transaction_ID` | Integer | Unique transaction identifier | 1001 |
| 2 | `Date` | Date | Transaction date | 2023-01-15 |
| 3 | `Month` | Text | Month of transaction | January |
| 4 | `Year` | Integer | Year of transaction | 2023 |
| 5 | `Day_of_Week` | Text | Day of the week | Monday |
| 6 | `Hour` | Integer | Hour of transaction (6-20) | 9 |
| 7 | `Store_Location` | Text | Store location | Tipu Sultan |
| 8 | `Product_Name` | Text | Product purchased | Barista Espresso |
| 9 | `Product_Category` | Text | Product category | Coffee |
| 10 | `Transaction_Count` | Integer | Number of transactions | 1 |
| 11 | `Revenue` | Decimal | Revenue amount | $5.50 |

### Data Distribution

| Metric | Value |
|--------|-------|
| Total Records | Varies by period |
| Time Period | January - June 2023 |
| Product Categories | Coffee, Tea, Bakery, Branded, etc. |
| Total Revenue | $166,486 (June 2023) |
| Monthly Growth Rate | 15.31% CAGR |
| Store Locations | Multiple (including Tipu Sultan) |
| Product Types | 15+ |

---

## ✨ Features

### 📊 Dashboard Features

- ✅ **Executive KPI Cards** - Total Revenue, Growth Rate, CAGR
- ✅ **Monthly Revenue Trend** - January to June 2023
- ✅ **Product Category Analysis** - Category performance breakdown
- ✅ **Top 15 Product Types** - Revenue and transaction analysis
- ✅ **Store Location Analysis** - Branded category performance
- ✅ **Hourly Heatmap** - Transaction patterns by hour and day
- ✅ **Day of Week Analysis** - Daily transaction patterns
- ✅ **Category Contribution** - Transaction volume by category
- ✅ **Growth Rate Tracking** - 15.31% monthly CAGR

### 🔧 Technical Features

- ✅ Single-file Excel solution
- ✅ Power Query data transformation
- ✅ Pivot Tables for all calculations
- ✅ Slicers for interactive filtering
- ✅ Conditional formatting with color coding
- ✅ Dynamic charts and visualizations
- ✅ Cross-filtering between visuals

---

## 📌 Business Problem

Coffee shop owners face challenges in analyzing business performance without a centralized analytics solution. Key questions that remain unanswered:

- ❓ What is the monthly revenue trend?
- ❓ What is the business growth rate (CAGR)?
- ❓ Which product categories drive the most revenue?
- ❓ Which products are top performers?
- ❓ How does store location performance compare?
- ❓ What are the peak transaction hours?
- ❓ Which days of the week perform best?
- ❓ Which categories have low contribution?
- ❓ How can product mix be optimized?
- ❓ Where are growth opportunities?

**Manual analysis of transaction data is:**
- ⏰ Time-consuming
- 💰 Expensive
- ❌ Prone to errors
- 📉 Lacks actionable insights

---

## 🎯 Dashboard Goal

The objective of this dashboard is to provide a **centralized, single-file reporting solution** that helps coffee shop businesses:

- 📊 Monitor monthly revenue performance
- 📈 Track business growth rate (CAGR)
- ☕ Analyze product category performance
- 🏪 Identify high and low performing store locations
- 📅 Understand hourly and daily transaction patterns
- 💰 Optimize product mix and inventory
- 🎯 Support data-driven business decisions
- 📉 Identify areas for improvement
- 📈 Drive revenue growth strategies

---

## 🏗 Architecture

### Single-File Structure

```
┌─────────────────────────────────────────────────────┐
│   365_Coffee_Cafe_Analytics.xlsx                    │
│                                                     │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 1: Dataset                             │   │
│  │ (Raw Data - Transaction Data)                │   │ 
│  └──────────────────────────────────────────────┘   │
│              ↓ (Power Query)                        │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 2: Pivot_Tables                        │   │
│  │ (Data Summarization)                         │   │
│  └──────────────────────────────────────────────┘   │  
│              ↓                                      │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 3: Coffee Cafee Dashboard              │   │
│  │ (Executive Dashboard)                        │   │
│  └──────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

### Data Flow

```
Raw Data → Power Query (Clean) → Pivot Tables → Dashboard
```

---

## 📊 Dashboard Walkthrough

### Coffee Café Analytics Dashboard

<img src="Coffee Caffee.png" width="100%">

*Figure 1: 365 Coffee Café Analytics Dashboard - Complete Overview*

#### Executive KPI Cards

| KPI | Value | Description |
|-----|-------|-------------|
| 💰 **Total Revenue** | $166,486 | Revenue for June 2023 |
| 📈 **CAGR** | 15.31% | Monthly Compound Annual Growth Rate |
| ☕ **Total Transactions** | ~149,000 | Total transactions in period |

#### Monthly Revenue Trend (January - June 2023)

| Month | Revenue | MoM Growth |
|-------|---------|------------|
| January | $81,678 | - |
| February | $76,145 | -6.77% |
| March | $98,835 | +29.80% |
| April | $118,941 | +20.34% |
| May | $156,728 | +31.75% |
| June | $166,486 | +6.22% |

**Key Insight:** Overall company progress is in an **Upward Trend** with a **15.31% monthly CAGR**.

#### Product Category Contribution

| Category | Transactions | % of Total |
|----------|--------------|------------|
| Coffee | 63,000+ | ~42% |
| Tea | 38,000+ | ~25% |
| Bakery | 25,000+ | ~18% |
| Branded | 12,000+ | ~8% |
| Other | 10,000+ | ~7% |

**Key Insight:** Coffee, Tea, and Bakery collectively account for approximately **85% of total transactions** (126,661 individual sales).

---

## 📊 Top 15 Product Types by Revenue

| Rank | Product Name | Revenue |
|------|--------------|---------|
| 1 | **Barista Espresso** | $91,406 |
| 2 | **Brewed Chai Tea** | $77,082 |
| 3 | **Hot Chocolate** | $72,416 |
| 4 | **Gourmet Brewed Coffee** | $70,035 |
| 5 | **Brewed Black Tea** | $47,932 |
| 6 | **Brewed Herbal Tea** | $47,540 |
| 7 | **Premium Brewed Coffee** | $38,781 |
| 8 | **Organic Brewed Coffee** | $37,747 |
| 9 | **Spice** | $36,866 |
| 10 | **Drip Coffee** | $31,984 |
| 11 | **Pastry** | $25,656 |
| 12 | **Brewed Green Tea** | $23,853 |
| 13 | **Biscotti** | $19,794 |
| 14 | **Regular Syrup** | $6,085 |
| 15 | **Sugar Free Syrup** | $2,324 |

### 🚀 Top 5 Revenue Drivers

| Rank | Product | Revenue | Category |
|------|---------|---------|----------|
| 1 | Barista Espresso | $91,406 | Coffee |
| 2 | Brewed Chai Tea | $77,082 | Tea |
| 3 | Hot Chocolate | $72,416 | Other |
| 4 | Gourmet Brewed Coffee | $70,035 | Coffee |
| 5 | Brewed Black Tea | $47,932 | Tea |

---

## 🏪 Store Location Analysis

### Tipu Sultan Area Insights

| Metric | Value |
|--------|-------|
| **Branded Category Contribution** | 15.93% of total transactions |
| **Other Areas Branded Contribution** | ~40% |
| **Gap (Branded vs Other)** | ~24% lower |
| **Action Required** | High - Investigate and improve |

### Comparison: Branded Category % by Location

| Store Location | Branded % | Status |
|----------------|-----------|--------|
| Location 1 | 34.28% | ✅ Above Avg |
| Location 2 | 35.78% | ✅ Above Avg |
| Location 3 | 31.97% | ✅ Average |
| Location 4 | 37.50% | ✅ Above Avg |
| Location 5 | 21.94% | ⚠️ Below Avg |
| Location 6 | 28.64% | ⚠️ Below Avg |
| Location 7 | 28.43% | ⚠️ Below Avg |
| Location 8 | 37.35% | ✅ Above Avg |
| Location 9 | 34.56% | ✅ Above Avg |
| Location 10 | 33.61% | ✅ Average |
| Location 11 | 33.41% | ✅ Average |
| Location 12 | 32.81% | ✅ Average |
| Location 13 | 41.07% | ✅ Excellent |
| Location 14 | 40.08% | ✅ Excellent |
| **Tipu Sultan** | **15.93%** | 🔴 **Critical - Needs Review** |
| Location 15 | 40.45% | ✅ Excellent |

**Key Insight:** In the Tipu Sultan area, the Branded category shows a disproportionately low contribution, accounting for just **15.93%** of total transactions, signaling a potential area for review.

---

## 📅 Hourly Transaction Pattern

### Peak Hours Analysis

| Hour | Transaction Volume | Status |
|------|-------------------|--------|
| 6 AM | Low | ⏰ Opening |
| 7 AM | Medium | Morning Rush Start |
| 8 AM | High | Peak Morning |
| 9 AM | High | Peak Morning |
| 10 AM | High | Morning Peak |
| 11 AM | High | Pre-Lunch |
| 12 PM | Medium | Lunch |
| 1 PM | Medium | Post-Lunch |
| 2 PM | Medium | Afternoon |
| 3 PM | Medium | Afternoon |
| 4 PM | Medium | Pre-Evening |
| 5 PM | High | Evening Rush |
| 6 PM | High | Evening Peak |
| 7 PM | Medium | Evening |
| 8 PM | Low | Closing |

### Day of Week Analysis

| Day | Transaction Volume | Performance |
|-----|-------------------|-------------|
| Monday | High | ⭐ Busiest |
| Tuesday | High | ⭐ Second Busiest |
| Wednesday | Medium | Average |
| Thursday | Medium | Average |
| Friday | Medium | Average |
| Saturday | Low | Weekend Low |
| Sunday | Low | Weekend Low |

---

## 💡 Key Insights

### 🚀 Growth Opportunities

| # | Finding | Impact | Recommended Action |
|---|---------|--------|---------------------|
| 1 | 🚀 **15.31% monthly CAGR** | Excellent | Maintain growth momentum |
| 2 | 🚀 **Revenue grew to $166,486** | Positive | Invest in top performing products |
| 3 | 🚀 **Coffee, Tea, Bakery = 85% transactions** | High | Focus marketing on these categories |
| 4 | 📈 **Barista Espresso top revenue ($91,406)** | High | Feature prominently in promotions |
| 5 | 📈 **June revenue up 6.22% MoM** | Positive | Continue current strategy |

### 📉 Areas for Improvement

| # | Finding | Impact | Recommended Action |
|---|---------|--------|---------------------|
| 1 | 🔴 **Tipu Sultan Branded category only 15.93%** | Critical | Investigate location-specific issues |
| 2 | ⚠️ **February showed decline (-6.77%)** | Medium | Analyze seasonal patterns |
| 3 | ⚠️ **Branded category underperforming** | Medium | Increase branding and awareness |
| 4 | ⚠️ **Weekend transactions lower** | Low | Weekend promotional offers |
| 5 | ⚠️ **Evening hours need optimization** | Low | Evening special offers |

### 📊 Key Performance Metrics

| Metric | Value | Status |
|--------|-------|--------|
| Total Revenue (June) | $166,486 | ✅ Excellent |
| Monthly CAGR | 15.31% | 🟢 Exceptional |
| Top Product Revenue | $91,406 | 🟢 Strong |
| Category Contribution | 85% (Coffee/Tea/Bakery) | 🟢 Strong |
| Branded % Tipu Sultan | 15.93% | 🔴 Critical |
| Average Branded % | ~40% | 🟢 Good |

---

## 💼 Business Impact

### 📈 Strategic Benefits

#### 1. Revenue Growth Tracking
- Monitor monthly revenue trends
- Track 15.31% CAGR performance
- Identify growth patterns and seasonality

#### 2. Product Optimization
- Identify top performing products
- Optimize product mix for maximum revenue
- Feature top sellers in promotions

#### 3. Category Management
- Understand category contribution (85% from Coffee/Tea/Bakery)
- Improve Branded category performance
- Balance product portfolio

#### 4. Store Location Strategy
- Address Tipu Sultan Branded category gap
- Share best practices across locations
- Optimize location-specific strategies

#### 5. Operational Optimization
- Understand peak transaction hours
- Staff scheduling optimization
- Inventory management based on demand

#### 6. Day of Week Planning
- Optimize staffing for busy days (Monday-Tuesday)
- Weekend promotional strategies
- Weekly performance monitoring

#### 7. Data-Driven Decisions
- Real-time KPI monitoring
- Executive-level reporting
- Self-service analytics for teams

---

## 🚀 Installation & Setup

### Prerequisites

- Microsoft Excel 2016 or later
- Windows or Mac OS
- ~10 MB free disk space
- Power Query enabled (default in Excel 2016+)

> ✅ **No Add-ins Required!** This dashboard works with standard Excel with Pivot Tables.

### Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/NoreenVizLogix/365-Coffee-Cafe-Analytics.git

# 2. Navigate to project folder
cd 365-Coffee-Cafe-Analytics

# 3. Open the Excel file
# Double-click 365_Coffee_Cafe_Analytics.xlsx
# OR
start 365_Coffee_Cafe_Analytics.xlsx
```

### File Structure After Download

```
365-Coffee-Cafe-Analytics/
│
├── Dashboard/
│   └── 365_Coffee_Cafe_Analytics.xlsx  ← Main file (Data + Dashboard)
│
├── Requirements/
│   └── 365 Coffee Cafe.pdf  ← Raw data (optional)
│
├── Images/
│   └── Coffee Caffee.png  ← Dashboard screenshot
│
└── README.md
```

---

## 📖 How to Use

### Step 1: Open the File
- Open `365_Coffee_Cafe_Analytics.xlsx`
- Enable editing if prompted

### Step 2: Navigate to Dashboard
- Click on sheet tab **"Coffee Cafee Dashboard"** at the bottom
- View the complete analytics dashboard

### Step 3: Analyze KPIs
- Review total revenue and CAGR
- Check monthly revenue trend
- Understand overall business performance

### Step 4: Explore Product Categories
- Review category contribution (Coffee, Tea, Bakery)
- Analyze top 15 product types
- Identify revenue drivers

### Step 5: Store Location Analysis
- Review Tipu Sultan performance (15.93% Branded)
- Compare locations
- Identify improvement areas

### Step 6: Transaction Patterns
- Analyze hourly transaction patterns
- Review day of week performance
- Optimize operations

### Step 7: Use Slicers
- Click on any slicer to filter data
- All charts update automatically
- Drill down into specific segments

### Step 8: View Raw Data
- Click on **"Dataset"** tab
- See all transaction records
- Use filters to explore specific segments

### Step 9: Modify as Needed
- Update data in Dataset sheet
- Click `Data` → `Refresh All`
- Dashboard updates automatically

---

## 📂 Project Structure

```
365-Coffee-Cafe-Analytics/
│
├── Dashboard/
│   └── 365_Coffee_Cafe_Analytics.xlsx  ← Main Excel file
│       ├── Sheet 1: Dataset (Raw Data)
│       ├── Sheet 2: Pivot_Tables (Data Summarization)
│       └── Sheet 3: Coffee Cafee Dashboard (Executive Dashboard)
│
├── Requirements/
│   └── 365 Coffee Cafe.pdf  
│
├── Images/
│   └── Coffee Caffee.png  ← Dashboard screenshot
│
└── README.md  ← This file
```

---

## 📋 File Specifications

| Property | Value |
|----------|-------|
| 📁 File Name | `365_Coffee_Cafe_Analytics.xlsx` |
| 📊 File Type | Excel Workbook (.xlsx) |
| 💾 File Size | ~2-3 MB |
| 📋 Sheets | 3 sheets |
| 📈 Columns | 11 columns |
| 📊 Pivot Tables | 8+ |
| 🎛 Slicers | 4+ |
| 📈 Charts | 12+ |
| 🎨 Theme | Coffee Café (Warm colors) |
| 📅 Version | 1.0.0 |
| 📅 Last Updated | July 2026 |

---

## 📸 Screenshots

### Coffee Café Analytics Dashboard

<img src="Coffee Caffee.png" width="100%">

*Figure 1: 365 Coffee Café Analytics Dashboard - Complete Overview*

**Includes:**
- 💰 3 KPI Cards (Total Revenue, CAGR, Transactions)
- 📈 Monthly Revenue Trend (Jan-Jun 2023)
- ☕ Category Contribution Analysis
- 🏆 Top 15 Product Types by Revenue
- 🏪 Store Location Analysis (Tipu Sultan)
- 📅 Hourly Transaction Heatmap
- 📊 Day of Week Analysis
- 🎛 Interactive Slicers

---

## ⚠️ Troubleshooting

| Issue | Possible Solution |
|-------|-------------------|
| **"Slicers not working"** | Enable macros and active content. Go to `File` → `Options` → `Trust Center` → `Enable all macros` |
| **"Refresh fails"** | Check file path and permissions. Ensure data source is accessible |
| **"Charts show #N/A"** | Refresh all data connections: `Data` → `Refresh All` |
| **"Cannot open file"** | Ensure Excel 2016+ and enable editing if downloaded from web |
| **"Pivot Tables not showing"** | Verify data range is correct and refresh pivot tables |
| **"Performance is slow"** | Close other applications, reduce data if needed |
| **"Category filters not working"** | Check if slicer is properly connected to all PivotTables |
| **"Heatmap not displaying"** | Ensure data has proper hour and day columns |
| **"Conditional formatting lost"** | Re-apply formatting rules from the Pivot_Tables sheet |
| **"Data not updating"** | Check if data range references are correct |

---

## 🔮 Future Enhancements

- [ ] Add predictive sales forecasting
- [ ] Add customer segmentation analysis
- [ ] Add competitor analysis
- [ ] Create Power BI version
- [ ] Add inventory optimization
- [ ] Add automated email reports
- [ ] Create mobile-optimized version
- [ ] Add customer loyalty analysis
- [ ] Add seasonal trend analysis
- [ ] Integrate with POS systems
- [ ] Add What-If analysis scenarios
- [ ] Add menu optimization analysis

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Ideas
- 🐛 Bug fixes
- 📊 Additional visualizations
- 📝 Documentation improvements
- 🌍 Translations
- 🎨 UI/UX improvements
- 🎛 New slicer configurations

---

## 📞 Support

If you have any questions or need help:

- 📧 **Email:** noreensajjad70@gmail.com
- 💼 **LinkedIn:** [Noreen Raheel](https://www.linkedin.com/in/noreen-raheel-data-analyst)
- 🐛 **Issues:** [GitHub Issues](https://github.com/NoreenVizLogix/365-Coffee-Cafe-Analytics/issues)

---

## 👤 Author

<div align="center">

### **Noreen Raheel**

**Data Analyst | Excel & Power BI Expert**

[![Email](https://img.shields.io/badge/Email-noreensajjad70@gmail.com-red?style=flat-square&logo=gmail)](mailto:noreensajjad70@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Noreen_Raheel-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/noreen-raheel-data-analyst)
[![GitHub](https://img.shields.io/badge/GitHub-NoreenVizLogix-black?style=flat-square&logo=github)](https://github.com/NoreenVizLogix)

</div>

---

## ⭐ Show Your Support

If you found this dashboard useful, please give it a **Star ⭐** on GitHub!

<div align="center">

### 🌟 Star this repository 🌟

[![GitHub stars](https://img.shields.io/github/stars/NoreenVizLogix/365-Coffee-Cafe-Analytics.svg?style=social&label=Star)](https://github.com/NoreenVizLogix/365-Coffee-Cafe-Analytics)

**Made with ❤️ by Noreen Raheel**

</div>

---

## 📌 Tags

`excel` `dashboard` `data-visualization` `coffee-shop-analytics` `cafe-analytics` `retail-analytics` `business-intelligence` `transaction-analysis` `product-analysis` `power-query` `pivot-tables` `coffee-dashboard` `excel-dashboard` `data-modeling` `slicers` `kpi-tracking` `microsoft-excel` `hospitality-analytics`

---

## 🙏 Acknowledgments

- Microsoft Excel team for amazing tools
- Power Query community
- Coffee shop industry research
- All contributors and supporters
- Open source community

---

<div align="center">

**☕ If you like this project, don't forget to ⭐ the repository! ☕**

[⬆ Back to Top](#-365-coffee-café-analytics-dashboard)

</div>
