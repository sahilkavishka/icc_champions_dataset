# 🏏 ICC Champions Trophy Historical Insights Dashboard

An interactive **Power BI Business Intelligence dashboard** built to explore historical ICC Champions Trophy match data and uncover meaningful insights into team dominance, player performance, rankings, and venue trends.

## 📊 Project Overview

This project transforms historical cricket match data into an interactive analytical dashboard using **Power BI, DAX, and data modeling**.

The dashboard is designed to help users explore historical tournament performance and answer questions such as:

- Which teams have dominated the Champions Trophy?
- Who are the most successful Player of the Match recipients?
- How have team batting rankings changed over time?
- Which cricket grounds have hosted the most matches?
- Which team dominates when two countries are compared head-to-head?

## 🎯 Key Dashboard Features

### 🏆 Overall Dominance Tracker
A dynamic KPI/visual analysis showing the total number of Champions Trophy match wins by country.

### ⚔️ Head-to-Head Dominator
A DAX-driven KPI that dynamically identifies the dominant team when two teams are selected for comparison.

### 📈 Batting Strength Trend
A historical trend analysis of team average batting rankings to visualize changes in batting strength over time.

### ⭐ Most Dominant Players
A filtered leaderboard highlighting players with the highest number of **Player of the Match** awards, with data cleaning applied to anomalies and missing values.

### 🌍 Venue Popularity
A treemap visualizing the most frequently used cricket grounds across the tournament's historical matches.

## 🧹 Data Preparation

The dataset was prepared before visualization and analysis. Key data preparation activities included:

- Handling missing and inconsistent values
- Cleaning Player of the Match records
- Removing/handling data anomalies
- Standardizing relevant fields
- Preparing fields for time-based analysis
- Creating calculated measures using DAX

## 🧮 DAX & Data Modeling

The project uses Power BI's data modeling and DAX capabilities to create dynamic analytical measures.

Examples of analytical logic include:

- Total Wins
- Head-to-Head comparison
- Player of the Match counts
- Ranking-based analysis
- Dynamic filtering and KPI calculations

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard development & visualization |
| **DAX** | Calculated measures and analytical logic |
| **Power Query** | Data cleaning and transformation |
| **Data Modeling** | Structuring data for interactive analysis |
| **CSV** | Source dataset |
| **Jupyter Notebook** | Exploratory data analysis / data preparation |

## 📁 Repository Structure

```text
icc_champions_dataset/
│
├── all_champions_trophy_matches_results.csv
├── all_champions_trophy_players_list.csv
├── icc_champions.ipynb
├── README.md
└── Power BI Dashboard
```

## 📌 Dataset

The repository contains historical ICC Champions Trophy match and player data.

### Match Dataset

The match dataset contains information including:

- Teams
- Toss result
- Match duration
- Winner
- Player of the Match
- Winning margin
- Ground/Venue
- Match date
- ODI status
- Average batting rankings
- Average bowling rankings
- Champions Trophy participation
- Champions Trophy wins
- Head-to-head win/loss ratio

### Player Dataset

The player dataset contains:

- Team
- Year
- Player Name

## 💡 Business / Analytical Value

Although this is a sports analytics project, the workflow demonstrates practical **Business Intelligence skills** applicable to many domains:

**Raw Data → Data Cleaning → Data Modeling → DAX → Interactive Visualization → Insights**

The project demonstrates how structured historical data can be transformed into an interactive decision-support dashboard.

## 📷 Dashboard Preview

Add screenshots of the Power BI dashboard here.

Example:

```markdown
![Dashboard Preview](images/dashboard-preview.png)
```

## 🚀 Key Skills Demonstrated

- Power BI Dashboard Development
- Business Intelligence
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- KPI Development
- Interactive Data Visualization
- Exploratory Data Analysis
- Sports Analytics
- Insight Generation

## 🔗 Project Links

**GitHub Repository:**  
https://github.com/sahilkavishka/icc_champions_dataset

**LinkedIn Project Post:**  
Add your LinkedIn post URL here.

## 👤 Author

**Sahil Kavishka**

Aspiring Data Analyst | Business Intelligence | Data Science | Machine Learning

GitHub:  
https://github.com/sahilkavishka

---

⭐ If you find this project useful or interesting, feel free to explore the repository and give it a star!
