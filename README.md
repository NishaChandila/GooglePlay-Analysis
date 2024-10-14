# **GooglePlay-Analysis**

## **Introduction**

"On Google Play, every app is more than just code—it's a vision turned into reality, solving problems or bringing joy. Its true power lies not in features but in the lives it touches and connections it creates. Success isn’t just about downloads; it’s about making something that truly matters."

This project analyzes a dataset of over **2 million rows** sourced from the **Kaggle Google Play Store dataset**. The objective is to gain insights into user behavior, app performance, and trends by examining key factors such as installs, ratings, pricing, and in-app purchases.

We conducted thorough **data cleaning** to address missing values, standardize formats, and ensure data consistency. Using Power BI, we visualized app distribution, user engagement, and key performance metrics across various app categories.

This analysis aims to provide actionable insights for developers, marketers, and businesses to better understand app trends and user preferences.


- [Power BI Dashboard Link](https://github.com/NishaChandila/OnlineRetail-Customer-Segmentation/blob/main/Customer-Segmentation-Dashboard.pdf)  
- [Data Cleaning & EDA File](https://github.com/NishaChandila/OnlineRetail-Customer-Segmentation/blob/main/OnlineRetail-DC.ipynb)
- [You can access the dataset from these links:](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)

----

## **Data Structure**

The dataset used for this analysis was sourced from Kaggle and contains transactional data from an online retail store. It spans two fiscal years: 2009-2010 and 2010-2011.

### **Dataset Preview:**
![Dataset Preview]()  

### **Data Columns:**
The dataset consists of several columns providing detailed information about Google Play Store apps:

- **App Name:** The name of the app.
•	**Category:** App category (e.g., Games, Productivity).
•	**Content Rating:** Age-appropriate rating (e.g., Everyone, Teen).
•	**Installs:** The number of times the app has been installed, including minimum and maximum values.
•	**Price:** Whether the app is free or paid, with pricing details.
•	**In-App Purchases:** Indicates if the app offers in-app purchases.
•	**Rating:** Average user rating (on a scale from 0 to 5).
•	**Rating Count:** Total number of ratings submitted by users.
•	**Size:** App size, typically in MB or KB.
•	**Minimum Android Version:** The lowest Android version required to run the app.
•	**Developer Information:** Includes developer email, ID, and website.
•	**Release Date:** The app’s initial release date.
•	**Last Updated:** The most recent date the app was updated.

This detailed information allows for comprehensive analysis of app performance and user engagement across the Google Play Store ecosystem.

[You can access the dataset from these links:](https://www.kaggle.com/datasets/sanlian/online-retail-dataset/data)
---

## **Executive Summary**

This report presents an analysis of an online retail dataset collected from 2009 to 2011, containing over 1 million transactions. The dataset includes key details such as customer ID, invoice date, invoice number, product description, quantity, price, and country of transaction. Our primary objective was to segment customers based on their purchasing behavior and analyze churn rates to support business decisions aimed at improving customer retention and revenue growth.

![Power BI Dashboard](https://github.com/NishaChandila/project-assets/blob/main/onlineretail1.PNG)

### **App Information**

Analyzing the Google Play Store dataset, which includes over 2 million entries, reveals essential insights into app characteristics and user engagement.

![App & Performance]() 

Key Findings
**1. Rating Distribution:**
o	51.38% of apps have a "Low" rating, indicating a need for improvement in quality.
o	Only 16.78% achieve an "Excellent" rating, highlighting the opportunity for enhancing user satisfaction.


**2.	Free vs. Paid Apps:**
o	The dataset shows a strong preference for free apps, suggesting that developers should consider offering free versions or trials to attract users.

**3.	Category Insights:**
o	Popular categories include Education, Music and Audio, and Tools. Tailoring offerings to these demands can drive user engagement.

**4.	Release Trends:**
o	A peak in app releases occurs in May, suggesting it is an optimal time for launching new applications.


### **Availability & Updates**

The Availability & Updates section highlights the frequency of app updates and their presence in the market, vital for assessing app ecosystem health.

[Avaibility & Updates]()  


**Key Findings**

**1.	Editor’s Choice Apps:**
o	There are 2,230 apps marked as "Editor’s Choice," signifying high-quality selections that enhance visibility.

**2.	Updates by Developer:**
o	Subsplash Inc. accounts for 35.66% of all updates, indicating active engagement in maintaining app relevance.

**3.	Category-Specific Updates:**
o	Education apps lead with 234.56k updates, followed by Music apps at 152.72k. Frequent updates are essential in fast-evolving categories.

**4.	Annual Growth Trends:**
o	2019 was significant, with 541k new apps launched, reflecting growing demand for innovative applications.

---

## **Data Cleaning and RFM Analysis Summary**

To prepare for customer segmentation analysis, we conducted critical data cleaning and analysis steps:

1. **Missing Values Handling**:
   - **Description**: We addressed 4,382 missing values (0.41%) in the Description column by replacing them with 'Unknown', preserving the context for our analysis.
   - **Customer ID**: For the 243,007 missing CustomerID values (22.76%), we created a new column called CustomerType and labeled these as 'Guest' to represent unregistered transactions.

2. **Outlier Detection**:
   - We identified and removed extreme outliers in the Price and Quantity columns using box plots and the Interquartile Range (IQR) method to ensure that our analysis reflects typical customer behavior without distortion from outliers.

3. **RFM Analysis**:
   - **Recency**: Calculated the number of days since each customer's last purchase.
   - **Frequency**: Counted the total number of purchases made by each customer.
   - **Monetary**: Summed the total amount spent by each customer.
   - **RFM Score**: Combined the scores for recency, frequency, and monetary value to create a composite RFM Score, allowing us to rank customers based on their engagement.
   - **Segmentation**: Categorized customers into segments such as Champions, Loyal Customers, At Risk, Hibernating, and Lost Customers based on their RFM Score, facilitating targeted marketing and engagement strategies.

- [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)

---

## **Recommendations**

1.	**Enhance User Experience:** With 51.38% of apps rated low, focus on user feedback to improve app satisfaction. Regular updates based on reviews can boost ratings.
   
2.	**Capitalize on Free App Popularity:** Since most apps are free, explore monetization strategies like in-app purchases or ads while maintaining user engagement.
	
3.	**Optimize Release Timing:** As many apps are released in May, align launch strategies with this trend to increase visibility and downloads.

4.	**Invest in Education and Music Categories:** Given the high update rates in the education category (234.56K), developers should explore opportunities in these sectors.
	
5.	**Analyze Long-Term Trends:** Learn from successful strategies during peak years, such as 2019 for releases and 2020 for ratings, to guide future development.
	
6.	**Aim for Editor’s Choice Status:** Strive to meet the quality standards of the 2,230 "Editor’s Choice" apps to gain visibility and credibility in the marketplace.


- [Power BI Dashboard Link](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-Dashboard.pdf)  
- [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)
- [You can access the dataset from these links:](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)
