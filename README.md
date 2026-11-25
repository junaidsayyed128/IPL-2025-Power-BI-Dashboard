# IPL 2025 Analysis — Power BI Dashboard

An interactive Power BI report exploring team, batting, and bowling performance across the 2025 Indian Premier League season.

## Project overview

This project analyses IPL 2025 match and player performance using Power BI. The report brings key tournament indicators, team comparisons, and player-level statistics into a single dashboard.

## Dashboard highlights

- **Tournament KPIs:** runs, overs, and innings.
- **Team performance:** team-wise runs and overs comparisons.
- **Batting analysis:** batter performance and statistical breakdowns.
- **Bowling analysis:** bowler performance, wickets, and bowling comparisons.
- **Player comparisons:** tables and visuals to explore individual contributions.

## Tools and skills

- Microsoft Power BI
- Power Query for data preparation
- DAX for measures and KPI calculations
- Data modelling and interactive data visualization

## Dashboard preview

![IPL 2025 Power BI dashboard preview](./ipl-2025-dashboard%20(2).png)

*The report overview shows tournament KPIs, team-wise runs and overs, batting and bowling statistics, and player-level tables.*

## Key dashboard metrics

The figures below are transcribed from the dashboard view:

| Metric | Dashboard value |
|---|---:|
| Total runs | 25,166 |
| Innings | 1,116 |
| Total legal overs (decimal) | 2,677.67 |
| Boundary share — fours | 63.44% |
| Boundary share — sixes | 36.56% |
| Four-wicket haul share | 88.89% |
| Five-wicket haul share | 11.11% |

### Team OVR comparison

The team chart compares overs bowled by team using the corrected legal-balls calculation.

> **Calculation note:** The source `OVR` values use cricket notation (overs.balls), so the updated report converts each value to legal balls (overs × 6 + balls), sums legal balls, and then displays the result as decimal overs or cricket-format overs. The dashboard's total is 2,677.67 decimal overs, equivalent to 2,677 overs and 4 balls.

## Project file

The Power BI report is included in this repository:

**[Download IPL-2025-Analysis.pbix](./IPL-2025-Analysis.pbix)**

GitHub displays a “Binary file not shown” message for the `.pbix` file. Download it and open it in Microsoft Power BI Desktop to interact with the report.

## How to explore

1. Open the [PBIX file](./IPL-2025-Analysis.pbix) menu and choose **Download** (or use the download link above).
2. Open the downloaded file in Microsoft Power BI Desktop.
3. Explore the report's team, batting, bowling, and player-performance visuals.

## Author

**Junaid Sayyed**  
[GitHub](https://github.com/junaidsayyed128) · [LinkedIn](https://www.linkedin.com/in/junaid-sayyed-2b40212b7/)
