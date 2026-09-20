# Zameen Real Estate Analysis Dashboard | Power BI

An interactive **Power BI real estate market analysis dashboard** built using property listing data collected from **Zameen.com**.

The dashboard analyzes property prices, property types, area, cities, locations, agencies, bedrooms, bathrooms, and price-per-marla metrics.

---

# Dashboard Preview

![Zameen Real Estate Dashboard - Market Overview](Screenshots/Zameen%20Dashboard-page-1.png)

## Dashboard Demo

![Zameen Real Estate Dashboard Demo](Demo/Zameen.com%20Real%20Estate%20Dashboard%20Demo%20%28gif%29.gif)

**🎬 [Watch the Full Interactive Dashboard Demo in Best Quality on YouTube](https://youtu.be/-I5ykpb4MGI)**

## 🚀 Live Power BI Dashboard

**[Open the Interactive Power BI Dashboard](https://app.powerbi.com/reportEmbed?reportId=65972570-ecfc-49e3-bacb-02d12b8168d1&autoAuth=true&ctid=961c5db5-ccc4-4e28-9334-9ce22ef4b255)**

**To view DAX measures:** [Zameen.com Dashboard DAX Measures.xlsx](https://github.com/zaifi320/Zameen-Real-Estate-Analysis-Powerbi/blob/main/Zameen.com%20Dashboard%20DAX%20Measures.xlsx "Zameen.com Dashboard DAX Measures.xlsx")

---

# 1. 📌 Business Questions / Dashboard Requirements

Before creating the dashboard, the project was approached as a real-world business analytics task.

### Market Overview
- How many properties are in the dataset?
- How are properties distributed across cities?
- What is the sales vs rental property mix?
- Which property types are most common?
- Which cities have the highest number of listings?
- What are the main market-level KPIs?

### Price & Property Analysis
- What are the average, median, minimum, and maximum property prices?
- How does average price vary by property type?
- Which cities have the highest average price per marla?
- How are properties distributed across price ranges?
- How does property price relate to area?
- How are listings distributed by bedrooms and bathrooms?
- How does price per marla vary with property area?

### Location & Agency Insights
- How many cities, locations, and agencies are represented?
- Which cities contain the most property listings?
- Which agencies have the highest number of listings?
- How are agencies distributed across provinces?
- Which cities have the highest average property prices?
- Which cities have the highest average price per marla?
- What is the geographic distribution of listings?
- How concentrated is listing activity across agencies?

---

# 2. 🔄 Project Process

**Web Scraping → Data Storage → Data Cleaning → Data Modeling → DAX Analysis → Power BI Dashboard → Interactive Insights**

### 1. Data Collection
Property listing data was collected from Zameen.com using a Scrapy-based web scraping pipeline.

### 2. Data Storage
The scraped property data was structured and stored for further processing and analysis.

### 3. Data Cleaning & Transformation
- Handled missing values
- Cleaned text fields
- Standardized property attributes
- Converted price and area values into numeric formats
- Extracted area in Marla
- Created Price per Marla
- Prepared city, location, agency, and province fields
- Handled invalid records where required

### 4. Data Modeling
The cleaned dataset was loaded into Power BI and organized for analysis.

### 5. DAX Analysis
Created DAX measures for KPIs and analytical calculations such as Total Properties, Average Price, Median Price, Minimum Price, Maximum Price, Average Price per Marla, Total Cities, Total Locations, Total Agencies, Top City by Properties, and Top Agency by Listings.

### 6. Dashboard Development
Built three interactive pages:
1. **Market Overview**
2. **Price & Property Analysis**
3. **Location & Agency Insights**

### 7. Interactive Analysis
Added slicers, filters, navigation buttons, KPIs, charts, maps, and insight sections.

---

# 3. 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Data processing and supporting workflows |
| **Scrapy** | Web scraping and structured property data extraction |
| **MongoDB** | Storage of scraped property listings |
| **Power BI** | Interactive dashboard and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures, KPIs, and analytical calculations |
| **Microsoft Excel** | DAX documentation and supporting data work |
| **Git & GitHub** | Version control and project sharing |

---

# 4. 📊 Data Source

The primary data source is **Zameen.com**, a real estate platform containing property listings in Pakistan.

The dataset used in this project was collected through **web scraping** and then cleaned and transformed for analysis.

### Main data fields include
- Property ID
- Property title
- Property type
- City
- Location
- Agency
- Price
- Area
- Bedrooms
- Bathrooms
- Province
- Listing URL
- Other available property attributes

> **Important:** This dashboard represents the collected dataset used for this project. It should not be interpreted as a live or complete representation of all current Zameen.com listings.

---

# 5. ⭐ Features and Highlights

## Business Problem

Real estate listing data can contain a large number of properties across different cities, locations, property types, price ranges, and agencies. Working directly with raw listing data makes it difficult to quickly identify market patterns and compare locations.

The challenge was to transform a large property listing dataset into an interactive analytical dashboard for exploring property prices, market distribution, locations, property characteristics, and agency activity.

## Dashboard Goal

The goal was to turn raw real estate listing data into an **interactive Power BI analytical product** that helps users:
- Understand the overall property market
- Compare property prices across cities and property types
- Analyze price per marla
- Explore area and price relationships
- Identify cities with high listing activity
- Analyze agency listing activity
- Explore geographic property distribution
- Filter and investigate specific parts of the dataset

---

# 6. 📑 Dashboard Pages & Key Visuals

## Page 1 — Market Overview

Provides a high-level summary of the real estate dataset.

**Key visuals and reasoning**
- **KPI Cards** — quick summary of important market metrics.
- **Sales vs Rentals** — shows the distribution between sales and rental listings.
- **Properties by City** — shows where listing activity is concentrated.
- **Property Type Analysis** — identifies major property categories.
- **Market Summary** — provides a quick starting point for analysis.
- **Interactive Filters** — allow focused exploration.

## Page 2 — Price & Property Analysis

Focuses on property pricing and physical characteristics.

**Key visuals and reasoning**
- **Average, Median, Minimum & Maximum Price** — statistical summary of property prices.
- **Average Price by Property Type** — compares pricing across property categories.
- **Average Price per Marla by City** — provides a size-adjusted city comparison.
- **Property Price Distribution** — shows how listings are spread across price ranges.
- **Properties by Bathrooms** — shows listing distribution by bathroom count.
- **Price per Marla vs Area** — explores the relationship between property size and normalized pricing.
- **Properties by Bedrooms** — shows listing distribution by bedroom count.

## Page 3 — Location & Agency Insights

Focuses on geographic distribution and agency activity.

**Key visuals and reasoning**
- **Total Cities, Locations & Agencies** — summarizes geographic and agency coverage.
- **Top City by Properties** — shows the city with the highest listing count in the dataset.
- **Top Agency by Listings** — shows the agency with the highest listing count in the dataset.
- **Properties by City** — compares listing activity between cities.
- **Properties by Province** — provides a broader geographic view.
- **Properties by Agency** — compares listing activity across agencies.
- **Average Price by City** — compares overall property pricing across cities.
- **Average Price per Marla by City** — provides a size-adjusted city comparison.
- **Map** — adds geographic context to listing distribution.
- **Agency Distribution by Province** — shows agency presence across provinces.
- **Insight Section** — summarizes observations from the dashboard.

---

# 7. 📈 Business Impact and Insights

The dashboard provides a structured way to investigate:
- Which cities have the most listings
- Which property types dominate the dataset
- How property prices vary across cities
- How price per marla differs by location
- Which price ranges contain the largest number of listings
- How property area relates to price per marla
- Which agencies have high listing activity
- How agencies are distributed across provinces
- Which property characteristics are common in the dataset

The actual values and patterns depend on the collected dataset and selected dashboard filters.

---

# 8. 🧮 DAX Measures

The project uses DAX for calculated metrics and dashboard KPIs.

```DAX
Total Properties =
COUNTROWS('Zameen')
```

```DAX
Total Cities =
DISTINCTCOUNT('Zameen'[City])
```

```DAX
Total Locations =
DISTINCTCOUNT('Zameen'[Location])
```

```DAX
Total Agencies =
DISTINCTCOUNT('Zameen'[Agency])
```

**[View Zameen.com Dashboard DAX Measures.xlsx](https://github.com/zaifi320/Zameen-Real-Estate-Analysis-Powerbi/blob/main/Zameen.com%20Dashboard%20DAX%20Measures.xlsx)**

---

# 9. 📁 Repository Structure

```text
Zameen-Real-Estate-Analysis-Powerbi/
│
├── Dashboard/
│   └── Zameen Dashboard.pbit
│
├── Dataset/
│   └── zameen_updated_property_data.csv
│
├── Demo/
│   ├── Zameen.com Real Estate Dashboard Demo (gif).gif
│   └── Zameen.com Real Estate Dashboard Demo.mp4
│
├── Screenshots/
│   ├── Zameen Dashboard-page-1.png
│   ├── Zameen Dashboard-page-2.png
│   └── Zameen Dashboard-page-3.png
│
├── Zameen.com Dashboard DAX Measures.xlsx
├── Zameen.com Dashboard.pdf
├── .gitattributes
└── README.md
```

---

# 10. 🎯 Skills Demonstrated

- Web Scraping
- Data Extraction
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Data Modeling
- Power BI
- Power Query
- DAX
- Data Visualization
- KPI Development
- Dashboard Design
- Geographic Analysis
- Business Analytics
- Git & GitHub
- End-to-End Data Analytics Workflow

---

# 👨‍💻 Author

**Huzaifa Bin Saeed**

Data Scientist & Web Scraping Specialist

**LinkedIn:** [Huzaifa Bin Saeed](https://www.linkedin.com/in/huzaifabinsaeed/)

---

## ⭐ Project

Explore the interactive dashboard, review the project documentation, and watch the demo to see the complete analysis workflow.
