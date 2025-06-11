# 📚 Data Dictionary

## fact_Property
| Column Name        | Description                          |
|--------------------|--------------------------------------|
| PropertyID         | Unique identifier for each listing   |
| SalesValue         | Total property sale value (₹)        |
| ListingType        | 'Rent' or 'Sale'                     |
| FurnishingStatus   | Fully/Semi/Unfurnished               |
| AvgPricePerSqft    | Price per square foot (₹)            |
| PropertyTypeID     | Foreign Key to dim_PropertyType      |
| LocationID         | Foreign Key to dim_Location          |

## dim_Location
| Column Name  | Description                |
|--------------|----------------------------|
| LocationID   | Unique location ID         |
| City         | City name                  |

## dim_PropertyType
| Column Name     | Description                   |
|-----------------|-------------------------------|
| PropertyTypeID  | Unique ID for property type   |
| PropertyType    | Apartment, Villa, etc.        |

## dim_Agent
| Column Name | Description              |
|-------------|--------------------------|
| AgentID     | Unique agent ID          |
| AgentName   | Name of the agent        |

## dim_Date
| Column Name | Description             |
|-------------|-------------------------|
| Date        | Date field              |
| Month       | Month of the transaction|
| Year        | Year of the transaction |
