# Real Estate Market Dashboard – Power BI

## 🏠 Overview
An interactive Power BI dashboard to visualize real estate property data across major Indian cities. The dashboard showcases key metrics like total listings, sales value, average price per square foot, and more using filters, slicers, and dynamic visuals for better decision-making.

## 🎯 Objectives
- Analyze real estate trends by city, property type, and furnishing status
- Compare sale vs rent listings
- Identify top-performing cities based on total sales value

## 📊 Dataset Description
The dataset is composed of the following tables:
- `fact_Property`: Contains transactional data like sales value, listing type, and furnishing status
- `dim_Location`: City and location mapping
- `dim_PropertyType`: Property type details (Apartment, Villa, Plot, etc.)
- `dim_Agent`: Agent information
- `dim_Date`: Date-related details

## 💻 Dashboard Features
- 💡 Total Listings, Total Sales, Avg Price/Sqft
- 📊 Line chart for price trends by city & property type
- 🍩 Donut chart showing Sale vs Rent ratio
- 🏙️ Bar chart of top cities by property value
- 📄 Interactive table with city-wise & type-wise stats
- 🧩 Filters: City, Property Type, Furnishing Status, Listing Type

## 🔍 Key Insights
- Mumbai has the highest average price per sqft
- Most properties are sold rather than rented
- Semi-furnished apartments are the most common listings

## 🧠 How to Use the Dashboard
1. Open `RealEstateDashboard.pbix` in Power BI Desktop
2. Use slicers (City, Property Type, etc.) to explore different views
3. Hover or click visuals for interactive insights

## 🛠️ Tools & Tech
- Microsoft Power BI
- Excel for data cleaning
- DAX for measures
