# 🏏 IPL Data Analysis — Task 3  
### Data Science Internship Project (EDA)

This repository contains **Task 3 of my Data Science Internship**, where I performed an Exploratory Data Analysis (EDA) on IPL (Indian Premier League) datasets using Python, Pandas, Matplotlib, and Seaborn.

The goal of this project is to explore match data and ball-by-ball data to extract meaningful insights about teams, players, stadiums, and overall IPL performance trends.

---

## 📁 Dataset Description

This analysis uses **two CSV files**:

1. **matches.csv**  
   Contains match-level information such as:
   - Season (e.g., IPL-2017)
   - Teams (team1, team2)
   - Toss results
   - Match winner
   - Venue
   - Victory margin, etc.

2. **deliveries.csv**  
   Contains ball-by-ball details such as:
   - Batsman & bowler names  
   - Runs scored  
   - Wickets  
   - Extra runs  
   - Dismissal type  

Both files must be uploaded in Google Colab before running the notebook.

---

## 🛠 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 📊 Analysis Performed

### ✔ **1. Most Winning Teams**
Using match results to count which teams have the highest total wins.

### ✔ **2. Toss Decision Analysis**
Understanding the relation between choosing to bat/field and match outcomes.

### ✔ **3. Top Stadiums (Most Matches Hosted)**
Finding the venues where most IPL matches were played.

### ✔ **4. Top Batsmen (Total Runs)**
Using ball-by-ball data to compute total career runs of top IPL batsmen.

### ✔ **5. Top Bowlers (Wickets Taken)**
Count of total wickets taken by bowlers across seasons.

### ✔ **6. Total Runs Scored by Teams**
Aggregated using batting_team column in deliveries.csv.

### ✔ **7. Wins per Season (Stacked Bar Chart)**
- Extracted numeric year from Season (e.g., IPL-2017 → 2017)
- Created a year-wise stacked bar chart of team wins.

---

## 📈 Sample Visualizations

The notebook generates several PNG charts such as:

- `wins_per_year.png`
- `top_batsmen.png`
- `top_bowlers.png`
- `stadiums.png`
- `toss_decisions.png`
- `team_runs.png`

These are saved automatically during notebook execution.

---

## ▶️ How to Run This Project

### **🟢 Option A — Google Colab (Recommended)**

1. Open the notebook  
2. Upload:
   - `matches.csv`
   - `deliveries.csv`
3. Run all cells to generate visualizations.

### **🟡 Option B — Local Environment (Jupyter Notebook)**

Install dependencies:
```bash
pip install pandas matplotlib seaborn
