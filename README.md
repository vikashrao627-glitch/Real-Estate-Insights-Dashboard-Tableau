# 🏠 Real Estate Insights Dashboard | Tableau

<p align="center">

### 📊 Interactive Real Estate Market Analytics Dashboard

**Transforming Real Estate Data into Actionable Business Insights**

</p>

<p align="center">


\

</p>

---

# 📌 Project Overview

The **Real Estate Insights Dashboard** is an interactive Business Intelligence project developed using **Tableau** to analyze real estate sales data from **2011 to 2022**.

The project transforms raw real estate transaction data into an interactive dashboard that helps users understand:

* 📈 Sales trends
* 🏘️ Town-level performance
* 🏠 Property type distribution
* 💰 Average sale values
* 🗺️ Geographic sales patterns
* 📊 Sales ratio performance
* 🏡 Residential market composition

The main objective is to convert raw transactional data into **clear, interactive, and business-focused insights**.

---

# 🎯 Business Objective

The goal of this project is to provide a centralized analytical dashboard for understanding real estate market performance.

The dashboard helps answer important business questions such as:

* How are real estate sales changing over time?
* Which towns generate the highest sales?
* Which locations have higher average sale values?
* Which property types dominate the market?
* How does residential property distribution vary by location?
* Which areas have higher or lower sales ratios?
* What geographic patterns can be observed in the market?

---

# 📊 Dashboard

## 🔗 Live Tableau Dashboard

### 👉 [View Interactive Real Estate Dashboard](https://public.tableau.com/app/profile/vikash.rao/viz/Real_Estate_sale/Dashboard?publish=yes)

The dashboard includes interactive filters, charts, maps, KPI cards, calculated fields, and dashboard actions.

---

## 🖼️ Dashboard Preview

<p align="center">

<img src="Images/real-estate-dashboard.png" alt="Real Estate Insights Dashboard" width="100%">

</p>

> **Note:** Make sure the screenshot filename matches the actual image stored inside your `Images` folder.

---

# 📅 Dataset

### Analysis Period

**2011 – 2022**

The dataset contains real estate transaction information used to analyze sales performance across different locations, property types, and residential categories.

---

# 📌 Key KPIs

The dashboard provides high-level KPIs to quickly understand overall market performance.

| KPI                    | Description                             |
| ---------------------- | --------------------------------------- |
| 💰 Total Sales         | Total value of recorded property sales  |
| 🏷️ Average Sale Price | Average value of property transactions  |
| 🏠 Total Transactions  | Number of recorded transactions         |
| 📊 Average Sales Ratio | Average sales ratio across transactions |
| 🏘️ Property Count     | Number of properties/records analyzed   |

These KPIs provide a quick overview before users move into detailed analysis.

---

# 📈 Dashboard Features

## 1️⃣ KPI Cards

The dashboard provides a high-level market summary through KPI cards.

Key metrics include:

* Total Sales
* Average Sale Price
* Total Transactions
* Average Sales Ratio

These metrics allow users to understand the market at a glance.

---

# 2️⃣ Sales Trend Analysis

A time-series visualization analyzes real estate sales performance between:

**2011 → 2022**

This helps identify:

* Long-term market movement
* Sales growth patterns
* Changes in transaction activity
* Market performance over time

### 🔎 Key Insight

The overall analysis shows a **positive sales trend** during the analyzed period.

---

# 3️⃣ Geographic Sales Analysis

The dashboard includes an interactive geographic map for analyzing sales performance across towns.

Users can identify:

* High-performing locations
* Sales concentration
* Geographic patterns
* Differences between towns

The map allows users to visually explore the distribution of real estate sales.

---

# 4️⃣ Sales by Town

A comparative bar chart is used to analyze sales performance across different towns.

### 🔎 Key Insight

**Fort Collins** is identified as one of the strongest-performing towns based on overall sales performance.

This indicates that location has a significant role in real estate sales distribution.

---

# 5️⃣ Property Type Analysis

Property types are analyzed to understand the overall composition of the real estate market.

### 🔎 Key Insight

**Single Family** properties are the dominant property type within the analyzed dataset.

The documented analysis shows an approximate total sale amount of:

### 💰 2,731,147

for the Single Family category.

---

# 6️⃣ Residential Type Analysis

A treemap visualization is used to analyze residential categories across towns.

It helps identify:

* Dominant residential categories
* Location-level differences
* High-volume segments
* Market composition

---

# 7️⃣ Average Sale Value Analysis

Average sale values are compared across different towns.

### 🔎 Key Insight

**Hot Springs** is identified as having the highest average sale value, at approximately:

### 💰 9,179.54

This highlights a significant difference in average property transaction values between locations.

---

# 8️⃣ Sales Ratio Analysis

Sales ratios are analyzed to compare performance across locations.

### 🔎 Key Findings

* **Bellingham** — highest sales ratio
* **Asheville** — lowest sales ratio

These differences highlight variations in market performance across locations.

---

# 🎛️ Interactive Features

The dashboard is designed to provide an interactive analytical experience.

## 🔍 Filters

Users can filter the dashboard based on available dimensions such as:

* Town
* Year
* Property Type
* Residential Type
* Sale Amount

---

## 🔄 Dashboard Actions

### Filter Action

Selecting a specific town can filter related visualizations.

```text
Select Town
     ↓
Related Charts Update
     ↓
Market Analysis Changes
```

---

### Highlight Action

Users can highlight selected towns or categories across multiple visualizations.

This makes comparisons easier.

---

### URL Action

The dashboard also supports dynamic URL-based navigation for selected locations.

```text
Select Location
      ↓
Dashboard Action
      ↓
External Location Information
```

---

# 📖 Dashboard Storytelling

The project is structured around three major analytical perspectives.

---

## 📍 Story 1 — Market Overview

### Includes

* KPI Cards
* Sales Trend
* Property Distribution

### Business Question

> What is the overall performance and trend of the real estate market?

---

## 📍 Story 2 — Geographic Performance

### Includes

* Geographic Map
* Sales by Town
* Average Sale Analysis

### Business Question

> Which locations are performing strongly?

---

## 📍 Story 3 — Property Market

### Includes

* Property Type Analysis
* Residential Type Analysis
* Sales Distribution

### Business Question

> Which property categories dominate the real estate market?

---

# 🧮 Calculated Fields

Tableau calculated fields were used to create analytical metrics.

## Total Sales

```tableau
SUM([Sale Amount])
```

---

## Average Sale Amount

```tableau
AVG([Sale Amount])
```

---

## Property Count

```tableau
COUNT([Property ID])
```

These calculations support the KPI cards and dashboard visualizations.

---

# 🛠️ Tools & Technologies

| Tool / Technology        | Purpose                               |
| ------------------------ | ------------------------------------- |
| 📊 **Tableau**           | Dashboard development                 |
| 🗺️ **Tableau Maps**     | Geographic analysis                   |
| 🧮 **Calculated Fields** | KPI and metric calculations           |
| 🎛️ **Parameters**       | Interactive analysis                  |
| 🔄 **Dashboard Actions** | Filter and highlight interactions     |
| 📑 **Excel**             | Data preparation / source data        |
| 💻 **GitHub**            | Project version control and portfolio |

---

# 📊 Visualization Techniques

This project demonstrates practical Tableau visualization techniques including:

* KPI Cards
* Bar Charts
* Line Charts
* Pie Charts
* Treemaps
* Geographic Maps
* Tables
* Filters
* Parameters
* Dashboard Actions
* Interactive Storytelling

---

# 🔄 Project Workflow

```text
Raw Real Estate Data
        ↓
Data Preparation
        ↓
Data Exploration
        ↓
Data Quality Checks
        ↓
Geographic Analysis
        ↓
Time-Series Analysis
        ↓
Calculated Fields
        ↓
Interactive Visualizations
        ↓
Dashboard Development
        ↓
Business Insights
        ↓
Tableau Public
```

---

# 🧹 Step 1 — Data Preparation

The dataset was prepared for analytical visualization.

Key activities included:

* Reviewing dataset fields
* Checking data types
* Reviewing geographic fields
* Checking data quality
* Preparing dimensions and measures

---

# 🔍 Step 2 — Exploratory Data Analysis

The dataset was explored to understand:

* Sales distribution
* Property types
* Town performance
* Residential categories
* Sales trends
* Average sale values

---

# 📍 Step 3 — Geographic Analysis

Geographic analysis was performed to identify differences in real estate performance across towns.

This included:

* Town-level sales
* Geographic sales distribution
* Average sale values
* Sales ratio comparison

---

# 📈 Step 4 — Trend Analysis

A time-series analysis was created to understand changes in sales performance between 2011 and 2022.

This helped identify long-term market patterns.

---

# 🧮 Step 5 — Calculated Metrics

Calculated fields were created to support:

* Total Sales
* Average Sale Amount
* Property Count
* Sales Ratio Analysis

---

# 🎨 Step 6 — Dashboard Development

Individual visualizations were combined into an interactive Tableau dashboard.

The dashboard contains:

* KPI cards
* Maps
* Charts
* Filters
* Property analysis
* Town analysis
* Residential analysis

---

# 📖 Step 7 — Business Storytelling

The dashboard was structured into three major analytical stories:

1. Market Overview
2. Geographic Performance
3. Property Market

This makes the analysis easier for business users to understand.

---

# 💡 Key Business Insights

## 🥇 1. Strong Town-Level Performance

Fort Collins demonstrates strong overall sales performance.

This suggests that the location may represent an important market within the analyzed dataset.

---

## 📈 2. Positive Sales Trend

The overall sales trend from 2011 to 2022 shows positive movement.

However, sales volume and average transaction value should be analyzed separately to understand the complete market picture.

---

## 🏠 3. Single Family Properties Dominate

Single Family properties represent the dominant property type in the dataset.

This makes the segment important for further market analysis.

---

## 💰 4. Location-Based Price Differences

Average sale values vary considerably between towns.

Hot Springs shows one of the highest average sale values in the analysis.

---

## 📊 5. Sales Ratio Variation

Bellingham and Asheville demonstrate differences in sales ratio performance.

This suggests that market behavior can vary significantly by location.

---

# 💼 Business Recommendations

Based on the dashboard findings:

### 1. Focus on High-Performing Locations

Real estate businesses can investigate strong-performing towns such as Fort Collins for:

* Market expansion
* Property inventory
* Investment opportunities
* Customer targeting

---

### 2. Analyze Single Family Demand

Since Single Family properties dominate the market, businesses can further analyze:

* Demand
* Pricing
* Inventory
* Location
* Transaction volume

---

### 3. Compare Locations Independently

Town-level analysis should be used to identify differences in:

* Sales
* Average prices
* Sales ratios
* Transaction activity

---

### 4. Monitor Long-Term Trends

Businesses should continuously track yearly sales performance to identify:

* Growth
* Decline
* Seasonal patterns
* Market changes

---

# 🚀 Future Improvements

The project can be further enhanced with:

* [ ] Year-over-Year Growth %
* [ ] Top 5 / Bottom 5 Towns
* [ ] Dynamic KPI Selector
* [ ] Median Sale Price
* [ ] Price Segmentation
* [ ] Sales Forecasting
* [ ] Predictive Analytics
* [ ] Advanced Geographic Analysis
* [ ] Market Growth Indicators
* [ ] Drill-Down Analysis
* [ ] Mobile Dashboard Optimization
* [ ] Dynamic Tooltips
* [ ] Advanced Parameter Controls

---

# 🎓 Skills Demonstrated

## Tableau

* Dashboard Development
* Data Visualization
* Calculated Fields
* Parameters
* Filters
* Dashboard Actions
* Geographic Mapping
* Interactive Storytelling

## Data Analytics

* Data Cleaning
* Exploratory Data Analysis
* KPI Development
* Trend Analysis
* Geographic Analysis
* Business Analysis
* Insight Generation

## Business Intelligence

* Dashboard Design
* Business Question Development
* KPI Reporting
* Interactive Analytics
* Data Storytelling
* Decision Support

---

# 📂 Project Structure

```text
Real-Estate-Insights-Dashboard-Tableau/
│
├── README.md
│
├── Data/
│   └── Real_Estate_Sales_2011-2022.xlsx
│
├── Dashboard/
│   └── Real_Estate_Insights_Dashboard.twbx
│
├── Documentation/
│   ├── Business_Questions.md
│   └── Key_Insights.md
│
├── Images/
│   └── real-estate-dashboard.png
│
└── LICENSE
```

> Update the filenames above if your actual repository uses different filenames.

---

# 📌 Project Highlights

| Category          | Details                                        |
| ----------------- | ---------------------------------------------- |
| 🏠 Domain         | Real Estate Analytics                          |
| 📅 Period         | 2011–2022                                      |
| 📊 Dashboard      | Tableau Interactive Dashboard                  |
| 🗺️ Analysis      | Geographic / Town Level                        |
| 📈 Trends         | Time-Series Sales Analysis                     |
| 💰 KPIs           | Sales, Average Sale, Transactions, Sales Ratio |
| 🏘️ Property      | Property Type Analysis                         |
| 🏡 Residential    | Residential Category Analysis                  |
| 🎛️ Interactivity | Filters & Dashboard Actions                    |
| 📍 Maps           | Geographic Visualization                       |
| 📖 Storytelling   | 3 Analytical Stories                           |

---

# 🧠 What I Learned

This project helped strengthen practical skills in:

* Building real-world Tableau dashboards
* Translating business questions into analytical visuals
* Creating meaningful KPIs
* Performing geographic analysis
* Performing time-series analysis
* Using calculated fields
* Creating dashboard interactions
* Designing business-focused visualizations
* Communicating insights through data storytelling

---

# 📈 Analytical Outcome

The project converts raw real estate transaction data into an interactive Business Intelligence solution.

The dashboard provides visibility into:

**Market Trends → Geographic Performance → Property Types → Residential Categories → Sales Ratios → Business Insights**

The analysis highlights a positive overall sales trend, strong performance in selected towns, significant differences in average sale values, and the dominance of Single Family properties.

---

# 👨‍💻 About Me

## Vikash Rao

**Aspiring Data Analyst**

I am passionate about transforming raw data into meaningful business insights using data analytics and Business Intelligence tools.

### 💻 Technical Skills

* SQL
* Python
* Pandas
* NumPy
* Advanced Excel
* Power BI
* Tableau
* Data Cleaning
* Exploratory Data Analysis
* Business Intelligence
* Data Visualization

---

# 🤝 Connect With Me

I'm open to connecting with:

* Recruiters
* Hiring Managers
* Data Analysts
* Business Analysts
* BI Professionals
* Data Science Professionals
* Fellow Data Analytics learners

---

## 🌐 Portfolio

### [Vikash Rao | Aspiring Data Analyst — SQL, Python, Power BI, Tableau](https://vikashrao-data-portfolio.vercel.app/#projects)

---

## 💼 LinkedIn

### [Connect with me on LinkedIn](https://www.linkedin.com/in/vikash-rao-402044336)

---

## 📊 Tableau Public

### [View My Tableau Public Profile](https://public.tableau.com/app/profile/vikash.rao)

### [View This Real Estate Dashboard](https://public.tableau.com/app/profile/vikash.rao/viz/Real_Estate_sale/Dashboard?publish=yes)

---

## 💻 GitHub

### [Explore My GitHub Projects](https://github.com/vikashrao627-glitch)

---

## 📧 Email

**[vikashrao625@gmail.com](mailto:vikashrao625@gmail.com)**

---

# 📩 Connect / Contact

If you are interested in discussing:

* Data Analytics opportunities
* Data Analyst roles
* Business Intelligence
* Tableau projects
* Power BI
* SQL
* Python
* Collaboration

feel free to connect with me through **LinkedIn or Email**.

---

# 🙌 Project Creator

## Created & Developed by Vikash Rao

This project was **analyzed, designed, and developed by Vikash Rao** as part of a practical Data Analytics / Business Intelligence portfolio.

The project demonstrates the ability to transform raw data into:

**Data → Analysis → Visualization → Insights → Business Decisions**

---

# ⭐ Support

If you found this project useful:

⭐ **Star this repository**

🔗 **Connect with me on LinkedIn**

📊 **Explore the interactive Tableau dashboard**

---

## 🏠 Real Estate Analytics

### 📊 Tableau × 💼 Business Intelligence × 📈 Data Analytics

**Turning Raw Data into Actionable Business Insights**
