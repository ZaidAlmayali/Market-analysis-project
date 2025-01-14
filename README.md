# **Project Background**

Vendora is a leading online retail company offering a wide variety of products through its e-commerce platform. With a strong presence in the digital marketplace, Vendora continuously invests in marketing campaigns and customer engagement strategies to drive growth and enhance customer experiences.
This project focuses on conducting an in-depth data analysis of Vendora marketing performance, customer engagement, and feedback. The goal is to uncover insights that can inform strategic decisions, optimize marketing efforts, and improve overall business performance.

**Focus Areas of Analysis:**

- Conversion Rate Analysis:
Examining the user journey on the website to identify opportunities for improving the conversion of visitors into customers and increasing the Average Order Value (AOV)

- Customer Engagement Trends:
Analysing how customers interact with marketing content across various channels to identify the factors contributing to decreased engagement.

- Customer Feedback Analysis:
Performing sentiment analysis on customer reviews and social media comments to better understand customer satisfaction and areas needing improvement.

An interactive Power BI dashboard showcasing key findings can be accessed [here].

SQL queries used for data inspection and quality checks are available [here].

SQL queries for data cleaning and dashboard preparation can be found [here].

Additional SQL queries addressing business-specific questions are provided [here].

# Data Structure & Initial Checks

The company’s main database structure as seen below consists of seven tables: Customers, Products, Customer_reviews, Customer_reviewsSentiment, Engagement_data, Customer_journey, Calendar and Country with a total row count of 11402 records. 

![image](https://github.com/user-attachments/assets/a7dfb9db-76c0-4593-8ca8-34ff1a32c1a2)















# Executive Summary

This analysis of Vendora performance reveals key areas for growth and improvement. Conversion rates showed ups and downs throughout the year, with some months performing well and others falling short. Social media engagement steadily declined over time, highlighting a need for more engaging content. Customer feedback has been mostly positive, but there are still opportunities to improve satisfaction, especially with products rated below 3.5 stars.

**Conversion Rates**:

- General Conversion Trend - Throughout the year, Vendora’s average conversion rate was 8.5%, with a peak of 18.5% in January and a low of 4.3% in May. Suggesting a strong seasonal demand early in the year, especially for winter-related products, while marketing strategies in slower months need improvement.

- Lowest Conversion Month - In May, the conversion rate dropped to 4.3%, with no standout product performance. This highlights the need for stronger marketing tactics during off-peak periods to maintain steady conversions.

- Highest Conversion Rates - January saw a conversion rate of 18.5%, driven by products like ski boots achieving a 150% conversion rate. Indicating the success of seasonal marketing and suggests focusing more on high-demand products during peak seasons.

 
![Conversion_Rate_Analysis](https://github.com/user-attachments/assets/55284f56-cf86-4262-896a-217ad9d248ea)




**Customer Engagement**:

- Declining Views - Vendora recorded 2,982,369 views across social media, but views steadily dropped after August, signalling declining audience interest. This trend suggests that refreshing marketing content could help sustain engagement.

- Low Interaction Rates - Despite high views, the click-through rate (CTR) was 15.37%, with only 458,345 clicks and 73,618 likes. This gap between views and interactions indicates that more compelling content or stronger calls to action are needed.

- Content Type Performance - Blog content consistently attracted more views, especially in April and July, compared to social media and video content. This suggests blog content is effective, but other content types need improvement to drive similar engagement.

 ![image](https://github.com/user-attachments/assets/eb7cd496-035d-4858-ae28-9d5f85a9daa6)


**Customer Feedback Analysis:**

- Customer Ratings Distribution - The average customer rating was 3.7 out of 5, with most ratings falling in the 4 to 5-star range. However, products rated below 3.5 show room for improvement in quality or service.

- Sentiment Analysis - Out of all reviews, 275 were positive, while 82 were negative. The negative reviews highlight specific product or service issues that need addressing to improve customer satisfaction.

- Opportunities for Improvement - Mixed feedback from 21 mixed positive and 60 mixed negative reviews suggests a need to address common concerns. By resolving these issues, Vendora could potentially increase its overall ratings and customer loyalty.



![image](https://github.com/user-attachments/assets/2c377b81-34ff-4e0d-bc1e-882661a298ce)




# Recommendations

**Boost Conversion Rates**

- Prioritize marketing for products with strong conversion performance, like Kayaks, Ski Boots, and Baseball Gloves. Introduce seasonal promotions or personalized marketing campaigns during high-demand months (such as January and September) to maximize sales.

**Increase Customer Engagement**


- Refresh content strategies by introducing more interactive formats, like user-generated content or engaging videos, to improve interaction rates. Strengthen calls to action on social media and blogs, especially during slower engagement months (September to December), to drive more user activity.

**Enhance Customer Feedback Scores**

- Createa system to analyse mixed and negative reviews to uncover common pain points. Develop targeted solutions to address these issues and follow up with dissatisfied customers to improve their experience. This approach can help raise average product ratings closer to the 4.0 goal.


