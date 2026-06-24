# ✈️ British Airways Reviews Dashboard
An exploratory tableau dashboard analysing over 1200+ customer reviews of British Airways (2016-2023) to uncover service quality trends over time, geography and aircraft type. 


## 🛠 Tech Stack 
The dashboard was built using the following tools and technologies : 
• 📊 Tableau Public - Main data visualization platform used for dashboard creation.
• 📂 CSV Data -  Raw review dataset ‘ba_reviews.csv’ and supporting country mapping ‘countries.csv’.
• 📝 Data Cleaning - Basic preprocessing in Excel before import.
• 🔗 Data Modelling  - Logical data modelling in Tableau using Relationship (Place ↔ Country) to preserve granularity and avoid row duplication.


## 🌟 Features

### • Business Problem
Airlines generate thousands of customer reviews, but raw text and ratings make it difficult to identify trends in satisfaction across aircraft, routes, and regions.
### • Goal of the dashboard
To deliver an interactive visual tool that:
- Enables exploration of customer satisfaction trends over time and geography.  
- Compares performance across aircraft types and service categories.  
- Provides actionable insights for improving customer experience.

### • Walkthrough of Key Visuals
- **KPI Cards (Top Section)** : Average ratings for cabin staff, entertainment, food & beverages, seat comfort, ground service, and value for money.  
- **Ratings by Month (Line Chart)** : Trends in overall satisfaction from 2016–2023. 
- **Ratings by Country (Map)** : Geographic differences in customer experience, with filters for continent.
- **Ratings by Aircraft (Bar Chart)** : Comparison of aircraft types (e.g., Boeing 747‑400 scored 4.7 vs. A321 at 3.6).
- **Filter Panel (Left Side)** : Interactive filters for traveler type, seat type, aircraft group, continent, and time period

### • Insights
- **Customer Experience Analysis** : Identified weak areas (entertainment avg. 1.4, seat comfort < 3.0)
- **Aircraft Performance** : Boeing 747‑400 consistently outperformed other models.  
- **Regional Trends** : Country‑level ratings highlight differences in service perception.  

### • Business Impact
This dashboard demonstrates how customer feedback can be transformed into actionable insights, supporting airline strategy, customer experience teams, and data‑driven decision making. 

## 📷 Dashboard Overview
<img width="1386" height="827" alt="Snapshot of the dashboard" src="https://github.com/user-attachments/assets/262c8baa-b0ea-4308-8253-e6092422ccd8" />


## 🔗 Live Dashboard
[View this dashboard on Tableau Public](https://public.tableau.com/views/BritishAirwaysReviewsDashboard_17822210881140/BritishAirwaysReviews?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

