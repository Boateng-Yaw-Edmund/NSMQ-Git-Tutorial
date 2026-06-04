# NSMQ-Git-Tutorial
![nsmq](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/nsmq.jpg)

Power BI analysis of Ghana’s National Science & Maths Quiz (2016–2024). Explores school dominance, regional strength, gender representation, and competitiveness with interactive visuals and KPIs.

## Project Objective
To analyze NSMQ data from the 1/8 stage upwards and uncover insights on:
- Which schools and regions dominate the competition
- How gender representation looks across Mixed, Boys, and Girls schools
- The scoring power and competitiveness at different stages
- Regional distribution of advancement and wins

## Main KPIs
- Total Schools Represented (2016–2024): Unique schools that participated.
- Championship Titles: Total wins by schools at the Final stage.
- Average Winning Score: Average points scored by champions in the Finals.
- Average Scores by Year & Gender: Trend comparison across 8 years.
- Stage Advancement by Region: Number of schools per region reaching Quarter, Semi, Final.

## Project Process

1. **Data Cleaning & Prep**
   - Handled nulls with replacement (for example, “No”, “None”, “Others”).
   - Created Stage_Label mapping (1/8 Final, Quarter, Semi, Final) for better visuals.
   - Built measures for advancement, wins, and average scores

2. **Data Modeling**
   - Applied DAX measures (such as Total Wins, Avg_Winning_Points).
   - Structured calculations for school dominance, gender breakdowns, and competitiveness.
  
3. **Visualization Design**
   - Clustered bar charts for Stage Advancement by Region.
   - Line charts for Gender-based scoring trends.
   - KPI Cards for Total Schools, Average Winning Score.
   - Ghana-focused filled map for Regional Wins.
   - Rounded bar hack (error bars) for polished visuals.
  

## Data Visualisation
![dash](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/NSMQ%20analysis.png)

## Dax Measures
![dax1](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/Screenshot%202025-10-02%20123847.png)
![dax2](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/Screenshot%202025-10-02%20123826.png)
![dax3](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/Screenshot%202025-10-02%20123517.png)
![dax4](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/Screenshot%202025-10-02%20123927.png)
![dax5](https://github.com/Boateng-Yaw-Edmund/NSMQ-Dashboard-Analysis/blob/main/NSMQ/Screenshot%202025-10-02%20123906.png)

## Key Insights
- **School Dominance** Certain schools consistently rack up high points, showing scoring power beyond just wins.
- **Regional Strength** Greater Accra and Central dominate wins, but other regions consistently push schools into Quarters and Semis.
- **Gender Representation** Boys’ schools dominate participation, but Girls’ schools are making strong runs into Semis and Finals.
- **Competitiveness** Some contests are nail-bitingly close (margin under 5 points), showing how tight the competition can get.

## Explore the Dashboard
**[Click here to interract with the dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjNhMTZhMGUtNWVmMi00N2Y5LTg0MDUtNzI1YTZmMzkxNjc3IiwidCI6IjEwNGQ4MDQ4LWZkMGMtNDNkNS1hNjMwLWZjNjI5ZTVkYWI1OSJ9)**
