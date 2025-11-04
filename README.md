# Myntra-Online-Retail-Customer-Segmentation-ML

<img width="747" height="420" alt="Image" src="https://github.com/user-attachments/assets/abd335a7-5b5c-4e9d-8c69-53570b2cd861" />

## About Company:
Myntra is a leading Indian fashion e-commerce company known for its wide range of clothing, accessories, and lifestyle products. While Myntra is recognized primarily for fashion, this dataset relates to the company's online retail operations for Myntra Gifts Ltd., a UK-based division specializing in unique all-occasion giftware. This dataset spans transactions from December 1, 2009, to December 9, 2011, and includes detailed records of sales made through Myntra Gifts Ltd.’s non-store online platform. The dataset provides a thorough snapshot of the company's international online retail activities during this period.

## Objective:

The primary purpose of analyzing this dataset is to extract valuable insights to enhance Myntra Gifts Ltd.'s business strategies. Specific goals include:

1) Identifying Purchasing Trends: Understanding patterns in customer purchases over time, including seasonal trends and product preferences, to better align inventory and marketing strategies.

2) Evaluating Product Performance: Assessing which products are most and least popular to optimize product offerings and make informed decisions about stock management and new product introductions.

3) Understanding Customer Behavior: Analyzing customer buying habits, frequency of purchases, and geographic distribution to tailor marketing efforts and improve customer segmentation.

4) Optimizing Pricing Strategies: Evaluating the relationship between unit prices and sales volume to refine pricing models and maximize revenue while ensuring competitive pricing.

5) Streamlining Inventory Management: Using sales and demand data to enhance inventory planning, reduce instances of overstock and stockouts, and improve overall inventory efficiency.

## DataSet:

1) InvoiceNo

2) StockCode

3) Description

4) Quantity

5) InvoiceDate

6) UnitPrice

7) CustomerID

8) Country

## Conclusion:

This project aimed to analyze and model the online retail data of Myntra Gifts Ltd., focusing on enhancing business strategies through data-driven insights. By working with a comprehensive dataset covering transactions from December 2009 to December 2011, we conducted a thorough analysis of sales patterns, customer behavior, and product performance.
Key data preprocessing steps included handling missing values, outlier treatment, categorical encoding, text cleaning (lowercasing and expanding contractions), and feature engineering (creating TotalPrice). Through data wrangling and visualization, we uncovered valuable insights such as purchasing trends, high-performing countries, peak transaction months, and correlations between variables.
We built multiple machine learning models to predict total sales and selected the Linear Regression model as our final model due to its high accuracy (R² = 0.98), low RMSE and MAE, and strong interpretability. Using model explainability tools like SHAP, we identified Quantity as the most influential feature in driving total sales, followed by UnitPrice.
Evaluation metrics were used not just to assess model performance, but to link results to business impact. Accurate sales forecasting supports inventory planning, pricing strategies, and marketing efforts, ultimately improving profitability and operational efficiency.In conclusion, this project successfully demonstrated how a combination of data analysis, visualization, and machine learning can empower business decisions. The insights gained can help Myntra Gifts Ltd. optimize its international retail operations and stay competitive in the evolving e-commerce landscape.

### Component and there Key Outcome / Insights:

1) Objective - Analyze Myntra Gifts Ltd.’s online retail data to extract insights and build predictive models.

2) Data Preprocessing - Handled missing values, outliers, encoded categories, and cleaned text for analysis-ready data.

3) Feature Engineering - Created TotalPrice from Quantity × UnitPrice to serve as target variable.

4) Visualization Insights - Identified top-selling countries, seasonal trends, high-demand products, and customer patterns.

5) ML Model Chosen - Linear Regression – due to high accuracy, low error rates, and interpretability.

6) Model Performance (R²) - 0.98 – indicates excellent prediction capability.

7) Important Features - Quantity and UnitPrice — both positively impact total sales.

8) Explainability Tool Used - SHAP (Confirmed Quantity as the most influential predictor).

9) Business Impact - Improved demand forecasting, pricing strategy, and inventory management.

10) Final Outcome - Delivered a reliable, interpretable, and high-performing model aligned with business goals.



