**Retail Sale Data Analysis Using Power BI**

**Introduction**
This project showcases a comprehensive analysis of retail sales data through a Power BI dashboard. The primary goal is to glean insights into sales trends, the impact of discounts on sales, and to identify peak sales hours across different city locations.

**Dataset Description**
The dataset used in this project pertains to retail sales transactions. Each record represents a transaction with details such as transaction date, hour, location, number of items, amount of sale, coupon flag and discount amount. For privacy reasons, the dataset source cannot be shared publicly.

**Transformations and Assumptions**
During the data preparation phase, the following transformations and assumptions were made:

Time Transformation: The original dataset contained transaction times as dates; these were transformed to hours to facilitate analysis of peak sales periods.
Handling Missing Values: Approximately 70% of 'coupon flag' and 'discount amount' fields were missing. It was assumed that missing 'coupon flag' values equated to 'No' (no coupon used), and missing 'discount amount' values were treated as zero, indicating no discount was applied.
Discount Status Column: A new column named 'discount status' was created to categorize transactions into 'Discounted' and 'Non-Discounted' based on the presence of a discount amount.
Features and Dashboard Description

**The Power BI report is spread across two dashboards:**

Dashboard 1: Analyzes peak sales hours across different cities, enabling the identification of strategic hours for targeted marketing or staffing.
Dashboard 2: Explores the correlation between sales amounts and discounts applied, offering insights into the effectiveness of discounts on sales performance.

**Usage**
To interact with the dashboard:
Use the slicers to filter data by city, date, and other relevant dimensions.
Hover over visual elements to see detailed data points and trends.

**Requirements**
Power BI Desktop (latest version recommended) is required to interact with the .pbix file included in the repository.
