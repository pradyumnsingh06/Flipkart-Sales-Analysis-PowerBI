Flipkart Sales & Quality Analysis

Project Overview:
This project is a comprehensive analysis of a Flipkart sales dataset containing over 20,000 product listings. The primary goal was to use Power BI to clean, model, and visualize the data to uncover actionable insights that could inform business strategy, improve customer satisfaction, and drive strategic growth.

The analysis focuses on three core business questions:

What are our most valuable product categories?

How does product quality vary across the platform?

How effective is our current pricing and discount strategy?

Dashboard Preview
Here is a preview of the final three-page interactive dashboard built in Power BI.

![Executive Summary](https://raw.githubusercontent.com/pradyumnsingh06/Flipkart-Sales-Analysis-PowerBI/main/Screenshot%202025-07-24%20182839.png)

![Executive Summary](https://raw.githubusercontent.com/pradyumnsingh06/Flipkart-Sales-Analysis-PowerBI/main/Screenshot%202025-07-24%20182851.png)

[Executive Summary](https://raw.githubusercontent.com/pradyumnsingh06/Flipkart-Sales-Analysis-PowerBI/main/Screenshot%202025-07-24%20182905.png)

Data Cleaning & Transformation (Power Query)
The raw dataset required significant cleaning to be usable for analysis. The primary challenge was the Main_Category column, which contained a mix of structured "breadcrumb" text and unstructured product names.

The following steps were taken in Power Query to create a clean Clean Category column:

Isolate Structured Data: A conditional column was used to identify rows containing the >> delimiter.

Extract Main Category: The "Split Column by Delimiter" function was used to extract the true main category from the structured data.

Group Unstructured Data: All remaining rows (unstructured product names) were grouped into a single "Other" category for clarity.

Data Type Correction: All numeric and date columns were converted to their correct data types.

DAX Measures:
New measures, such as Average Discount %, were created to enable deeper analysis.

Key Findings & Recommendations
Finding 1: Jewellery is the Star Performer
Observation: Jewellery is the most valuable category, demonstrating a powerful combination of high sales volume, significant market demand, and strong customer satisfaction (4.14 average rating).

Recommendation:
Protect and grow this segment by promoting top-rated products and ensuring a robust supply chain.

Finding 2: The "FK Advantage" Paradox
Observation: The "FK Advantage" badge, intended as a mark of quality, is associated with lower average ratings in key categories like Clothing and Jewellery.

Recommendation:
Re-evaluate the "FK Advantage" criteria to include mandatory product quality standards, not just logistics and shipping speed.

Finding 3: High Discounts on Unrated Products
Observation: Products with no customer ratings often receive the highest discounts, suggesting a strategy of using price cuts to move unpopular or low-quality inventory.

Recommendation:
Adopt a "Smart Discounting" policy. Shift from clearing unpopular stock to amplifying "winner" products and using discounts to incentivize initial reviews on new items.

Tools Used

Microsoft Power BI: For data modeling, analysis, and dashboard creation.
Power Query: For data cleaning and transformation.
DAX: For creating custom measures and calculations.
Microsoft PowerPoint: For summarizing findings and creating the final presentation.
