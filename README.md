# E-commerce Customer Analysis

A data analysis project using RFM segmentation to identify key customer personas and provide marketing recommendations.



### Project Goal
The goal of this project was to analyze a large e-commerce transaction dataset to understand customer behavior. By implementing RFM (Recency, Frequency, Monetary) analysis, the project segments customers into distinct groups to enable targeted and effective marketing strategies.

### Tech Stack
* **Data Manipulation & Analysis:** Python (Pandas, NumPy, SQLAlchemy)
* **Database:** SQL (SQLite)
* **Data Visualization:** Tableau

### Process
1.  **Data Cleaning:** Loaded multiple CSV files into a SQL database. Used SQL joins to create a master dataset, which was then cleaned and preprocessed using Python.
2.  **RFM Analysis:** Calculated the Recency, Frequency, and Monetary value for each unique customer. These values were then used to create RFM scores.
3.  **Persona Creation:** Grouped RFM segments into actionable, named personas such as "Champions," "At-Risk VIPs," and "Newcomers" using rule-based logic.
4.  **Dashboarding:** Connected the final, segmented dataset to Tableau to build an interactive dashboard showcasing the findings.

### Key Findings
* Identified a key **"Champions"** segment (customers with high R, F, and M scores) that represents the most valuable customer group.
* Uncovered a significant **"At-Risk VIPs"** segment, comprising high-value customers who have not made a purchase in a long time, indicating a key opportunity for re-engagement campaigns.
* The final dashboard provides a clear, filterable view of customer distribution, allowing for strategic decision-making.

### How to View
* **[View the Interactive Dashboard on Tableau Public](https://public.tableau.com/views/RFMDataAnalysis/KPI?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
