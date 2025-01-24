# **GooglePlay-Analysis**

## **Introduction**

> "On Google Play, every app is more than just code—it's a vision turned into reality, solving problems or bringing joy. Its true power lies not in features but in the lives it touches and connections it creates. Success isn’t just about downloads; it’s about making something that truly matters."

This project analyzes a dataset of over **2 million rows** sourced from the **Kaggle Google Play Store dataset**. The objective is to gain insights into user behavior, app performance, and trends by examining key factors such as installs, ratings, pricing, and in-app purchases.

We conducted thorough **data cleaning** to address missing values, standardize formats, and ensure data consistency. Using Power BI, we visualized app distribution, user engagement, and key performance metrics across various app categories.

This analysis aims to provide actionable insights for developers, marketers, and businesses to better understand app trends and user preferences.

- GooglePlay [Power BI Dashboard](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-dashboard.pdf)  
- GooglePlay [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)
- GooglePlay [Dataset](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)

----

## **Data Structure**

The Google Play dataset, sourced from Kaggle, contains over 2 million rows of data, offering a comprehensive overview of app performance, user engagement, and developer activity. This dataset includes a variety of key attributes such as app categories, ratings, installs, and update histories, providing valuable insights into the mobile app ecosystem.

### **Dataset Preview:**
![Dataset Preview](https://github.com/NishaChandila/project-assets/blob/main/data.PNG?raw=true)  

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

- GooglePlay [Power BI Dashboard](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-dashboard.pdf)  
- GooglePlay [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)
- GooglePlay [Dataset](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)
---

## **Executive Summary**

This project analyzes a comprehensive dataset from the Google Play Store, encompassing over 2 million rows and 24 columns of app-related data. Our primary objectives are to gain insights into app performance, availability, and update trends. By examining key metrics such as ratings, installs, and category distributions, we aim to identify patterns that can guide app developers and stakeholders in making informed decisions. Through meticulous data cleaning and visualization, this analysis sheds light on the current landscape of mobile applications, highlighting opportunities for innovation and growth in the marketplace.

![Power BI Dashboard](https://github.com/NishaChandila/project-assets/blob/main/googleplay1.PNG)

### **App Information**

Analyzing the Google Play Store dataset, which includes over 2 million entries, reveals essential insights into app characteristics and user engagement.

![App & Performance](https://github.com/NishaChandila/project-assets/blob/main/googleplay2.PNG?raw=true) 

Key Findings

**1. Rating Distribution:**

- 51.38% of apps have a "Low" rating, indicating a need for improvement in quality.

- Only 16.78% achieve an "Excellent" rating, highlighting the opportunity for enhancing user satisfaction.


**2.	Free vs. Paid Apps:**

- The dataset shows a strong preference for free apps, suggesting that developers should consider offering free versions or trials to attract users.

**3.	Category Insights:**

- Popular categories include Education, Music and Audio, and Tools. Tailoring offerings to these demands can drive user engagement.

**4.	Release Trends:**
 
- A peak in app releases occurs in May, suggesting it is an optimal time for launching new applications.


### **Availability & Updates**

The Availability & Updates section highlights the frequency of app updates and their presence in the market, vital for assessing app ecosystem health.

![Avaibility & Updates](https://github.com/NishaChandila/project-assets/blob/main/googleplay3.PNG)  


**Key Findings**

**1.	Editor’s Choice Apps:**

- There are 2,230K apps marked as "Editor’s Choice," signifying high-quality selections that enhance visibility.

**2.	Updates by Developer:**

- Subsplash Inc. accounts for 35.66% of all updates, indicating active engagement in maintaining app relevance.

**3.	Category-Specific Updates:**

- Education apps lead with 234.56k updates, followed by Music apps at 152.72k. Frequent updates are essential in fast-evolving categories.

**4.	Annual Growth Trends:**

- 2019 was significant, with 541k new apps launched, reflecting growing demand for innovative applications.


- GooglePlay [Power BI Dashboard](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-dashboard.pdf)
  
---

## **Data Cleaning and RFM Analysis Summary**

**Data Cleaning Process**

To ensure the accuracy and reliability of our analysis, a thorough data cleaning process was conducted on the Google Play Store dataset. Here are the key steps involved:

1. **Handling Missing Values:**

- Rows with critical missing information, such as app names or category identifiers, were removed.For fields like ratings and reviews, entries were set to NaN when not applicable, allowing for better handling during analysis.
  
**2. Data Type Conversion:**

- Columns such as Release Date, Rating, and Size were converted to appropriate data types (e.g., datetime for release dates, numeric for ratings) to facilitate accurate calculations and visualizations.
  
**3. Standardization:**

- Text fields, such as Category and Content Rating, were standardized to ensure consistency and eliminate variations in naming conventions.
  
**4. Outlier Detection:**

- Potential outliers in numerical fields, such as Installs and Size, were identified and evaluated for removal, ensuring that extreme values did not skew the analysis.

**5. Categorization:**

- Apps were categorized based on defined criteria (e.g., price ranges, size ranges) to enable clearer comparisons and visualizations.


- GooglePlay [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)

---

## **Recommendations**

1.	**Enhance User Experience:** With 51.38% of apps rated low, focus on user feedback to improve app satisfaction. Regular updates based on reviews can boost ratings.
   
2.	**Capitalize on Free App Popularity:** Since most apps are free, explore monetization strategies like in-app purchases or ads while maintaining user engagement.
	
3.	**Optimize Release Timing:** As many apps are released in May, align launch strategies with this trend to increase visibility and downloads.

4.	**Invest in Education and Music Categories:** Given the high update rates in the education category (234.56K), developers should explore opportunities in these sectors.
	
5.	**Analyze Long-Term Trends:** Learn from successful strategies during peak years, such as 2019 for releases and 2020 for ratings, to guide future development.
	
6.	**Aim for Editor’s Choice Status:** Strive to meet the quality standards of the 2,230 "Editor’s Choice" apps to gain visibility and credibility in the marketplace.

- GooglePlay [Power BI Dashboard](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-dashboard.pdf)  
- GooglePlay [Data Cleaning & EDA File](https://github.com/NishaChandila/GooglePlay-Analysis/blob/main/GooglePlay-DC.ipynb)
- GooglePlay [Dataste](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps)
