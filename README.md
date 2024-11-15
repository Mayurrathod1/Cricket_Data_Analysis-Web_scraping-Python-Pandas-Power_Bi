# Cricket_T20_Analytics-Project_sportan-:cricket_game:

## Files included;-
1) Cricket T20-Analytics - Power Bi.mp4 --> Sample video of dashboard
2) Cricket T20-Analytics.pdf --> Dashboard sample
3) Cricket T20-Analytics.pbix --> Power bi file
4) t20_csv_files.zip --> includes individual Processed data files inside the zip archive file
5) t20_data_preprocessing.ipynb --> python data processing codes
6) t20_json_files.zip --> includes individual raw data files inside the zip archive file
---

## Parameters set:
1**The team should be able to score at least 180 runs on an average**

2**They should be to defend 150 runs on an average**

===========================
# 1) OPENERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average | Average runs scored in an innings | > 30 |
| Strike Rate | No of runs scored per 100 balls | > 140 |
| Innings Batted | Total Innings batted | > 3 |
| Boundary % | % of runs scored in boundaries | > 50 |
| Batting Position | Order in which the batter played | < 4 |

# 2) ANCHORS/MIDDLE ORDER

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average|  Average runs scored in an innings | > 40 |
| Strike Rate | No of runs scored per 100 balls | > 125 |
| Innings Batted|  Total Innings batted | > 3 |
| Avg. Balls Faced | Average balls faced by the batter in an innings | > 20 |
| Batting Position | Order in which the batter played | > 2 |

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

# 4) SPECIALIST FAST BOWLERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Innings Bowled | Total Innings bowled | > 4 |
| Bowling Economy | Average runs allowed per over | < 7 |
| Bowling Strike Rate | Average no. of balls required to take a wicket | < 16 |
| Bowling Style | Bowling style of the player | = "%Fast%" |
| Bowling Average | No. of runs allowed per wicket | < 20 |
| Dot Ball % | % of dot balls bowled | > 40 |
