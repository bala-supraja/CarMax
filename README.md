# CarMax Project
This project is a Python Colab notebook that presents an analysis conducted to provide marketing and inventory recommendations for CarMax's strategies aimed at optimizing operations for their new stores.

The data I am working with is from CarMax's 2024 Case Competition. Here is the link: https://github.com/kmx-analytics-showcase/Fall-2024/blob/64bea6dc5f535a7a92119f73b25e4a4a00a176cd/README.md

# Problem Statement
CarMax is considering opening new stores in the United States. How should marketing and inventory strategy be approached to drive maximum sales depending on the location of the new store?

# Data Set and Important Files
The data is composed of purchasers and non-purchasers and their shopping journey details, such as number of website visits, marketing touchpoints, geographic details, and vehicle purchase attributes. Vehicle purchasers bought a vehicle from CarMax; whereas non-purchasers did not purchase a vehicle with CarMax .

Disclaimer: This is pseudorandomly generated and manipulated CarMax data. No data corresponds directly to reality, but is inpired by and mimics true data. No data represents current CarMax inventory and business.

Relevant Files:

CarMax_Case_Study.ipynb - This file contains the Python code for analysis, including visualizations, commentary, and actionable suggestions.
Fall 2024 dataset (1).csv - the data set containing the relevant KMX purchases and non-purchases to be used in the analysis.
Fall 2024 Showcase Data Dictionary.xlsx - information about each feature in the data set.

# Inventory Suggestions from Analysis:
**Focus on High-Demand Vehicle Types:** Since we’ve observed that Small SUVs and Medium SUVs are consistently the top two most purchased vehicle types across all states, we should prioritize stocking these vehicles in the new stores to meet universal customer demand.

**Regional Adjustment for Third-Position Vehicles:** Because the third most purchased vehicle type varies by state (e.g., Pickup trucks, Compact cars, Luxury cars, or Mid-size cars), we should fine-tune the inventory for new stores based on regional preferences to optimize sales.

**Standardize Inventory for Low-Demand Vehicles:** Since Large SUVs, Vans, Sports Cars, Full-Size, and Mid-Size cars consistently occupy the bottom positions across states, we should limit stocking these vehicle types in new stores to avoid overstocking low-demand items.

**Prepare for Financing Preferences:** Because 75% of transactions are financed purchases, we should ensure that the inventory strategy aligns with this preference, focusing on vehicles that appeal to financing customers, such as Small and Medium SUVs.

**Regional Focus on Outright Purchases:** Since outright purchases vary across states (e.g., Idaho has the highest at 35%, Mississippi the lowest at 16%), we should consider these variations when planning inventory for states with a higher inclination toward outright payments.

**Prepare for Service Plan Purchases:** Since we’ve noticed that up to 70% of purchasers opt for a service plan and that service plans are more commonly included with financed purchases, we should ensure a good supply of service plans and design processes to integrate them seamlessly into financed transactions.

**Cater to Trade-In Customers:** Because 27% of purchases involve trade-ins and 38% of trade-in customers proceed to purchase, we should maintain an inventory that appeals to trade-in customers, focusing on high-demand vehicles like Small SUVs and Medium SUVs, which are likely to convert trade-ins into purchases.

# Marketing Suggestions from Analysis:

**Leverage Campaigns B and C:** Since we’ve observed that Campaigns B and C achieve conversion rates of 33% and 45%, respectively, we should prioritize a combination of these campaigns in new states. Campaign B’s wider reach and Campaign C’s higher conversion rate make them complementary for maximizing awareness and conversions.

**Optimize "No Campaign" Opportunities:** Since the "No Campaign" group accounts for more conversions than Campaign B despite its lower conversion rate, we should identify what drives these organic engagements.

**Combine Campaign Overlaps for Higher Impact:** Since customers exposed to multiple campaigns tend to convert at a higher rate (up to 75.8%), we should explore overlapping Campaigns B and C in targeted marketing strategies. This could involve unified messaging across digital, social media, and traditional channels.

**Invest in Awareness-First Strategies:** Because we noticed the "awareness period" in campaigns drives initial interest, the new stores should employ early-stage marketing tactics such as teaser campaigns, local events, and introductory offers to spark curiosity and drive foot traffic.

**Engage the Untapped "No Campaign" Trade-In Segment:** Since a significant percentage of trade-ins occur without campaign influence, new stores should focus on localized marketing strategies to engage this audience. Utilize targeted ads, email campaigns, and in-store promotions to encourage trade-in customers to convert to purchases.

**Replicate the Success of Campaign C:** As Campaign C demonstrates the highest purchase-after-trade-in percentage, new stores should analyze and adopt similar messaging and strategies for their local markets. Emphasize clear, compelling trade-in benefits tailored to regional preferences.

**Develop Trade-In Focused Campaigns for New Markets:** Since trade-ins serve as a valuable customer engagement point, new stores should implement campaigns exclusively promoting the trade-in process. Highlight features like instant appraisals, flexible financing options, and the ease of upgrading vehicles.

**Leverage Overlapping Campaign Strategies:** Since customers targeted by all three campaigns (A, B, and C) exhibit an impressive 75.8% conversion rate, new stores should adopt an overlapping campaign approach. Coordinate messaging across campaigns to reinforce brand awareness and drive higher engagement among potential customers.

**Introduce Awareness Periods for Untargeted Audiences:** Since "No Campaign" purchasers lack engagement opportunities, new stores should implement minimal awareness mechanisms, such as personalized email follow-ups, targeted ads, or in-store promotions. These efforts can bridge the engagement gap and convert untapped potential into actual sales.

**Target Non-Purchasers with Re-Engagement Strategies:** Since many non-purchasers interact significantly with campaigns before disengaging, new stores should implement remarketing campaigns targeting these individuals. Offer tailored incentives such as discounts, exclusive offers, or educational content to encourage conversion.
