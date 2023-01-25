# Amazon_Vine_Analysis
## Overview
The goal of this analysis was to look at Amazon review information to determine if there was a significant bias in positive reviews for Vine members. The Vine program allows certain companies to provide products to users who are required to publish a review on the product. The dataset in this analysis was extracted and filtered to allow for easy analysis of product reviews. 

### Results
* Analysis of the dataset determined there were a total of 40,565 reviews. Of the total amount of reviews, 94 reviews were from Vine members, leaving the remaining 40,471 reviews from unpaid members.
*  Of the 94 Vine member reviews, 48 of them were five star reviews, meaning that Vine members left a five star review %51 of the time. 
*  Of the 40,471 unpaid member reviews, 15,711 were five star reviews, meaning unpaid members left a five star review %39 of the time. 

![reviews](https://user-images.githubusercontent.com/111502918/214469119-fd6bf1ec-ba39-4897-9d07-54fd19a6857d.PNG)

#### Summary
In this example, there appears to be a slight bias towards Vine members in regards to leaving favorable reviews. There's a difference of %12 of Vine member reviews being five stars compared to unpaid member reviews. For future analysis, I would recommend increasing the amount of data in the dataset, especially regarding Vine members. The lack of paid member review data could cause results to be skewed. Additionally, a machine learning model could be established to help predict whether members are more likely to leave a 5 star review depending on their Vine membership status. 
