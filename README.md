# 🧮 Katingos Sales Statistical Analysis (Jan–Sep 2025)
📉 Problem Solving  
I analyzed the company’s sales data from January to September 2025 to identify key insights and statistically validate hypotheses about performance by product line and sales channel. This analysis aims to support data-driven marketing decisions and resource allocation.

🎯 Objective  
To find actionable insights for the Marketing Department that help improve sales strategies and optimize marketing campaigns by understanding the behavior of different product lines, channels, and regions.

🚀 Tech Stack  
Languages: Python  
Data Science: pandas, numpy, math, scipy  
Visualization: matplotlib  
Environment: Jupyter Notebook, Visual Studio Code, Python virtual environments  

🗝️ Key Steps  
1.- Data Mining: Load and explore internal sales datasets (Jan–Sep 2025).  
2.- Exploratory Data Analysis (EDA): Detect patterns, trends, and missing data.  
3.- Data Preprocessing: Rename columns, clean data, handle missing values, and ensure consistent formatting.  
4.- Statistical Analysis: Perform Levene’s test for variance equality and a two-tailed Student’s t-test to compare group means.  
5.- A/B Test: Validate whether the baby product line performs significantly better in Amazon than in Mercado Libre.  
6.- Visualization: Create bar and pie charts to display sales by region, channel, and product line.  
7.- Conclusions: Summarize findings and provide recommendations for marketing and sales optimization.  

✅ Results  
After completing the project, the following key insights were found:  
-The brand has a strong presence in El Bajío and in the states of Nuevo León and Oaxaca.  
-The strongest channels are Amazon and Retail stores, which together hold the largest share of total sales.  
-The Baby product line leads total sales and performs best on Amazon.  
-The A/B test confirmed that baby product sales are 259% higher on Amazon compared to Mercado Libre — a statistically significant difference at α = 0.05.  

📊 Recommendations for the Marketing Team  
-Prioritize Amazon for digital marketing investments.  
-Strengthen the brand’s presence in El Bajío and northern Mexico, where conversion rates are higher.  
-Continue tracking sales by line and channel using statistical validation methods for future decision-making.  

▶️ How to Run  
1.- Clone this repository:  
git clone https://github.com/CesarLpzM/Spreads_company_sales_statistical_analysis.git  
2.- Create and activate a Python virtual environment:  
python -m venv venv  
source venv/Scripts/activate   # On Windows  
3.- Install dependencies:  
pip install pandas numpy scipy matplotlib  
4.- Open the project in VS Code or Jupyter Notebook and run the analysis cells.  
