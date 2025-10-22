# Dubai_Apartment_Price_Analysis
Interactive Power BI dashboard analyzing apartment prices in Dubai. Shows average, minimum, and maximum prices, trends per neighborhood, price vs. size, and geographical distribution. Filters allow exploring by bedrooms or furnishing status. `Price_per_sqft` is included in the original dataset

## Project Goal
Analyze apartment prices in Dubai using Power BI by cleaning the data and creating an interactive dashboard.

## Data Source
An Excel file containing the following apartment data:
- Neighborhood
- Price
- Size_in_sqft
- No_of_bedrooms
- No_of_bathrooms
- Quality
- Unfurnished
- Latitude
- Longitude

## Project Steps
1. Import the file into Power BI.
2. Clean the data:
   - Remove blank rows.
   - Remove duplicates.
   - Adjust data types.
   - Filter out illogical values (e.g., Price = 0 or Size_in_sqft < 20).
3. Create an interactive dashboard:
   - KPI Cards: Average Price, Maximum Price, Minimum Price.
   - Bar Chart: Average price per Neighborhood.
   - Area Chart: Price versus Size.
   - Map: Distribution of apartments by Latitude & Longitude.
   - Slicer: Filter data by number of bedrooms or Unfurnished status.

## Notes
- Only the essential columns are kept to simplify analysis.
- The `Price_per_sqft` column was already present in the original dataset.
- A sample dataset version is included to protect sensitive information.

- ##Dashboard Preview
- ![Dashboard](images/dashboard.png)
  
