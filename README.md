#  Netflix Data Analysis Dashboard

![Netflix Dashboard Screenshot](Netflix%20Dashboard.png)

##  Project Overview
This project involves analyzing the Netflix dataset to understand content trends, user preferences, and the platform's global expansion. Using **Power BI**, I have transformed raw data into an interactive dashboard that helps identify the distribution of Movies vs. TV Shows, top genres, and content ratings.

##  Problem Statement
The goal was to answer key business questions such as:
- How has content production grown over the years?
- Which countries produce the most content on Netflix?
- What is the ratio between Movies and TV Shows?
- Which ratings (TV-MA, PG-13) are most common?

##  Tools Used
- **Power BI Desktop:** For Data Visualization and Dashboarding.
- **SQL(Structured Query Language) and Power Query:** For Data Cleaning and Transformation (Handling null values, splitting columns).
- **DAX (Data Analysis Expressions):** For creating calculated measures (e.g., Total Titles, Counts by Genre).
- 

##  Key Insights
- **Content Volume:** Analyzed a total of **7,982 titles**, comprising **5,656 Movies** and **2,326 TV Shows**.
- **Global Reach:** The **United States** and **India** are the top contributors to Netflix's library.
- **Content Trend:** There has been a significant exponential growth in content addition starting from **2015**.
- **Movies vs TV Shows:** Movies dominate the platform, accounting for approximately **70%** of the content compared to **30%** for TV Shows.
- **Ratings:** The majority of content is rated **TV-MA** (Mature Audience), followed by TV-14.

##  Steps Followed
1. **Data Extraction:** Imported the dataset (CSV file) into Power BI.
2. **Data Cleaning:**
   - Removed duplicates.
   - Handled missing values in `Director` and `Country` columns.
   - Standardized the `Date` format.
3. **Data Modeling:** Created necessary relationships and calculated measures using DAX.
4. **Dashboard Design:** Designed a user-friendly layout with KPIs, Slicers, and Charts using the Netflix Red & Black theme.

## 🏁 Conclusion
This dashboard provides a comprehensive view of Netflix's content strategy, highlighting its focus on Movies and mature content, with significant growth in international markets like India.
