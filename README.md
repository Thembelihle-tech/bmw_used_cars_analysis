# 📊 BMW Used Car Analysis Dashboard

## Project Overview

This project analyzes used BMW car listings to uncover patterns in:

- Price trends over time  
- Mileage vs price relationship  
- Fuel type distribution  
- Transmission distribution  
- Average engine size by model  
- Fuel efficiency (MPG) insights  

The goal of this analysis is to extract business insights that could support pricing strategy, marketing decisions, and inventory management.

---

## Dataset

The dataset contains used BMW vehicle listings with the following attributes:

- Model  
- Year  
- Price  
- Mileage  
- Fuel Type  
- Transmission  
- Engine Size  
- MPG  

---

## Data Cleaning & Preparation

Data cleaning was performed in Power BI (Power Query):

- Removed unnecessary columns  
- Removed duplicate records  
- Filtered out unrealistic MPG values (>100 MPG) to eliminate extreme electric outliers  
- Corrected data types  
- Standardized categorical values  

This ensured accurate aggregation and meaningful visual analysis.

---

## Dashboard KPIs

- **Total Cars**
- **Average Price**
- **Average MPG**
- **Most Common Fuel Type**

---

## Key Insights

1. Diesel vehicles dominate the dataset.
2. Higher mileage vehicles generally have lower prices.
3. Semi-Auto is the most common transmission type.
4. Diesel vehicles show higher average MPG than Petrol vehicles.

---

## Tools Used

- Power BI  
- Power Query  
- DAX  
- Excel  

---

## Skills Demonstrated

- Data cleaning & transformation  
- Handling outliers  
- KPI design  
- Dashboard design  
- Data storytelling

---

## Dashboard Preview

![Dashboard](https://github.com/Thembelihle-tech/bmw_used_cars_analysis/blob/main/BMW%20Car%20Analysis%20-%20project/screenshot/bmw_car_analysis.jpeg)

---

## Files in This Repository

- `BMW Car analysis.pbix` – Power BI dashboard report file  
- `data/` – Contains the BMW dataset used for analysis  
- `screenshot/` – Contains dashboard preview image  
- `README.md` – Project documentation  

---

## How to Use

1. Download or clone this repository.
2. Open `BMW Car analysis.pbix` using Microsoft Power BI Desktop.
3. If prompted, ensure the dataset path matches the file inside the `data/` folder.
4. Explore interactive filters and visuals to analyze:
   - Pricing trends
   - Fuel type distribution
   - Transmission patterns
   - Fuel efficiency metrics
   - Mileage vs price relationships

---

## Author

**Thembelihle Nkosi**  

This project was developed as part of a personal data analytics portfolio to demonstrate skills in data cleaning, transformation, visualization, and business insight extraction using Power BI.
