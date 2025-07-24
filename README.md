# Blinkit Sales Analysis with Python

# Project Overview
This project delivers an in-depth Exploratory Data Analysis (EDA) of Blinkit sales data using Python tools. We uncover sales trends, product performance, and outlet behavior by applying data cleaning, KPI computation, and visualization techniques.

#Objective
The key goals of this analysis include:

Understanding the impact of fat content, item categories, and outlet attributes on sales.

Tracking performance by outlet type, size, and location.

Computing critical business KPIs: Total Sales, Average Sales, Items Sold, Average Ratings.

Identifying actionable insights to guide inventory strategy and operational planning.

#Dataset
The dataset features sales data from Blinkit with attributes such as:

Item_Identifier: Unique ID per item

Item_Type: Category (e.g., Snacks, Dairy)

Item_Fat_Content: e.g., Low Fat, Regular

Item_Visibility, Item_Weight

Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, Outlet_Type

Sales: Revenue per item sold

Rating: Customer rating (1–5 scale)
(Full schema based on blinkit dataset conventions)

#Steps & Workflow
1. Data Cleaning & Processing
Standardized inconsistent fat content labels (e.g. “LF”, “low fat”, “reg”) to unified categories.

Handled missing values and corrected data types.

Applied feature engineering and removed anomalies/outliers.

2. KPI Calculation & Business Metrics
Computed the following KPIs:

Total Sales: Overall revenue across outlets

Average Sales: Mean revenue per transaction/item

Number of Items Sold

Average Rating: Customer satisfaction metric

3. Exploratory Data Analysis
Performed with Pandas, Seaborn, and Matplotlib:

Sales by Fat Content: Pie or bar charts of metrics across fat categories

Sales by Item Type: Visual comparisons of sales and ratings per category

Outlet Establishment Year Trends: Time-based performance analysis

Outlet Size & Location Impact: Sales distribution by store size and region

Relationship analysis among pricing, item visibility, and ratings

4. Visualization & Insights
Generated visual narratives such as:

Donut chart for fat-content sales distribution

Stacked bar charts comparing item types across outlet attributes

Line graphs showing trends over outlet establishment years

Geographic or tier-based maps for location-driven sales patterns (if mapping used)

🧰 Tools & Technologies Used
Python (pandas, numpy) for data processing

Seaborn & Matplotlib for visualization

Jupyter Notebook (or .py scripts) for EDA workflow

How to Run This Project
bash
Copy
Edit
# Clone the repo
git clone https://github.com/Harquin14/BLINKIT-SALES-ANALYSIS-WITH-PYTHON.git
cd BLINKIT-SALES-ANALYSIS-WITH-PYTHON

# Ensure Python and required libraries
pip install pandas numpy matplotlib seaborn

# Run analysis
# Either open and run in Jupyter:
jupyter notebook blinkit_analysis.ipynb
# Or execute script:
python blinkit_analysis.py
Key Insights & Findings
From the analysis, we observed:

Low Fat items outperform in total sales and ratings across multiple outlets.

Snack foods and Dairy emerge as high-revenue product categories.

Medium‑sized outlets and outlets in Tier‑3 locations demonstrate strong sales performance.

Earlier established outlets tend to have higher average ratings (suggesting operational maturity).

Recommendations
For Management
Prioritize stocking inventory in Low Fat & Snack segments.

Invest in expansion or retention strategies for Tier‑3 locations and medium outlets.

Leverage trends from outlet establishment data to guide new outlet rollout plans.

For Analysts & Stakeholders
Extend analysis with Machine Learning for price predictions and trend forecasting.

Incorporate sentiment analysis from customer reviews to enrich feedback insights.

Build an interactive dashboard using Plotly, Tableau, or Power BI for dynamic stakeholder reporting.

Future Work
Build predictive models on pricing or sales volume.

Integrate review data for deeper sentiment insights.

Deploy an interactive dashboard or web app for real‑time exploration.

License
This project is licensed under the MIT License – free to use, modify, and distribute.

Contact
Have questions or want to collaborate? Reach out:

GitHub: Harquin14

LinkedIn: (Add your LinkedIn profile here)
