# Dynamic-Pricing-Engine-for-E-Commerce-
A Python script to simulate, process, and visualize sales data using pandas, numpy, matplotlib, and seaborn.

Features





Simulates Sales Data: Generates 1000 records with product IDs, timestamps, prices, quantities, and customer IDs.



Simulates Product Data: Creates 9 products with costs and categories (electronics, apparel, home_goods).



Feature Engineering: Adds time-based features, lagged prices/quantities, moving averages, and profit calculations.



Data Validation: Ensures no negative prices or quantities.



Visualizations: Plots daily sales trends, profit by category, price vs. quantity, sales by hour, and profit distribution.

Requirements





Python 3.x



Libraries: pandas, numpy, matplotlib, seaborn

Setup





Clone the repository:

git clone <repository-url>



Install dependencies:

pip install pandas numpy matplotlib seaborn



Run the script:

python sales_simulator.py

Usage





Run the script to generate and process sales data.



View five visualizations and a sample of the processed data in the output.



Modify the visualize_data function to customize plots or add new ones.

Example Output





Daily Sales Trend: Line plot of total quantity sold over time.



Profit by Category: Bar plot comparing profit across categories.



Price vs. Quantity: Scatter plot with regression line, colored by category.



Sales by Hour: Box plot showing sales distribution by hour.



Profit Distribution: Histogram with KDE for profit per sale.

