# Data Analyst Portfolio: Excel & Google Sheets

Welcome to my **Data Analyst Portfolio**, where I showcase my skills in **Excel** and **Google Sheets** through various data analysis projects. Each project demonstrates my expertise in handling real-world datasets, performing detailed analysis, and providing actionable insights.

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
  - [Project 1: Analyzing Game Performance and Monetization Metrics!](#project-1-Analyzing-Game-Performance-and-Monetization-Metrics)
  - [Project 2: Sales Analysis in Excel](#project-2-sales-analysis-in-excel)
  - [Project 3: Financial Budget Tracker in Google Sheets](#project-3-financial-budget-tracker-in-google-sheets)
- [Skills Demonstrated](#skills-demonstrated)
- [Tools Used](#tools-used)
- [How to Access the Files](#how-to-access-the-files)
- [Contact](#contact)

## Projects

### Project 1: Analyzing Game Performance and Monetization Metrics!
   
[View Project](https://docs.google.com/spreadsheets/d/1F9Uwg5q6XEsSFQx10aBxMZngsFyvJbU7XD-G8UP7-DA/edit?usp=sharing)

I cleaned data and calculated KPIs to improve game performance and provide insights for game managers.

Key Metrics:
Total Revenue: For each game.
Paid Users Count: Across all games.
Conversion Rate: Users to paid users.
ARPPU: Average revenue per paying user.
Age Statistics: Average, median, minimum, and maximum ages of paying users.

This project provided insights for improving game monetization and user engagement.

<img width="957" alt="Analyzing Game Performance and Monetization Metrics" src="https://github.com/user-attachments/assets/26736ffd-e1d0-45f1-ae04-c645b372e646">


### Project 2: User Demographics and Device Analysis

[View Project](https://docs.google.com/spreadsheets/d/1LHg_NAnDhJs7B9ctFCGpdEKKXfptMYYg-y1Fdkvz8l8/edit?usp=sharing)

As part of my analysis of user demographics, I focused on the 'active users' dataset. By calculating key statistical measures such as mean, standard deviation, median, interquartile range, and 10th and 90th percentiles for user age, I gained valuable insights into our user base's age distribution. These findings will be instrumental in tailoring our products and marketing strategies to serve our target audience better.

- **Outcome**: Provided insights into user age distribution, language preferences, and device model trends.

<img width="1300" alt="User Demographics and Device Analysis" src="https://github.com/user-attachments/assets/6141e0bc-b5df-4984-97b8-815a98e29591">


### Project 3: Daily and Weekly Active Users Analysis

[View Project](https://docs.google.com/spreadsheets/d/1XgtfhbdW503GjHmgtdPYeKhkjHSXRfmUKU4CgEMyUUA/edit?usp=sharing)

I analyzed user engagement by creating and managing sheets for Daily Active Users (DAU) and Weekly Active Users (WAU), including statistical calculations and data visualizations.

- Activity Month: Created a column to extract the month from each activity_date.
- First Activity Month: Added a column to capture the first month of activity for each user, using the MINIFS function to find the earliest activity_date.
- Activity Month Number: Calculated how many months have passed since the user's first activity month, ensuring all values are 0 or greater.
- **DAU Sheet**: Created a sheet with unique `activity_date` values, calculated DAU using `COUNTUNIQUEIFS`, and added `week_start_date`.
- **WAU Sheet**: Developed a sheet with unique `week_start_date` values,
- **WAU Calculation**: Calculated WAU using the formula `=COUNTUNIQUEIFS(activity!A:A,activity!B:B,">="&A2,activity!B:B,"<"&A2+7)` to ensure accurate weekly user counts., and included columns for Average DAU and User Stickiness (DAU/WAU).
- **WAU Trend Analysis**: Created a chart on the "WAU" sheet with weeks on the horizontal axis and WAU values on the vertical axis. Added a linear trendline to visualize trends in weekly active users over time.

This project provides a comprehensive view of user engagement, including trend analysis to support strategic decision-making.

<img width="1368" alt="Project Daily and Weekly Active Users Analysis" src="https://github.com/user-attachments/assets/744f0020-ae6c-443e-b129-6c74c5858b1f">


### Project 4: Forecasting Daily and Weekly Active Users (WAU/DAU)
[View Project](https://docs.google.com/spreadsheets/d/1LRXWWGK_6Y1-qU6vuvjK7WRTNRVLUpg9p6oHu-mYKIw/edit?usp=sharing)

I forecasted Daily Active Users (DAU) and Weekly Active Users (WAU) for the next 20 weeks using historical data and built trend analysis.
- Extended Week Data: Added 20 new rows for future weeks on the "WAU" sheet.
- Forecasting: Used ROUND and FORECAST functions to predict DAU and WAU values for the new weeks, fixing historical data ranges for accurate forecasting.
- Stickiness Calculation: Filled in the DAU/WAU ratio for the forecasted weeks.
- Visualization: Created a chart showing WAU over time with a linear trendline to highlight user stickiness trends.

This project demonstrates my ability to forecast user metrics and visualize trends for strategic insights.

<img width="1191" alt="Project Forecasting DAU and WAU" src="https://github.com/user-attachments/assets/dae1baab-22d5-4c4b-8ccc-cef756829c53">

### Project 5: Cohort Analysis with Retention Rate Calculation
[View Project](https://docs.google.com/spreadsheets/d/1Z3gW2RgGniv1nwym5bCdX90N9PQBOtYxrChfdxG9KLA/edit?usp=sharing)

I conducted a cohort analysis based on users' first activity month, using pivot tables for unique user counts and retention rates, with slicers for filtering.

- Pivot Table: Displayed first activity month (rows), activity month number (columns), and unique users (values). I added slicers for the game, activity type, and user language.
- Retention Rate Table: Created a dynamic table below the pivot table, calculating retention rates by dividing users in a given month by users in their first month.
- Conditional Formatting: Applied gradient formatting to highlight key values.
- This analysis simplifies tracking user retention over time with flexible filtering and clear visuals.

  <img width="1272" alt="Cohort Analysis with Retention Rate Calculation" src="https://github.com/user-attachments/assets/95eb5908-ad6a-4274-ad39-1e6e4c9bb02e">

  ### Project 6: Functions: XLOOKUP, SPLIT
  [View Project](https://docs.google.com/spreadsheets/d/1UwEmHPn1qVHTHPm8Y45TkmckpetqHCia8FYy4rN3QVY/edit?usp=sharing)

  I split the game activity data and mapped user languages using lookup functions to enhance data organization and analysis.

- Split Game and Activity Names: On the "activity" sheet, I separated the game_activity_name column into two parts: game and activity, using the delimiter ": ". =SPLIT(F2, ":")
- User Language Mapping: Added a new column for user language on the "activity" sheet, and populated it by referencing the "active users" sheet with the XLOOKUP function. =XLOOKUP(A2,'active users'!$A:$A,'active users'!$C:$C)

  This improved data clarity and allowed for a more granular analysis of user activity.

<img width="1297" alt="Project XLOOKUP, SPLIT" src="https://github.com/user-attachments/assets/09551b49-d775-4023-b54c-de88e0909dd9">
