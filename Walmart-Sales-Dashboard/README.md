# Walmart Sales Dashboard

The Walmart Sales Dashboard is a Power BI project for exploring retail sales performance across products, customers, stores, and employees. It transforms transactional sales data into interactive business insights that can support revenue tracking, operational analysis, and better decision-making.

The project uses a fact-and-dimension data model. The central sales table records individual transactions, while related dimension tables provide descriptive details about the people, products, locations, and employees involved in each sale.

## Analysis Areas

- Sales trends by date
- Revenue, quantity, unit price, and shipping cost analysis
- Product category, sub-category, and brand performance
- Store performance by city, state, region, and store type
- Customer analysis by demographic and customer segment
- Employee and department-related sales analysis
- Payment method comparisons

## Data Model

- `Sales_Fact.csv` - transaction-level sales data, including sale date, quantity, prices, payment method, and shipping cost
- `Customer_Dim.csv` - customer names, demographics, locations, and segments
- `Product_Dim.csv` - product names, categories, sub-categories, and brands
- `Store_Dim.csv` - store locations, regions, and store types
- `Employee_Dim.csv` - employee names, positions, departments, and hire dates

## Tools

- Power BI Desktop
- Power Query for data preparation and transformation
- DAX for calculated measures and KPIs
- CSV files as the source data