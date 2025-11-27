# Adidas-Vs-Nike
We investigated how Adidas and Nike position their products through pricing, discounts, customer engagement, and satisfaction.
Our analysis answers the three main research questions outlined on page 7 of the project description :
How do pricing strategies differ between Adidas and Nike, and how do price, discounts, and customer ratings relate?
Which brand achieves higher engagement (reviews) and satisfaction (ratings)?
Do the brands follow distinct product-positioning strategies?
Data Cleaning & Preparation
According to the cleaning summary (page 2 of the presentation ):
Filled missing descriptions, ratings, and reviews using appropriate imputations.
Standardized Adidas sub-brands into a single ADIDAS group.
Replaced 426 Nike rows with missing listing prices using sale price values (because discount = 0).
Removed 89 duplicate product IDs.
Converted price fields to correct format (/100).
Prepared final dataset with consistent pricing, discounting, and rating metrics.

Database: https://www.kaggle.com/datasets/kaushiksuresh147/adidas-vs-nike

Used Molab/Marimo for coding part and graphs

Key Findings
1. Pricing Strategy – Nike is Premium, Adidas is Mid-Price
Supported by the listing price distribution graph on page 3 .
Adidas has a narrow peak around €50–€80 → tightly clustered mid-price products.
Nike has a wide, flat distribution from €80–€150+ → premium segmentation with more high-end items.
Nike prices are ~48% higher on average (page 11) .
Conclusion:
Nike defends a premium position; Adidas competes on accessible pricing.
2. Discounting Behavior – Adidas Discounts Heavily, Nike Not at All
Shown on page 12.
Adidas discounts aggressively (20–60%).
Nike’s discount rate is a flat 0% across all products.
Discounting significantly increases engagement (correlation = 0.318, page 8) .
Conclusion:
Adidas: volume-driven, promotion-oriented.
Nike: strict price integrity to protect brand equity.
3. Customer Engagement – Adidas Wins (Mass Market)
Page 7 visualization.
Adidas average reviews: ~49.2
Nike average reviews: ~10.6
Discounted, lower-priced Adidas products generate significantly more reviews.
4. Customer Satisfaction – Nike Wins (Premium Expectations)
Page 7 right chart.
Adidas avg. rating: 3.37
Nike avg. rating: 4.25 (after removing review=0 rows)
Nike ratings are higher but more volatile (page 13) .
5. Price & Discount Have No Influence on Ratings
Correlation matrices.
Price ↔ Rating = no correlation
Discount ↔ Rating = no correlation
Ratings remain stable regardless of price or discount.
Final Conclusion
Summarized on page 15 .
Adidas and Nike occupy entirely different competitive spaces:
Adidas = Mass-Market, Value-Driven
Lower prices
Heavy discounts
High engagement
Stable ratings
Nike = Premium, Equity-Driven
High prices
Zero discounts
Lower engagement
Higher—but more volatile—ratings
These differences reflect deliberate, opposing product-positioning strategies.
