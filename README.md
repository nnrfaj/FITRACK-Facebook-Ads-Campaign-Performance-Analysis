# FITRACK Facebook Ads Campaign Performance Analysis and Optimization Strategy

## Scenario

As a newly appointed Marketing Data Analyst at FITRACK, an innovative tech startup specializing in affordable, high-quality wireless earbuds, you've been entrusted with a critical task.

Your mission is to conduct an in-depth analysis of the company's recent Facebook Advertising campaign, which ran from July 1, 2023, to July 31, 2024.

This comprehensive analysis aims to uncover key insights that will shape FITRACK's future digital marketing strategies, particularly in preparation for an upcoming flagship product launch.

By leveraging data-driven decision-making, you're poised to provide valuable recommendations to stakeholders, optimize Ad Spend, and maximize campaign effectiveness in a competitive market landscape.

## Objective

To conduct a comparative analysis of Image, Video, and Carousel ad creatives within Fitrack's Facebook Advertising campaign, focusing on cost-effectiveness and conversion efficiency.

The goal is to identify the most impactful ad format and provide data-backed recommendations for resource allocation and creative strategy optimization in future campaigns.

## Tools Used

- Python: To generate a fictional dataset.

- Excel: For data exploration, cleaning, and analyzing.

- Google Looker Studio: To build an interactive dashboard.

- Google Sheet: To connect the dataset to Looker Studio. I tried connecting directly from Excel but couldn't get the date to work the way I wanted. It is still new, I am sure they will fix it.

## Extra Assets

[**Looker Studio Dashboard**](https://lookerstudio.google.com/reporting/e022cc5f-0e95-4ce6-8b51-62f983598a18)

[**Executive Summary**](https://docs.google.com/presentation/d/1rUEgiWZLGsODFYZyVN42QNmSjB5dXLoHCt3lU6Ld8j8/pub?start=false&loop=false&delayms=3000)

## Data Analysis Process Stages

From data collection / generation to analysis.

### 1.) Data Gathering

A fictional dataset was generated using Python script written by ChatGPT and Claude and edited by me.

I then used Jupyter Notebook to run this script and export the generated dataset as a CSV file.

### 2.) Data Loading and Cleaning

The data was loaded into Microsoft Excel for cleaning and transformation.

![1 generated dataset](https://github.com/user-attachments/assets/cd14fa68-108c-4de0-a27a-591133b464e7)

**Formatting**

- The date column was changed from general to Date format.

- The cost column was formatted as currency ($).

- Numerical columns, such as Clicks and Reach, were changed to Number format for accurate calculations.

**Column Re-arrangement**

- The 'Ad Set' and 'Ad Creative' columns were moved from the end of the data table to the beginning, just after the 'Campaign Name' column for logical flow.

- The 'Cost' (Amount Spent) column was placed after 'Ad Creative' and before 'Reach' and 'Impressions' columns.

### 3.) Data Transformation / Metric Calculations

Key performance metrics, including CTR (Click-Through Rate), CPC (Cost Per Click), CPM (Cost Per Mille), Conversion Rate, CPA (Cost Per Conversion), and Frequency, were calculated using Ads data such as Cost or Amount Spent on Ads, Reach, Impressions, Clicks, and Conversions.

![2 dataset after transformation and cleaning](https://github.com/user-attachments/assets/1edc9e9b-ed41-488a-a146-120649c0b6eb)

### 4.) Data Analysis

Pivot Tables were used to analyze the performance of different ad creatives.

## Analysis Results

Since the objective of this analysis was to compare the Ad Creatives and identify the best one, I focused on 5 key metrics for the analysis.

### 1.) Click-Through Rate (CTR)

- Carousel Ads: 2.63%

- Image Ads: 2.57%

- Video Ads: 2.55%

![CTR by Ad Creative](https://github.com/user-attachments/assets/fd87e56d-baaf-4706-ac61-0d3bb64d5240)

Carousel Ads have the highest CTR, indicating they are slightly more engaging in terms of encouraging clicks.

### 2.) Cost Per Click (CPC)

- Video Ads: $0.389

- Image Ads: $0.387

- Carousel Ads: $0.388

![CPC by Ad Creative](https://github.com/user-attachments/assets/0efe1465-90de-4059-8e0f-eb04530804a2)

Image Ads have the lowest CPC, making them the cheapest option for driving clicks, but the difference is minimal.

### 3.) Cost Per Mille (CPM)

- Video Ads: $9.48

- Image Ads: $9.61

- Carousel Ads: $9.82

![CPM by Ad Creative](https://github.com/user-attachments/assets/a7f0501c-a6a8-42fd-b51c-08b4d848a1a2)

Video Ads have the lowest CPM, making them the most cost-effective option for impressions.

### 4.) Cost Per Action / Conversion (CPA)

- Video Ads: $4.00

- Carousel Ads: $4.02

- Image Ads: $4.03

![CPA by Ad Creative](https://github.com/user-attachments/assets/5e59088b-eb94-489d-a16e-83e92565ff98)

Video Ads have the lowest CPA, meaning they are the most cost-effective at generating conversions.

### 5.) Conversion Rate

- Video Ads: 10.44%

- Carousel Ads: 10.35%

- Image Ads: 10.23%

![Conversion Rate by Ad Creative](https://github.com/user-attachments/assets/96a09a2c-4d5c-44ec-be2b-ad39c3ea2bf8)

Video Ads have the highest conversion rate, indicating they are the most effective at converting clicks into acquisitions.

## Insights

Based on the above metrics, Video Ads emerge as the most effective ad creative:

- Lowest CPM ($9.48): Cost-effective for generating impressions.

- Lowest CPA ($4.00): Cost-effective for acquiring customers.

- Highest Conversion Rate (10.44%): More effective at converting clicks into acquisitions.

While Carousel Ads have a slightly higher CTR, the marginal difference does not outweigh the overall cost-effectiveness and higher conversion rate of Video Ads.

Image Ads have the lowest CPC, but their slightly higher CPA and lower conversion rate compared to Video Ads make them less favorable overall.

## Recommendations

- Focus on Video Ads as the primary ad creative due to their overall cost-effectiveness and high performance in driving conversions. It should receive a higher budget allocation in future campaigns.

- However, it's also beneficial to maintain a mix of Carousel Ads and Image Ads to keep the audience engaged with varied content and test performance continuously.

- Optimize Content for Video Ads because of the slightly lower CTR compared to other ad types. Consider improving the visuals, messaging, and call-to-action elements to increase engagement.

- Regularly conduct A/B testing to refine video ad content and optimize performance further.

- Periodically update video ad creatives to prevent ad fatigue and maintain audience interest.

By focusing on Video Ads and incorporating these strategies, Fitrack can maximize the effectiveness of its future advertising campaigns, ensuring efficient use of resources and a higher return on investment.

## More Looker Studio Samples

[**GA4 E-Commerce Dashboard**](https://lookerstudio.google.com/u/0/reporting/7767f410-1843-4d05-a6b1-3d6e08c717db/)

[**Multi-Channel PPC Dashboard**](https://lookerstudio.google.com/reporting/fb173bf2-9e12-44ac-845c-581faeae325c)
