# Car-Sales-Data-analysis-Project
End-to-end car sales data analysis project featuring data cleaning, preprocessing, EDA, feature engineering, and visual insights using Python. Includes an interactive Power BI dashboard showcasing key sales metrics, trends, top models, and seller performance.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚗 Car Sales Data Analysis Project
📊 Comprehensive Data Cleaning, Feature Engineering & Visualization Using Python
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📌 Overview
This project focuses on analyzing a car sales dataset to uncover key market insights, pricing patterns, and sales trends.
It includes:
A complete Python analysis (data cleaning → feature engineering → EDA → visualizations)
An interactive Power BI dashboard to explore KPIs such as sales trends, top brands/models, seller performance, and body-type distribution

The goal is to simulate a real-world data analyst workflow — from raw data to business-ready visual insights.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🎯 Objectives

Clean and preprocess the dataset for consistency and accuracy

Engineer new features to enhance analytical depth

Explore sales trends, pricing behavior, and market patterns

Visualize findings effectively using Python

Save the cleaned and processed dataset for future use (output.csv)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧰 Tools & Libraries Used
Purpose	                 Library
Data manipulation    	Pandas, NumPy
Visualization	        Matplotlib, Seaborn
Environment	          Jupyter Notebook
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Dataset Information

File name: car_prices.csv

Rows & Columns: Varies depending on dataset version

Key Columns:

make, model, body, transmission, state, color, interior

condition, odometer, mmr, sellingprice

seller, vin, saledate

Cleaned output file: output.csv

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🧹 Step 1: Data Cleaning

Data cleaning ensures accuracy and consistency before analysis.
Performed tasks include:

Removed duplicate rows

Filled missing numeric values with median

Filled missing categorical/string values with ‘Unknown’

Converted column data types appropriately

Handled and standardized the sale date column (YYYY-MM-DD)

Renamed and formatted columns for clarity

✅ Final dataset validated with no missing values and correct data types.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠️ Step 2: Feature Engineering

New features were created to enhance analysis depth and trend identification:

Feature	Description
sale_year, sale_month, sale_quarter, sale_weekday	Time-based analysis
price_per_mile	Selling price divided by odometer reading
is_expensive	Boolean — selling price above average
make_simplified	Rare car makes grouped as “Other”
trim_length, vin_prefix	Derived string-based insights
seller_sales_count	Number of cars sold per seller

Cleaned and engineered dataset saved as output.csv.

📊 Step 3: Exploratory Data Analysis (EDA)

EDA was performed to understand:

Data shape, types, and distributions

Missing values and duplicates

Summary statistics (mean, median, IQR)

Relationships among numeric and categorical variables

High-level insights on top brands, states, and sellers

Key Analytical Checks

Dataset shape and info (df.info())

Missing values summary

Unique value counts

Numeric column analysis (min, max, mean, median)

Correlation matrix for numeric features

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Step 4: Visualizations

Visualizations help uncover trends and communicate insights effectively.

Main Visuals & Insights

Analysis                	Visualization Type	                 Description
Sales Trends	          Bar & Line Charts	           Yearly and monthly car sales trends
Brand Insights	        Bar Charts	                 Top-selling car brands & their avg. selling price
Price & Condition	      Boxen & Scatter Plots	       Impact of condition and year on price
Mileage Impact	        Scatter Plot	               Relationship between odometer reading and selling price
Geographic Trends	      Bar Charts	                 Top states by sales volume and avg. price
Seller Insights	        Bar Charts	                 Top sellers by number of cars sold
Body Type Popularity	  Bar Chart	                   Most popular car body types (SUV, Sedan, Truck, etc.)
Correlation Matrix	    Heatmap	                     Numeric feature relationships and selling price drivers
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
💡 Key Insights

🚘 Top-selling brands: Toyota, Ford, BMW dominate overall sales.

🌎 Top states: California, Texas, and Florida have the highest car sales.

📅 Seasonality: Sales peak in specific months, showing clear seasonal patterns.

🧮 Condition vs Price: Better car condition strongly correlates with higher price.

⚙️ Mileage Impact: Higher odometer readings reduce selling price.

💰 Seller Trends: Certain dealers have consistently higher sales volumes.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📦 Step 5: Saving Final Dataset

The fully cleaned and feature-engineered dataset is saved as:

output.csv

This file is ready for:

Interactive dashboard creation

Further predictive analysis (optional)

Data visualization tools like Power BI or Tableau
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📊 Step 6: Possible Next Steps

Although this project focuses on analytics and visualization, possible extensions include:

Building a Streamlit dashboard for interactivity

Performing predictive modeling for price forecasting

Connecting insights to business recommendations
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Step 7: Visualizations (Power BI Addition) — ADD THIS AT THE END OF THE SECTION
🟦 Power BI Dashboard (Added Section)

Along with Python visualizations, an interactive Power BI dashboard was created to explore:
Top-selling car models and brands
Sales trends by month, body type, and condition
Seller performance metrics
State-wise sales distribution
Key KPIs such as total sales, average selling price, and brand share
This dashboard helps in high-level decision-making and business reporting.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎥 Dashboard Demo Video

Watch the interactive Power BI dashboard demonstration for this project:

▶️ https://youtu.be/YOUR_VIDEO_LINK

This demo video showcases:

• Interactive Power BI dashboard  
• Sales trends and key KPIs  
• Top car brands and models analysis  
• Seller performance insights  
• State-wise sales distribution  

The dashboard enables quick exploration of sales performance and supports data-driven business insights.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📁 Project Structure
Car_Sales_Analysis/
│
├── car_prices.zip                        # Original raw dataset (compressed)
├── car_sales_analysis.ipynb              # Jupyter Notebook (main analysis)
├── car_sales_analysis_dashboard.pbix     # Power BI interactive dashboard
├── output.zip                            # Cleaned & feature-engineered dataset (compressed)
├── README.md                             # Project documentation (this file)
└── visuals/                               # Folder for charts (optional)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 How to Run

1. Clone this repository
https://github.com/bhaveshmishra123/Car-Sales-Analysis
2. Open the notebook
jupyter notebook car_sales_analysis.ipynb
3. Install dependencies
pip install pandas numpy matplotlib seaborn
4. Run all cells to reproduce the analysis
5. (Optional) Explore saved dataset output.csv
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📧 Author
Name: Bhavesh Kumar Mishra
Role: Data Analyst | Python Enthusiast | Visualization Expert & Power BI Specialist
Connect: 📧 Author

Name: Bhavesh Kumar Mishra
Role: Data Analyst | Python Enthusiast | Visualization Expert & Power BI Specialist
Connect: LinkedIn Profile (www.linkedin.com/in/bhavesh-kumar-mishra-a99b67379)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🏁 Conclusion
This project demonstrates a complete data analytics workflow — from raw data cleaning to feature engineering and insightful visualizations — using real-world car sales data.
It highlights analytical thinking, Python proficiency, and data storytelling through both Python visualizations essential skills for a professional data analyst.
The project also includes a professional Power BI dashboard, enabling interactive exploration of key metrics and supporting business decision-making.
