# 🏏 IPL 2024 Data Analysis with Python

This project provides a comprehensive data analysis of the **Indian Premier League (IPL) 2024** using Python. It explores team performance, match outcomes, score trends, venue impact, and winning strategies, offering deep insights through clean visualizations.

---

## 📁 Dataset
The dataset used is `ipl_complete_data_2024.csv`, containing 74 IPL 2024 matches with the following columns:

- `Match Number`
- `Date & Time`
- `Venue`
- `Team 1`, `Team 1 Score`
- `Team 2`, `Team 2 Score`
- `Winner`
- `Winning Margin`, `Winning Margin Value`, `Winning Margin Type`

---

## 🧰 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `datetime`

---

## 📊 Key Insights & Visualizations

### 🏆 Team Performance & Winning Patterns
- Total wins by each team
- Teams dominating by **runs** or **wickets**

### 🏟️ Venue Analysis
- Match distribution across venues
- Home advantage and performance patterns

### 📈 Highest & Lowest Team Scores
- Score distribution across matches
- Trends in scores over the tournament timeline

### ⚖️ Match Outcomes Based on Strategy
- Wins while **batting first** vs **chasing**
- Team-wise preference and effectiveness

### 📏 Winning Margin Distribution
- Frequency of close finishes vs one-sided wins
- Boxplot comparison of wins by runs vs wickets

---

📂 IPL-2024-Data-Analysis/
│
├── data/
│   ├── ipl_complete_data_2024.csv       # Raw dataset
│
├── notebooks/
│   ├── IPL2024_Datacleaning.ipynb       # Data cleaning & preprocessing
│   └── IPL2024_Analysis.ipynb           # Exploratory data analysis & visualizations
│
├── outputs/
│   └── ipl_cleaned_data.csv             # Cleaned dataset saved after preprocessing
│
├── README.md                            # Project overview and documentation
