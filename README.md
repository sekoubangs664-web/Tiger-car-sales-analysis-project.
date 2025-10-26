# Tiger-car-sales-analysis-project.
This project analyzes a used car sales dataset to uncover trends in pricing, profitability, and seller performance. Using SQL, I performed data cleaning, exploratory analysis, and advanced queries to generate actionable business insights.

The dataset includes fields such as year, make, model, trim, body type, transmission, VIN, state, condition, odometer, color, interior, seller, MMR (Manheim Market Report value), selling price, and sale date.

Key Objectives

Clean and validate data (remove duplicates, standardize fields, and handle missing values).

Explore overall market performance by calculating total sales, average prices, and mileage distributions.

Compare actual selling prices against MMR to identify profitable deals and outliers.

Rank makes, models, and sellers by sales volume and profitability.

Analyze customer preferences across vehicle features such as color, transmission type, and body style.

Examine seasonality and sales trends over time.

SQL Techniques Used

Data Cleaning: DISTINCT, CASE, string functions, filtering.

Aggregations: SUM, AVG, COUNT, GROUP BY.

Window Functions: RANK(), ROW_NUMBER(), PARTITION BY.

Date Functions: DATEPART, EXTRACT for time-based analysis.

Subqueries & CTEs: For ranking, outlier detection, and advanced comparisons.

Business Insights

Identified the top-performing makes and models that consistently sell above market value.

Revealed the effect of mileage, condition, and year on resale price.

Found sellers who outperform others by selling above MMR benchmarks.

Discovered seasonal peaks in sales activity and pricing trends.
