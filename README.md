# Warehouse_and_Retail_Sales_analytics-
Repository of hands‑on analytics projects using Python Covers retail vs. warehouse sales comparisons, item type analysis, supplier allocation, and monthly trend visualizations. Designed to demonstrate applied data storytelling and business impact.
Data cleaning: Data cleaning has been performed for missing values in suppliers with unknown for less than 1% of the empty rows. Also less than 5 rows had missing numbers in retail sales so filled with 0 and Item type had 1 row missing. The data has 307645 rows in total. So this would not affect our work as a Analysis.
Create Net_Sales_Quantity = Retail Sales + Warehouse Sales - Retail Transfers. Which item type has the highest average Net_Sales_Quantity ?
Add Sales_Per_Supplier = Retail Sales / Number of Suppliers. Which supplier achieves the highest efficiency?
Create a Quarter column (Q1–Q3). Compare quarterly average Retail Sales.
Group by Item Type and calculate total Retail Sales, Warehouse Sales, and Transfers. Which item type dominates overall sales?
Group by Month and compute month-over-month growth rate in Retail Sales. Identify the fastest-growing month?
Group by Supplier and calculate variance in Retail Sales. Which supplier is most consistent?
Perform a t-test comparing Retail Sales vs. Warehouse Sales. Is there a significant difference?
Conduct a one-way ANOVA to test if Retail Sales differ across Item Types. Which item type drives the difference?
Run a Chi-Square test between Item Type and Supplier. Is supplier allocation independent of item type?
Create a line chart showing monthly Retail Sales trends. Highlight the peak month.
Build a stacked bar chart of Retail Sales, Warehouse Sales, and Transfers by Item Type. Which item type relies most on warehouse sales?
Plot a heatmap of Item Type vs. Months showing total Sales. Identify suppliers with seasonal sales patterns.
🔹 Python Workflow
Step 1: Data Preparation
Import into Python using pandas.read_csv().
Clean missing values, duplicates, and data types.
Step 2: Column Creation
Use Pandas to create Net_Quantity_Sales, Sales_Per_Supplier, Quarter.
Step 3: Grouping & Aggregation Apply groupby in Pandas for item type, month, supplier analysis.
Step 4: Statistical Analysis
Use scipy.stats for t-test, ANOVA, Chi-Square.
Document results in Jupyter Notebook.
Step 5: Visualization Python: matplotlib & seaborn for line charts, stacked bars, heatmaps.
Save charts as PNGs and include in repo.
Step 6: Documentation
Write insights in Markdown cells (Jupyter Notebook).
Export charts and reference them in README.
🔹 Key Insights & Charts
📈 Retail Sales Trend: Month July shows peak sales.
🏷️ Item Type Analysis: Item Type Beer dominates overall sales.
📊 Statistical Tests: ANOVA confirms significant differences across item types by warehouse sales.
🔥 Supplier Performance: Supplier ARCHER ROOSE LLC shows most consistent sales variance.
🎨 Visualizations: Line charts, stacked bars, and heatmaps provide clear business insights.
Charts:[Names](Saved as)
[Retail quantities sold by Quarter](Retail quantities sold by Quarter.png),
[Monthly Retail Sales Trend](Monthly Retail Sales Trend.png),
[Retail, Warehouse, and Transfers by Item Type](Retail, Warehouse, and Transfers by Item Type.png),
[Visual Representation for overall sales](Visual Representation for overall sales.png),
[Warehouse_and_Retail_Sales](Warehouse_and_Retail_Sales.png),
[Heatmap of Total Net Sales Quanity by Item type and Month](Heatmap of Total Net Sales Quanity by Item type and Month.png)
🔹 Repository Structure
Code
/data        -> Excel dataset
/notebooks   -> Jupyter notebooks (Python analysis)
/scripts     -> Python scripts
/charts      -> PNG visualizations
README.md    -> Project documentation
