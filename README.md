BMW Car Sales Classification – README
Overview
This dataset contains sales data for various BMW models across different regions, aimed at classifying sales performance into categories such as High or Low. The project focuses on analyzing patterns in sales, pricing, and specifications to understand factors influencing sales classification.

Dataset Information
File Name: BMW_Car_Sales_Classification.csv

Rows: 50,000

Columns: 11

Missing Values: None

Columns Description
Column	Description
Model	BMW model name (e.g., 5 Series, X3, i8, 7 Series)
Year	Manufacturing year of the vehicle
Region	Sales region (Asia, North America, Middle East, South America, etc.)
Color	Vehicle color
Fuel_Type	Type of fuel used (Petrol, Diesel, Hybrid, Electric)
Transmission	Gearbox type (Manual or Automatic)
Engine_Size_L	Engine size in liters
Mileage_KM	Distance driven in kilometers
Price_USD	Price of the car in USD
Sales_Volume	Number of units sold
Sales_Classification	Target variable: Sales category (High / Low)

Sample Data
Model	Year	Region	Color	Fuel_Type	Transmission	Engine_Size_L	Mileage_KM	Price_USD	Sales_Volume	Sales_Classification
5 Series	2016	Asia	Red	Petrol	Manual	3.5	151,748	98,740	8,300	High
i8	2013	North America	Red	Hybrid	Automatic	1.6	121,671	79,219	3,428	Low
5 Series	2022	North America	Blue	Petrol	Automatic	4.5	10,991	113,265	6,994	Low

Possible Analysis & Insights
Trend Analysis: Identify how sales vary by model, year, and region.

Feature Impact: Determine which features (price, engine size, mileage, fuel type) influence sales classification.

Predictive Modeling: Build a classification model (e.g., Random Forest, Logistic Regression) to predict Sales_Classification.

Visualization: Use charts to show regional preferences, price distributions, and correlations.

Tools & Libraries
Data Handling: Pandas, NumPy

Visualization: Matplotlib, Seaborn, Plotly

Modeling: Scikit-learn, XGBoost

Notebook Environment: Jupyter Notebook / Google Colab
