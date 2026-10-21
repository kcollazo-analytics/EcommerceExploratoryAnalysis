<h1 align= "center"> 
  Ecommerce_ExploratoryAnalysis_GS </h1>
 
## Introduction
This is an exploratory data analysis (EDA) of a synthetic e-commerce dataset with a timeline that ranges from 2022 - 2035. The dataset is sourced from Kaggle and the project is conducted entirely in Google Sheets. The analysis focuses on transforming the raw transactional data into actionable business insight using spreadsheet functions and pivot tables. 

## Data Transformation
After creating a copy of the original dataset onto a new sheet, I confirmed that the data from Kaggle was clean. Using the Data Cleaning tools, I made sure that there were no duplicates, random whitespaces, or nulls. Additionally, I updated the formatting for dollar amounts in the proper columns. Lastly, 2035 data has been omitted from this analysis to avoid skewing annual trends with incomplete, partial-year data.

## Data Analysis
The next step in my process consisted of creating pivot tables. I made them with the intention of answering various questions that will lead to a better understanding of the overall dataset. 

**1. How has the revenue changed among the different regions from 2022 to 2034?**
   
<img width="608" height="339" alt="RevenueByRegion" src="https://github.com/user-attachments/assets/2bc73b38-a71b-45e5-8e16-8d7e06092cbe" />


**2. How has the revenue changed among the different product categories from 2022 to 2034?**

<img width="607" height="341" alt="RevenueByProductCategory" src="https://github.com/user-attachments/assets/3353a7b0-8358-411a-9665-d2d2157a00f9" />

  
**3. How many reviews are there for each product category? How does rating volume across different tiers differ by product category?**

<img width="607" height="149" alt="RatingsForProductCategory" src="https://github.com/user-attachments/assets/cbc8f37f-8aaf-49b6-bc71-80a02b83f09d" />

## Data Visualization

By using the information from the pivot tables, I was able to create various charts that help explain important aspects about the ecommerce dataset. 

### Annual Revenue Totals
<img width="473" height="290" alt="AnnualRevenueTotals" src="https://github.com/user-attachments/assets/a79aa3ea-dc0b-41d3-bcef-3cd2fa217b4a" />

- **Core Trend:** Overall linear trendline steadily increases over 13 year period (2022-2034)
- **Baseline Performance:** Most annual revenues stay above the $350,000 threshold
- **Historical Low:** Minimum revenue was $349,802.33 in 2025
- **Peak Performance:** Maximum revenue was $408,725.72 in 2033

**Next Steps:** 
Investigate the root causes for recurring revenue dips in 2025, 2029, 2031, and 2034. Revenue does recover after each drop and so we see the steady increase in the trendline, however stabilizing these fluctuations provides an opportunity to even out cash flow and rise above the $408k ceiling.

### Annual Revenue by Region 
<img width="709" height="437" alt="AnnualRevenueRegion" src="https://github.com/user-attachments/assets/1290f080-1137-44e4-9a84-3833e5c27295" />

- **Core Trend:** The overall data is highly volatile as it stays clustered between $75,000 and $115,000. There are many intersections and no universal growth or decline trend.
- **South Region:** Demonstrates steady long-term revenue increase
- **West Region:** Contains noticeable revenue spikes between 2026-2028 and a resurgence in 2034
- **North Region:** Used to be the largest market in 2022 but contracted since then. It hit a significant low of $79,462.82 in 2031 before a brief recovery in 2033 with $108,414.53
- **East Region:** Tracked closest to the overall median performance, but fell to the lowest overall position in 2034 at $71,690.17

**Next steps:**
- **Replicate Success:** Study operational factors to maintain Southern success and identify scalable practices that can be applied to other regions
- **Analyze Spikes** Find the main causes for localized spikes in the West to see how this area's revenue can be stabilized
- **Mitigate downturn** Audit the 2034 downturns for the East, North, and South to apply local stabilization strategies

### Total Revenue by Category
<img width="477" height="298" alt="TotalRevProduct" src="https://github.com/user-attachments/assets/cac6d113-e894-4f6c-9e31-64184062f008" />

**Core Trend:** Electronics generated the highest revenue at $1.7M, followed by Clothing at $1.4M. Home brought in $0.9M ($937K), and Beauty was the lowest performing category at $0.7M ($734k). 

**Next Steps**
It is recommended that we maintain our high performers by exploring what is the reason for such high success, while also looking into raising the revenue of Home and Beauty. A good example would be to use the cross-selling method especially for holidays where we can choose a theme and market products in each category.

### Customer Ratings
<img width="483" height="295" alt="CustomerReviews" src="https://github.com/user-attachments/assets/a1a10774-ae59-4ad1-99b8-4865cddbac5a" />

**Core Trend** The ratings are on a scale from 1-5. Each rating on that scale has a similar amount of reviews surpassing the 1,100 threshold giving us a sufficient amount of data to work with. 

Electronics has the largest amount of customer ratings across each group. It is followed closely by the Clothing category. We then see Home with the third highest amount of ratings and lastly the Beauty category. 

**Next Steps**
The data suggests that the reviews match the pattern of Total Revenue by Category. We can thus infer that this ecommerce company is mostly known for its Electronic products. 

It is recommended to study the reviews further to understand why most of the electronic reviews are in the 2-4 range.  

Additionally, we may want to see about expanding in the other categories by understanding the customers demands so that we may increase revenue through those pipelines as well. 

By understanding critiques and demands, we can build trust in the brand and increase customer retetioin. 



