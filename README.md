# Retail-Sales-Analysis

## **Sales Order Data Analysis: Initial Insights** 
This report summarizes the initial analysis of a sales order dataset, likely for a vehicle company, obtained from Kaggle during the HNG Stage Zero data analysis internship ([https://hng.tech](https://hng.tech/internship)/). This exploration aimed to gain a high-level understanding of the data and identify initial patterns.


## **The Dataset**
The dataset contains information on 307 orders, including details like order number, quantity, price per item, date, status, and customer information. Categorical data includes product line, status, and country, while numerical data encompasses quantity, price, and sales.

## **Initial Observations**
**•	Product Distribution:** Order distribution varies significantly across product lines. "Classic Cars" and "Vintage Cars" have the highest number of orders, while "Trains" have the fewest. This can inform inventory management and marketing strategies by highlighting potential best- and worst-selling categories.

**•	Geographic Distribution:** Most orders originate from the USA (1004), followed by Spain (342) and France (314). This identifies the company's primary markets and lays the groundwork for further geographic analysis. High-order countries indicate a strong market presence, while lower values suggest potential expansion areas.


## **Data Quality Issues**
Missing values are present in some columns:
**•	State (1,486 missing):** This is crucial for location-based insights, especially in the USA.
**•	Postal Code (76 missing):** Missing postal codes can hinder precise location analysis.
**•	Territory (1,074 missing):** Incomplete territory information can affect sales analysis across regions.
**•	Order Date Format:** The format of "ORDERDATE" (e.g., 11/14/2003) might require conversion for time-series analysis.


## **Further Exploration**
•	Analyze sales trends over time (monthly, quarterly, yearly).
•	Identify top-selling products and assess their profitability.
•	Understand customer demographics and buying behavior based on location and order size.
•	Investigate the relationship between order status and factors like quantity or price.
•	Explore correlations between orders and sales by country.

## **Additional Notes**
•	The meaning of "DEALSIZE" (Medium, Small, Large) needs clarification.


## Conclusion
This initial exploration provides a foundation for understanding the sales order data. Further analysis with data cleaning, transformation, and potentially dropping unnecessary columns can yield valuable insights to improve sales strategies, product offerings, and customer targeting.
HNG Internship
Learn more about the HNG Internship program: [https://hng.techpremium](https://hng.tech/premium)
/.
