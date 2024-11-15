# Cricket_Data_Analysis-Web_scraping-Python-Pandas-Power_Bi:

![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

---

This project utilizes cricket data analysis to evaluate player performances and select the best XI players in the world. The process involves collecting data from ESPN Cricinfo, cleaning, transforming, and modeling the data using Python, Power Query, and DAX, and finally visualizing insights through a dashboard built in Power BI.

---

## Methodology
1. **Data Collection** 📊: Data is collected from ESPN Cricinfo website with python web scraping technique and brightdata website toot.
2. **Data Cleaning and Transformation** 🧹: Python and Pandas are used to clean and transform the collected data.
3. **Data Modeling** 🛠️: Power Query is utilized for further data transformation and shaping.
4. **Parameterization** 📝: Data Analysis Expressions (DAX) is employed for data modeling and building parameters.
5. **Dashboard Creation** 📊: A dashboard is built in Power BI to visualize various metrics and insights derived from the data.
6. **Player Selection** 🏏: Insights gathered from the dashboard are used to select the final XI players based on their performances.

---

## Parameters set:
**1. The team should be able to score at least 180 runs on an average**

**2. They should be to defend 150 runs on an average**

---

# 1) OPENERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average | Average runs scored in an innings | > 30 |
| Strike Rate | No of runs scored per 100 balls | > 140 |
| Innings Batted | Total Innings batted | > 3 |
| Boundary % | % of runs scored in boundaries | > 50 |
| Batting Position | Order in which the batter played | < 4 |

---

# 2) ANCHORS/MIDDLE ORDER

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average|  Average runs scored in an innings | > 40 |
| Strike Rate | No of runs scored per 100 balls | > 125 |
| Innings Batted|  Total Innings batted | > 3 |
| Avg. Balls Faced | Average balls faced by the batter in an innings | > 20 |
| Batting Position | Order in which the batter played | > 2 |

---

# 3) ALL-ROUNDERS/LOWER ORDER

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
|Batting Average | Average runs scored in an innings | > 15|
|Strike Rate | No of runs scored per 100 balls | > 140 |
|Innings Batted | Total Innings batted | > 2|
|Batting Position | Order in which the batter played | > 4 |
|Innings Bowled | Total Innings bowled | > 2 |
|Bowling Economy | Average runs allowed per over | < 7 |
|Bowling Strike Rate | Average no. of balls required to take a wicket | < 20 |

---

# 4) SPECIALIST FAST BOWLERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Innings Bowled | Total Innings bowled | > 4 |
| Bowling Economy | Average runs allowed per over | < 7 |
| Bowling Strike Rate | Average no. of balls required to take a wicket | < 16 |
| Bowling Style | Bowling style of the player | = "%Fast%" |
| Bowling Average | No. of runs allowed per wicket | < 20 |
| Dot Ball % | % of dot balls bowled | > 40 |

---

## Repository Structure
- **`csv and json`**: Contains the collected and transformed datasets.
- **`ipynb`**: Includes Python scripts for data collection, cleaning, and transformation.
- **`xlsx`**: Includes DAX scripts for data modeling and parameterization.
- **`pbix`**: Contains the Power BI dashboard file.

---

## Usage
- To interact with the dashboard, simply download the PBIX file available in the repository and open it using Power BI Desktop on your local machine. This will enable you to explore and interact with the dashboard, allowing for a seamless analysis of the cricket data.

---
