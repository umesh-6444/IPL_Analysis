 # IPL Analysis Project 🏏📊

## Project Overview
This project performs **end-to-end data analysis on IPL (Indian Premier League) data**
using **Python, SQL, and data visualization libraries**.

The objective is to extract **meaningful insights from match-level, player-level, and ball-by-ball data**
and present them through analytical dashboards.

---

## Datasets Used
The project uses the following datasets:

- `matches.csv` – Match-level details (season, teams, venue, winner, etc.)
- `deliveries.csv` – Ball-by-ball data (runs, wickets, overs, balls)
- `players.csv` – Player-level information
- `ipl_schema.sql` – Database schema for MySQL

---

## Tech Stack
- **Python**
- **Pandas**
- **NumPy**
- **MySQL**
- **SQLAlchemy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## ETL Workflow
1. Raw CSV files loaded using Pandas  
2. Data cleaning & preprocessing  
   - Removing duplicates  
   - Handling null values  
   - Standardizing columns  
3. Data loaded into **MySQL database**  
4. SQL queries used for analytics  
5. Visualizations created using Matplotlib & Seaborn  

---

## Dashboards & Analysis

### Dashboard 1: Team Performance
- Total runs scored by each team  
- Total wickets taken by each team  
- Team-wise performance comparison  

### Dashboard 2: Match Insights
- Average runs per match  
- Matches with **No Result**  
- Home vs Away performance  

### Dashboard 3: Player & Ball Analytics
- Runs distribution per match  
- Wickets per match  
- High-scoring matches analysis  

### Dashboard 4: Business KPIs
- Top teams by win percentage  
- Match outcome predictability  
- Impact of venue on results  

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/umesh-6444/IPL_Analysis.git

