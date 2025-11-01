# ?? FIFA World Cup Data Analysis

## ?? Project Overview
This project analyzes FIFA World Cup data from **1930 to 2018**, exploring trends in goals scored, teams qualified, matches played, and tournament winners.  
It helps understand how the World Cup has evolved over the decades — from a small 13-team event to a global football festival of 32 teams.

---

## ?? Dataset Details
- **Columns:** Year, Country, Winner, Runners-Up, Third, Fourth, GoalsScored, QualifiedTeams, MatchesPlayed  
- **Years Covered:** 1930 – 2018  
- **Data Source:** Manually collected FIFA World Cup records  
- **File Name:** `fifa_worldcup.csv`

---

## ?? Step 1: Data Cleaning
- Checked for missing and duplicate values  
- Removed any empty rows or inconsistencies  
- Verified numerical columns (Goals, Teams, Matches)

---

## ?? Step 2: Data Exploration
Used Python and Pandas to:
- Display dataset info using `df.info()`  
- View unique winners and total tournaments  
- Analyze numerical data with `df.describe()`

---

## ?? Step 3: Visualizations
Created visual insights using **Matplotlib** and **Seaborn**:

1. ?? **Most Successful FIFA Winners**
   - Bar chart showing Brazil, Germany, and Italy as top champions

2. ? **Goals Scored Over the Years**
   - Line chart showing increasing trend in total goals per tournament

3. ?? **Qualified Teams Over the Years**
   - Line chart showing tournament expansion from 13 to 32 teams

4. **Matches Played Over the Years**
   - Line chart showing growth in total matches from 18 to 64

---

## ?? Step 4: Insights

### ?? Most Successful Teams
- **Brazil** leads with **5 World Cup titles**  
- **Germany** and **Italy** follow with **4 titles each**  
- **Argentina** has **3 titles** and consistent top finishes  

### ? Goals Scored Trends
- Early tournaments: ~70–100 goals  
- Recent tournaments: ~150–170 goals  
- More teams ? more matches ? more goals  

### ?? Qualified Teams Growth
- 1930: 13 teams  
- 1982: 24 teams  
- 1998 onward: 32 teams  

### ?? Matches Played
- Increased from **18 (1930)** to **64 (2018)**  

### ?? Hosting Advantage
- Host countries like **Uruguay (1930)**, **Italy (1934)**, **England (1966)**, and **France (1998)** won while hosting  

---

## ?? Conclusion
The FIFA World Cup has evolved from a small regional tournament into the world’s most celebrated sporting event.  
**Brazil** remains the dominant force, and the increasing number of teams, goals, and matches reflects football’s global growth.

---

## ??? Tools Used
- **Python**  
- **Pandas**  
- **Matplotlib**  
- **Seaborn**  
- **Google Colab**

---

## ????? Author
Project by *Livingston Venkatesan*
