# Customer-Shopping-Behavior-Analysis
## Project Objective
This project focuses on a comprehensive Exploratory Data Analysis (EDA) of customer shopping behavior within an e-commerce context. The primary goal is to derive actionable insights into customer demographics, purchase patterns, and product preferences. The final deliverable includes a detailed data analysis script and an interactive dashboard built in Power BI.


## Dataset Used
- <a href="https://github.com/amanbhatt007/Customer-Shopping-Behavior-Analysis/blob/main/shopping_behavior_updated.csv">Customer Shopping Behavior Dataset</a>


##  Questions (KPI)
- What is the total revenue generated?
- How many distinct items were sold?
- What is the average spending per customer?
- What is the average customer rating?
- What is the gender distribution of our customer base?
- Which location generates the highest revenue?
- What is the distribution of purchase frequency?
- What are the top 5 most frequently purchased items?
- Which product category generates the highest sales?
- Which season has the highest sales revenue?
- What is the average review rating for transactions with a discount vs. without?
- Which payment method is used most often?
- Does the use of a promo code influence the purchase amount?

- Dashboard Interaction <a href="https://github.com/amanbhatt007/Customer-Shopping-Behavior-Analysis/blob/main/Project%202.png">View Dashboard</a>

## Process
Phase 1: Data Extraction and Initial Load 📥
The first step involves acquiring the raw data and placing it into the primary cleaning tool.

Extract Raw Data: The <a href="https://github.com/amanbhatt007/Customer-Shopping-Behavior-Analysis/blob/main/shopping_behavior_updated.csv">Customer Shopping Behavior Dataset</a> file was sourced from Kaggle and saved.

Initial Load to Excel: The raw CSV data was opened and imported into Microsoft Excel, making it the staging area for all subsequent cleaning and preparation.

<img width="1602" height="942" alt="Raw Data" src="https://github.com/user-attachments/assets/3dae2747-c442-44c6-be59-3e1d1563e699" />


Phase 2: Transform (Data Cleaning and Preparation in Excel) ⚙️
This phase ensures data quality and structure are optimal before being loaded into Power BI. All transformations were performed using Excel's built-in tools and functions.

Data Type Validation:

Confirmed Age and Previous Purchases were formatted as Numbers.

Confirmed Purchase Amount (USD) and Review Rating were formatted as Decimals/Currency.

Standardization and Cleaning:

Used Find and Replace to correct any simple spelling errors or standardize categorical entries (e.g., ensuring Gender is consistently 'Male' or 'Female').

Ensured consistency across columns like Category, Color, and Location.

Handling Outliers/Inconsistencies:

Inspected numerical columns (Age, Purchase Amount) using Excel's filtering and sorting to identify and correct any extreme or erroneous values.

Final Export (Clean Data):

The cleaned data sheet was saved as a final, clean version (e.g., a cleaned .csv file), ready for ingestion into Power BI.

Phase 3: Load and Model (Power BI Data Modeling) 🧱
The cleaned dataset is now brought into Power BI and structured for analysis. Since the cleaning was done externally, this is a smooth import process.

Load Clean Data: The final, cleaned CSV file was imported into Power BI Desktop using the "Get Data" function. (No major Power Query steps were necessary, as the transformation was already complete).

Data Model Setup: Since this is a single, flat table, no complex table relationships were required.

Measure Creation (DAX): Data Analysis Expressions (DAX) were written to define core Key Performance Indicators (KPIs) and metrics for the dashboard.

Examples: Total Revenue, Average Purchase Amount, Total Items Purchased, and calculated percentages (e.g., % of Total Sales).

Finalize Model: The data model was set up with appropriate sorting and default aggregations to prepare for visualization.

Phase 4: Visualize (Dashboard Creation) 🖼️
The final phase involved designing and building the interactive report in Power BI.

Design Layout: A consistent color palette, themes, and background were applied, and the layout was planned to group related metrics (e.g., KPIs at the top, demographics on the left, sales trends in the center).

Visual Selection and Mapping: Appropriate visualization types were chosen for each question:

Cards for KPIs (Total Purchase Amount).

Donut/Pie Charts for distributions (Gender).

Bar/Column Charts for comparisons (Purchase Amount by Category, Items Purchased by Season).

Interactivity: Slicers were added (e.g., for Season or Location) and visuals were configured to interact with each other, allowing users to drill down into the data.

Final Report: The complete report was saved as the <a href="https://github.com/amanbhatt007/Customer-Shopping-Behavior-Analysis/blob/main/Project%202.png">Customer Shopping Behavior Analysis</a> file.



## Dashboard
<img width="1450" height="857" alt="Project 2" src="https://github.com/user-attachments/assets/eb53086c-a79b-4941-9330-efe26b4adbbb" />


## Project Insights
- Total Purchase Amount: $201,414
- Total Items Purchased: 3,800
- Average Purchase Amount: $53.00
- Average Review Rating: 3.71
- Gender Distribution: Female customers (67.95%) significantly outnumber Male customers (32.05%).
- Top 3 Locations by Purchase Amount: Montana, California, and Idaho are the leading states for revenue.
- Frequency of Purchases: Annually is the most common purchase frequency, followed by Quarterly and Bi-Weekly.
- Top 5 Items Purchased: Dress, Blouse, T-Shirt, Sweater, and Pants. (A specific quantity bar chart shows this distribution).
- Top Category by Purchase Amount: Clothing is the dominant category for sales, followed by Accessories and Footwear.
- Season by Purchase Amount: Winter appears to be the most revenue-generating season, followed closely by Fall.
- Average Review Rating by Discount Applied: Transactions without a discount have a slightly higher average rating (e.g., ~3.75) than those with a discount (e.g., ~3.68), suggesting discount hunters may be less satisfied or less loyal.
- Top Payment Method by Purchase Count: PayPal and Credit Card are the most frequently used methods by customers.
- Promo Code Used vs. Purchase Amount: There seems to be a significant difference (likely higher) in average purchase amount when a Promo Code is Used, indicating codes encourage larger basket sizes.


## Final Conclusion
This project successfully analyzed the shopping_behavior_updated.csv dataset, transforming raw transactional data into actionable insights via a robust Power BI dashboard. The analysis revealed key patterns across customer demographics, product performance, and promotional effectiveness.
The <a href="https://github.com/amanbhatt007/Customer-Shopping-Behavior-Analysis/blob/main/Project%202(kaggle).pbix">Customer Shopping Behavior</a> dashboard serves as a single source of truth for tracking essential KPIs, allowing stakeholders to easily monitor revenue, spending trends, and customer satisfaction. The visualizations provide a clear, data-driven foundation for optimizing inventory, targeting marketing spend, and enhancing the overall customer experience.

