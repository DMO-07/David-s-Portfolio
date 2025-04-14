# David-s-Portfolio

# GREEN WHEEL ANALYSIS

To deliver data-driven insights on vehicle sales performance, cost efficiency, and sustainability metrics to support strategic business decisions.

# Steps Followed
 1. Data Collection & Preparation
* Imported raw data from Excel (e.g., sales records, customer data, model specs, warranty status).

* Cleaned and transformed the data using Power Query:
    - Removed duplicates
    - Filled missing values
    - Standardized column names (e.g., “Sales Rep”, “Model Name”, etc.)
    -  Merged datasets to create relationships (e.g., linking sales to models)
    
2. Data Modeling
* Defined relationships between tables:
    - Sales → Customers
    - Models → Warranty
    - Fuel Type → Vehicle Specs
* Created a data model schema for efficient filtering and slicers.

* Added calculated columns and DAX measures:
    - Total Revenue = SUM(Sales[Revenue])
    - Units Sold = SUM(Sales[Units])
    - Average Fuel Efficiency = AVERAGE(Vehicle[FuelEfficiency])
3. KPI Identification
* Selected key metrics for analysis:
    - Total Sales Revenue
    - Units Sold
    - TCO (Total Cost of Ownership)
    - Warranty Validity
    - Fuel Efficiency & Carbon Emissions
    - Competitor Market Share
4. Visualization Design
* Used appropriate visuals:
    - Bar Charts: TCO by model, average selling price
    - Line Graph: Sales trend over months, fuel efficiency by model
    - Pie Chart: Warranty status distribution
    - Gauge Chart: Sales vs monthly sales target
    - Tables: Customer units sold

* Applied slicers for filtering by:
    - Sales Rep
    - Model Name
    - Vehicle Type
    - Month
5. Interactivity and UX
* Ensured interactive filters and drill-down capabilities.
* Used color themes:
    - Green & white for sales dashboard (emphasis on growth)
    - Dark blue for sustainability/cost (professional, analytical tone)
* Ensured responsive layout for different screen sizes.
6. Testing and Validation
* Cross-checked calculations (e.g., total revenue vs sum of monthly sales).
* Validated that slicers and filters worked across all visuals.
* Ensured no data leakage or misalignment.

### Image of sales revenue by months in a line chart
![Image](https://github.com/user-attachments/assets/8f975f51-7727-475c-a899-b8ac5b928eb5)

### Image of TCO by model names in a column stacked column chart

![Image](https://github.com/user-attachments/assets/d7c8cba2-f14b-4d3d-9c1b-586ea8b8b270)

### Image of average of selling price per unit by warranty status

![Image](https://github.com/user-attachments/assets/bd2a917f-cce5-4db9-b3c6-83caf38e5389)

## Image of Dashboard 1 and Dashboard 2
![Image](https://github.com/user-attachments/assets/e006edc0-005a-40e3-9166-b0bc163637ce)
![Image](https://github.com/user-attachments/assets/a2677b04-5edd-4ea3-b112-372afe63e253)

