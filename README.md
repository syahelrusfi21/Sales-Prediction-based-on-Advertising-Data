# Sales Prediction based on Advertising Data

## Study Case
A health product entrepreneur is facing a problem of declining sales, despite implementing various strategies to boost product sales. The entrepreneur possesses a CSV dataset containing columns for sales and advertising data. As a machine learning engineer, what would you do to provide predictions about the relationship between sales and advertising to the entrepreneur?

## Goals
Predicting sales based on product advertising across multiple platforms.

## Objectives
- Building a linear regression model to predict sales
- Determining whether advertisements on TV, Billboards, Google Ads, Social Media, Influencer Marketing, and Affiliate Marketing influence sales fluctuations
- Identifying platforms that have the potential to provide significant advantages in product promotion.

## Result
Based on the analysis conducted, the regression model obtained is as follows:

**Product_Sold = -0.2172 + 0.2003 (TV) + 0.2983 (Billboards) + 0.1480 (Google_Ads) + 0.2468 (Social_Media) + 0.1201 (Influencer_Marketing) + 0.3932 (Affiliate_Marketing)**

With the following evaluation metrics:

- **Mean Absolute Error (MAE):** 0.0008322734331092896  
- **Mean Squared Error (MSE):** 1.0241796771915838e-06  
- **R-squared (R²) Score:** 0.9999659903345287  

## Conclusion  
Advertising through **TV**, **Billboards**, **Google Ads**, **Social Media**, **Influencer Marketing**, and **Affiliate Marketing** influences the increase or decrease in product sales. It is recommended to consider utilizing these platforms in the product marketing strategy, especially **Affiliate Marketing**, which shows significant potential to drive sales growth.
