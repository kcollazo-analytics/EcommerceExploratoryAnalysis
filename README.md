<h1 align= "center"> 
  Sales Performance and Customer Satisfaction Analysis </h1>


## Executive Summary
This is an exploratory data analysis (EDA) of a synthetic e-commerce dataset with the timeline from 2022 - 2035. The analysis focuses on transforming the raw transactional data into actionable business insight using spreadsheet functions and pivot tables. After careful analysis it can be concluded that this e-commerce store is steadily increasing its annual revenue. The dataset also has a multitude of customer ratings across all categories with the majority landing in the Electronics and Clothing categories. 

## Business Problem
This analysis was conducted to gain an understanding of the overall sales performance of the E-commerce store throughout the years while also having a focus on the customer satisfaction rates. This was done by answering the following questions:
- What is the total revenue for each year in business?
- How did the revenue differ across the different geographical regions?
- How does the revenue earned differ for each product category?
- What are the customer ratings throughout the product categories?

## Data Preparation
The E-commerce dataset is sourced from Kaggle; it contains 12 columns and 4991 rows. 

After creating a copy of the original dataset onto a new sheet, I performed data sanitation and validation techniques. Using the Data Cleaning tools, I made sure that there were no duplicates, random whitespaces, or nulls. Additionally, I standardized the formatting for dollar amounts in the necessary columns. Lastly, 251 rows of data have been omitted from this analysis to avoid skewing annual trends with incomplete, partial-year data.

## Data Analysis
The next step in my process consisted of creating pivot tables that would pull together the data to answer the questions above. 

**Yearly Revenue across different locations**
   
<img width="608" height="339" alt="RevenueByRegion" src="https://github.com/user-attachments/assets/2bc73b38-a71b-45e5-8e16-8d7e06092cbe" />


**Yearly Revenue across different product categories**

<img width="607" height="341" alt="RevenueByProductCategory" src="https://github.com/user-attachments/assets/3353a7b0-8358-411a-9665-d2d2157a00f9" />

  
**3. What are the customer ratings throughout the product categories?**

<img width="607" height="149" alt="RatingsForProductCategory" src="https://github.com/user-attachments/assets/cbc8f37f-8aaf-49b6-bc71-80a02b83f09d" />

## Data Visualization

By using the information from the pivot tables, I was able to create various charts that help explain important aspects about the E-commerce dataset. 

### Annual Revenue Totals
<img width="473" height="290" alt="AnnualRevenueTotals" src="https://github.com/user-attachments/assets/a79aa3ea-dc0b-41d3-bcef-3cd2fa217b4a" />

- **Core Trend:** Overall linear trendline steadily increases over 13 year period (2022-2034)
- **Baseline Performance:** Most annual revenues stay above the $350,000 threshold
- **Historical Low:** Minimum revenue was $349,802.33 in 2025
- **Peak Performance:** Maximum revenue was $408,725.72 in 2033

**Next Steps:** 
- **Revenue Dips** Investigate the root causes for recurring revenue dips in 2025, 2029, 2031, and 2034 to stabilize fluctuations
  
### Annual Revenue by Region 
<img width="709" height="437" alt="AnnualRevenueRegion" src="https://github.com/user-attachments/assets/1290f080-1137-44e4-9a84-3833e5c27295" />

- **Core Trend:** The overall data stays clustered between $75,000 and $115,000. There are many intersections and no universal growth or decline trend.
- **South Region:** Demonstrates steady long-term revenue increase
- **West Region:** Contains noticeable revenue spikes between 2026-2028 and a resurgence in 2034
- **North Region:** Used to be the largest market in 2022 but contracted since then. It hit a significant low of $79,462.82 in 2031 before a brief recovery in 2033 with $108,414.53
- **East Region:** Tracked closest to the overall median performance, but fell to the lowest overall position in 2034 at $71,690.17

**Next steps:**
- **Analyze Spikes** Find the main causes for localized spikes in the West to see how this area's revenue can be stabilized
- **Mitigate downturn** Audit the 2034 downturns for the East, North, and South to apply local stabilization strategies

### Total Revenue by Category
<img width="477" height="298" alt="TotalRevProduct" src="https://github.com/user-attachments/assets/cac6d113-e894-4f6c-9e31-64184062f008" />

**Core Trend:** Electronics generated the highest revenue at $1.7M, followed by Clothing at $1.4M. Home brought in $0.9M ($937K), and Beauty was the lowest performing category at $0.7M ($734k). 

**Next Steps**
-**Study Success and Failures** Understand why Electronics and Clothing outperform Health and Beauty. Is it marketing techniques, product availability, the main niche of the brand?
-**Cross-Selling Method** Market products from different categories together to shine light on the slow moving merchandise. 

### Customer Ratings
<img width="483" height="295" alt="CustomerReviews" src="https://github.com/user-attachments/assets/a1a10774-ae59-4ad1-99b8-4865cddbac5a" />

**Core Trend** The ratings are on a scale from 1-5. Each rating on that scale has a similar amount of reviews surpassing the 1,100 threshold giving us a sufficient amount of data to work with. 

Electronics has the largest amount of customer ratings across each group. It is followed closely by the Clothing category. We then see Home with the third highest amount of ratings and lastly the Beauty category. 

**Next Steps**
-**Electronics** Study why most of the electronic reviews are in the 2-4 range.  
-**Increase Purchases of Other Product Categories** Understand the customer's demands so that we may increase revenue through those pipelines as well. 

## Conclusion

The exploratory analysis of this E-commerce dataset has shown that this company in question is increasing its revenue year after year. The different regions that the company sells to have unique sales patterns and it is recommended that different teams tackle the needs of each region. The different product categories have unique performance data as well and should be studied alongside the customer reviews to ensure the highest customer satisfaction score possible for the company as a whole. 





