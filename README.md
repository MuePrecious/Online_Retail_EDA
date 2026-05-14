# Data Cleaning and Exploratory Data Analysis
### Project Overview
---
This dataset contains all purchases made for an online retail company based in the UK, it is dirty and is to be cleaned for Exploratory Data Analysis and visualization to draw meaningful business insights and give recommended data-driven decisions.

### Dataset
OnlineRetail Dataset from Kaggle
* Download [here](https://www.kaggle.com/datasets/vijayuv/onlineretail)

### Tools
---
* Python (Pandas, Numpy, Matplotlib, Seaborn)

##### Data Cleaning Process
---
1. Performed data familiarization to assess the dataset structure, data types, and missing values.
2. Handled missing data by removing or replacing null values where necessary.
3. Identified and removed duplicate records.
4. Standardized the data through consistent text casing and proper data type formatting.
5. Conducted data validation by detecting and removing extreme outliers and zero values in numeric columns.
6. Performed feature engineering by:
* Creating a new Sales column
* Splitting the Date column into Day, Month, and Year and formating into integer
* Dropping unnecessary columns
7. Conducted a final inspection of the cleaned dataset.
8. Saved the cleaned dataset as a CSV file.

### Exploratory Data Analysis (EDA) Process
1. Loaded the cleaned dataset for analysis.
2. Generated summary statistics to understand the distribution and characteristics of the data.
3. Created visualizations to analyze trends across time, regions, products, and relationships between variables.
4. Generated insights and recommendations based on the analysis findings.
5. Concluded the analysis with a summary of key findings and the overall analytical process.

### Visualizations

<img width="1178" height="1060" alt="OnlineRetail Visualization" src="https://github.com/user-attachments/assets/c2d027e7-2548-4d5b-a705-1f9ffc65aeae" />



### Business Insights
* Sales declined in January, April, and July, while peak sales were recorded in February, May, and September.
* The top three purchasing countries (UK excluded) by sales were Germany (92,911), France (84,222), and EIRE (75,349). The least-performing countries included Bahrain (218), Czech Republic (160), and Saudi Arabia (120).
* The product “Jumbo Bag Red Retrospot” (9,854)recorded the highest quantity ordered, while “Hanging Ridge Glass T-Light Holder” (-24) recorded the lowest quantity sold due to product returns, resulting in negative values.
* A weak negative correlation (-0.26) exists between unit price and quantity ordered, indicating that lower prices tend to encourage higher purchase volumes.
* Sales and quantity ordered showed a strong positive correlation (0.69), suggesting that higher order quantities significantly contribute to increased sales revenue.

### Recommendations
* Increase inventory levels and staffing during peak sales periods. For example, promote gift items in February for Valentine’s Day, children-related products in May, and seasonal decorations toward September in preparation for Halloween.
* Implement targeted marketing campaigns in low-performing regions such as Bahrain, the Czech Republic, and Saudi Arabia to improve customer engagement and sales.
* Maintain higher inventory levels for high-demand products such as “Jumbo Bag Red Retrospot.” Additionally investigate the causes of low demand and product returns associated with “Hanging Heart T-Light Holder.”
* Introduce promotional pricing and discount strategies where appropriate, as lower unit prices appear to encourage increased purchasing volume.

### Limitations
The Online Retail dataset underwent extensive cleaning, during which approximately 30% of the rows were removed with large extreme outliers making up the majority(28%), and missing values, duplicates, and invalid zero-value entries made up the remaining 2%.

### Conclusion
The findings suggest that the company can improve overall performance through:
* Increased inventory during peak sales periods
* Stronger regional marketing strategies
* Greater availability of high-demand products
* Improvements to low-performing products
* Strategic promotional discount campaigns

