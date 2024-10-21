### Home Sales Data Analysis
### Project Overview
This project analyzes home sales data using PySpark to gain insights into housing trends, pricing, and features. The analysis includes various data transformations, aggregations, and visualizations.

The dataset used for this analysis is sourced from AWS S3 and contains information on home sales, including features such as price, number of bedrooms, bathrooms, square footage, and view ratings.

Dataset URL: Home Sales Data

Technologies Used
Apache Spark: For data processing and analysis

Python: Programming language used for scripting

PySpark: Python API for Spark

Jupyter Notebook: Environment for interactive coding and visualization

Calculated average prices per view rating, filtering for homes priced over $350,000.

Grouped and aggregated data based on various features such as bedrooms, bathrooms, and date_built.

Caching:

Cached the temporary table home_sales for optimized performance during analysis.

Results
Average price per view rating was calculated and filtered for homes priced greater than or equal to $350,000.

Other significant trends and insights from the data analysis can be included here.

Conclusion

This analysis provides valuable insights into home sales data, helping stakeholders make informed decisions based on housing market trends. Future work could involve more complex visualizations or predictive modeling.
