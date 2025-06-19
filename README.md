# 🏠 Real Estate Market Dashboard – Power BI

An interactive Power BI dashboard to explore and analyze real estate trends across major Indian cities. This dashboard is designed to help stakeholders make informed decisions using visual insights into property listings, pricing, and market performance.

---

## 📌 Overview

This dashboard provides:

- Total listings, average price per square foot, and total sales value
- Filtering by city, property type, listing type, and furnishing status
- Visual comparisons across locations and listing categories
- Insights into agent performance and property distribution

---

## 🎯 Objectives

- Analyze real estate trends by city, property type, and furnishing status
- Compare sale vs rent listings across regions
- Identify top-performing cities based on total property value
- Understand average prices, maintenance costs, and property area distribution

---

## 📊 Dataset Description

The dashboard uses multiple tables:

| Table Name        | Description                                                      |
|------------------|------------------------------------------------------------------|
| `fact_Property`   | Transactional data like sales value, area, listing type, furnishing status |
| `dim_Location`    | City and location mapping                                        |
| `dim_PropertyType`| Property types (Apartment, Villa, Plot, etc.)                   |
| `dim_Agent`       | Agent name and managed property details                         |
| `dim_Date`        | Date information for time-based analysis                        |

---

## 💻 Dashboard Features

- **KPI Cards**: Total Listings, Total Sales Value, Avg Price per Sqft, Avg Property Age
- **Sankey Chart**: Avg Price per Sqft by City and Property Type
- **Bar Charts**:
  - Total Property Value by Listing Type
  - Average Price by Furnishing Status
  - Total Carpet Area by City
  - Maintenance Cost by City
- **Donut Chart**: Sale vs Rent Listing Distribution
- **Waterfall Chart**: Top Cities by Total Property Value
- **Map View**: Geographic distribution of listings
- **Pie Chart**: Property Count by State
- **Matrix Table**: Properties Managed by Agents
- **Interactive Table**: City-wise and Property-type-wise stats

---

## 🔍 Key Insights

- **Mumbai** has the highest average price per square foot
- **Most properties are for sale** rather than rent
- **Semi-furnished** apartments are most common in listings
- **Maharashtra and Gujarat** lead in total property values

---

## 🧠 How to Use the Dashboard

1. Open the `RealEstateDashboard.pbix` file in Power BI Desktop
2. Use slicers to filter data:
   - City
   - Property Type
   - Furnishing Status
   - Listing Type
3. Interact with visuals by hovering and clicking
4. Use pages to navigate between KPI views, geographic views, and property analysis

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop** – for creating interactive visual dashboards
- **Microsoft Excel** – for initial data cleaning and formatting
- **DAX (Data Analysis Expressions)** – for calculated measures and KPIs
- **Power BI Maps** – for geo-based visualizations

---

## 🚀 Future Enhancements

- Time series trends for property pricing
- Integration with live API data for real-time insights
- Predictive analytics using Power BI AI features

---


