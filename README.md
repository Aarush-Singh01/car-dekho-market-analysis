# Car Dekho Market Trends Analysis

## Project Overview

This project performs exploratory data analysis on Car Dekho vehicle data to
understand used-vehicle pricing, depreciation, vehicle popularity and market
trends.

The analysis covers manufacturing year, selling price, present price,
kilometers driven, fuel type, seller type, transmission and ownership.

## Objectives

- Analyze vehicle pricing and depreciation
- Identify popular vehicle models
- Analyze fuel type distribution
- Analyze seller and transmission patterns
- Compare cars and two-wheelers
- Study the relationship between vehicle age, kilometers driven and selling price
- Identify vehicles with unusually high resale value

## Dataset

The dataset contains **301 original records** and **9 attributes**.

### Attributes

| Attribute | Description |
|---|---|
| Car_Name | Name of the vehicle |
| Year | Manufacturing year |
| Selling_Price | Selling price of the vehicle |
| Present_Price | Current/present price |
| Kms_Driven | Kilometers driven |
| Fuel_Type | Fuel used by the vehicle |
| Seller_Type | Dealer or individual |
| Transmission | Manual or automatic |
| Owner | Number of previous owners |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Data Analysis

The project answers 25 questions covering:

- Manufacturing year
- Minimum and maximum selling price
- Number of records
- Missing values
- Vehicle popularity
- Fuel type
- Seller type
- Transmission
- Ownership
- Depreciation
- Vehicle age
- Kilometers driven
- Cars and two-wheelers
- Resale value

## Visualizations

The analysis includes:

- Bar charts
- Pie charts
- Histograms
- Box plots
- Scatter plots
- Line charts
- Correlation heatmaps

## Key Findings

- Vehicles in the dataset were manufactured between **2003 and 2018**.
- The original dataset contains **301 records**.
- There are **98 unique vehicle names**.
- Selling prices range from **₹0.10 lakh to ₹35 lakh**.
- Petrol vehicles are the dominant fuel type.
- Manual transmission vehicles are more common than automatic vehicles.
- **Honda City** is the most frequently occurring vehicle.
- **Royal Enfield Classic 350** is the most frequently occurring two-wheeler.
- **Toyota Land Cruiser** has the highest absolute depreciation in the dataset.
- Some newer vehicles with relatively low kilometers driven show high resale percentages.

## Project Structure

```text
car-dekho-market-analysis/
│
├── data/
│   └── car_data.csv
│
├── notebooks/
│   └── Car_Dekho_Market_Analysis.ipynb
│
├── visuals/
│   ├── Average Depreciation Percentage by Brand.png
│   ├── Average Selling Price by Fuel Type.png
│   ├── Average Selling Price by Transmission.png
│   ├── Average Selling Price vs Vehicle Age.png
│   ├── Cars vs Two-Wheelers.png
│   ├── Correlation Matrix.png
│   ├── Distribution of Selling Prices.png
│   ├── Manufacturing Year vs Selling Price.png
│   ├── Present Price vs Selling Price.png
│   ├── Selling Price Box Plot.png
│   ├── Top 10 Two-Wheelers by Number of Records.png
│   ├── Top 10 most frequently sold vehicles.png
│   ├── Two-Wheeler Price vs Kilometers Driven.png
│   ├── Two-Wheeler Price vs Vehicle Age.png
│   ├── distribution of vehicle depreciations.png
│   ├── fuel type distribution.png
│   ├── transmission distribution.png
│   └── vehicles by seller type.png
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
