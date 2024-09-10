# NBA-Player-Attributes-Analysis

Here’s a structured README content for your **NBA Player Analysis** project, which you can use for your GitHub repository. It follows a clear, organized format that will help showcase your project to potential employers and other professionals in the data analytics field:

---

# 🏀 NBA Player Analysis 📊

This repository contains my **NBA Player Analysis** project, which I completed as part of my personal data analytics portfolio. The project involves analyzing the physical attributes and draft metrics of NBA players from 2009 to 2017 using **Power BI**, **DAX**, and **Excel**. The primary goal is to identify trends that could influence player performance and NBA draft outcomes.

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Data Cleaning & Preparation](#data-cleaning--preparation)
3. [Key Metrics & Visualizations](#key-metrics--visualizations)
4. [Tools & Technologies](#tools--technologies)
5. [Key Insights](#key-insights)
6. [Future Work](#future-work)

---

## 📌 Project Overview
The NBA Player Analysis project focuses on analyzing physical characteristics such as **height**, **weight**, **wingspan**, **agility**, and **vertical jump** of NBA players to determine how these metrics influence their draft position and potential success in the league.

- **Dataset:** Contains 403 NBA players’ physical attributes from the years 2009 to 2017.
- **Goal:** To provide insights into which physical attributes are critical for success in the NBA draft.
- **Dashboard:** The interactive dashboard visualizes player data to help scouts and analysts make data-driven decisions.

---

## 🛠 Data Cleaning & Preparation
### Steps Involved:
1. **Missing Values Handling:**
   - Columns like **Bench**, **Sprint**, and **Agility** had missing values, which were filled using the average values.
   - Formula used: `=IF(ISBLANK(Q2), ROUND(AVERAGE($Q$2:$Q$518), 0), Q2)`
   
2. **Power Query in Power BI:**
   - Null values were filtered out during data loading and transformations were applied to ensure clean, usable data.

3. **Data Transformation:**
   - Columns like height and weight were categorized into ranges using the **SWITCH()** function in DAX.

---

## 📊 Key Metrics & Visualizations
### Key Performance Indicators (KPIs):
- **Total Players Analyzed:** 403 👥
- **Avg Body Fat:** 7.14% 💪
- **Avg Max Reach:** 138.3 inches 🏀
- **Avg Weight:** 214.5 lbs 🏋️‍♂️
- **Avg Sprint Time:** 3.31 seconds 🏃‍♂️
- **Avg Agility Time:** 11.35 seconds ⚡

### Visualizations:
- **Height Range vs Total Players (Clustered Column Chart):** Analyzes the distribution of player heights and their draft outcomes.
- **Sprint by Player (Clustered Bar Graph):** Shows sprint speeds for different players.
- **Body Fat vs Weight (Line Chart):** Correlates body fat percentage with weight across players.
- **Player Count by Weight (Clustered Column Chart):** Displays weight distribution among players.
- **Agility by Player (Clustered Bar Chart):** Highlights agility scores by player.

---

## 🧰 Tools & Technologies
- **Power BI**: Used for building interactive dashboards and generating insights.
- **DAX (Data Analysis Expressions)**: Used for calculating averages, measures, and creating KPIs.
- **Excel**: Utilized for initial data cleaning and handling missing values.
- **SQL**: (Optional, if you ran any queries to handle data before importing to Power BI)

---

## 🔍 Key Insights
1. **Height and Weight Distribution:**
   - Most players fall between **6'5" and 6'8"** in height, while the common weight range is **206-240 lbs**.
   
2. **Sprint and Agility:**
   - Top-performing players in sprint and agility, like **C.J. Leslie** and **Norris Cole**, demonstrate the importance of speed in basketball success.

3. **Vertical Jump Metrics:**
   - Players with higher vertical reach scores tend to perform better in agility and speed, indicating a correlation between jumping ability and overall athleticism.

4. **Body Fat and Weight:**
   - There is a slight correlation between body fat percentage and weight, providing insights into the fitness and conditioning levels of players.

---

## 🚀 Future Work
- **Incorporating Player Performance Metrics:** Adding stats like **points per game**, **rebounds**, and **assists** to build a more comprehensive analysis of player success.
- **Predictive Modeling:** Developing a model to predict draft outcomes based on physical attributes and performance data.
- **Enhanced Visualizations:** Creating more advanced visualizations to highlight trends over time and across different player categories.

---

🔗 Live Dashboard : https://app.powerbi.com/view?r=eyJrIjoiNGFiZDgwMGQtYzBkYS00N2M3LTk0OTUtZGZlMDA2MDJmYTAzIiwidCI6ImY5MmU3YTZmLTJmNmEtNGEzNi1iMzY2LTdkNGNlMjE4M2U5MiJ9
![Screenshot (1061)](https://github.com/user-attachments/assets/12dcb7b7-c2f9-47cb-a66d-3f1815f127f0)
