# CAR SALES ANALYSIS
## Project Overview
This project analyzes a dataset of 50,000 cars sold in the market, focusing on manufacturers, models, engine size, mileage, year of manufacture, fuel type, and price.
The goal is to understand trends in car sales, compare prices, and explore relationships between vehicle features.

## Dataset Description
The dataset contains 7 columns:
**Manufacturer** → Name of the car manufacturer (e.g., Ford, VW, BMW, Porsche).
**Model** → Model name of the car.
**Engine Size** → Size of the engine (numeric).
**Fuel Type** → Type of fuel used (e.g., Petrol, Diesel, Hybrid).
**Year of Manufacture** → The year the car was manufactured.
**Mileage** → Distance covered by the car (numeric).
**Price** → Selling price of the car.

📌 The dataset has no missing values after inspection.

### 1. Data Cleaning and preprocessing
Converted Year of Manufacture into a proper datetime format.
Checked for missing values → dataset is clean.
Standardized categorical features for analysis.

### 2. Exploratory Data Analysis (EDA)
Crosstab Analysis:
Manufacturer vs. Model.
Manufacturer vs. Fuel type.
Model vs. Fuel type.
Car Sales Distribution:
Horizontal bar plots to show the number of cars sold by each manufacturer.
Identified Ford and VW as top sellers (>14,000 cars each).
Porsche sold the least (~2,000 cars), followed by BMW (~4,000 cars).
Most Sold Car Models:
Count plots of car models to identify leading models in the dataset.

### 3. Price Analysis

Grouped by Manufacturer and Model to compare average prices.
Visualized price distributions using bar plots, scatter plots, and regression plots.
Trends showed variation in prices across manufacturers and models.
### 4. Feature Relationships

**Scatter Plot:**
Relationship between Engine Size and Mileage (with regression line).
**Heatmap:**
Correlation between Price, Mileage, and Engine Size.
**Histogram:**
Distribution of car prices in the market.

### 5. Trend Analysis
Line Plots to visualize how prices vary with Year of Manufacture.

## TOOLS AND LIBRARIES
This project uses Python 3 with the following libraries:
1. **pandas** → Data manipulation.
2. **numpy** → Numerical computations.
3. **matplotlib & seaborn** → Data visualization.

## Key Insights
Ford and VW dominate the market in terms of sales volume.
Luxury brands (e.g., Porsche, BMW) sell fewer cars but often at higher prices.
Engine size has a positive correlation with price, while mileage has a negative correlation.
Prices show clear variability depending on manufacturer, model, and fuel type.