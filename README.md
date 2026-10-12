# Life After Klopp: Analysing Liverpool FC's Transformation (2023/24 vs 2024/25)

Jürgen Klopp left Liverpool after nine years at the end of 2023/24. Arne Slot took over and won the Premier League title in his first season. This project compares the two seasons to find out what actually changed on the pitch.

## Question

How different were Liverpool's two seasons in points, goals, and home and away results?

## Data

Match results for both Premier League seasons from [football-data.co.uk](https://www.football-data.co.uk/), saved in the `data` folder as `2023_24.csv` and `2024_25.csv`.

## Method

1. Loaded both seasons into pandas and kept the match columns needed: date, teams, full time goals, and full time result.
2. Filtered each season to Liverpool's matches.
3. Built goals for, goals against, result, points, venue, and cumulative points columns from Liverpool's point of view, so both seasons share one format.
4. Compared the seasons with matplotlib and seaborn charts.

## Analysis sections

1. **Points and form trajectory:** cumulative points by matchweek for both seasons.
2. **Goals scored and conceded:** average goals per game, with totals.
3. **Home vs away performance:** win percentage and points per game by venue.
4. **Win, draw, and loss distribution:** how consistent results were across each season.

## Key findings

- **Attack and defence barely changed.** Goals scored and conceded per game were almost identical across the two seasons.
- **Away form made the difference.** Liverpool's away win rate rose from 47% to 58%.
- **The title races built up differently.** The cumulative points chart shows how each season developed week by week.

![Cumulative points](images/points_trajectory.png)
![Home vs away](images/home_away.png)

## Tools

Python, pandas, matplotlib, seaborn, Jupyter Notebook

## How to run

1. Clone the repo.
2. Install the libraries:

```
pip install -r requirements.txt
```

3. Open the notebook in Jupyter or VS Code and run all cells. The charts are saved as PNG files.

## Limitations

This compares two seasons only, so small differences could be down to chance. Match results do not capture chance quality or individual player performance.

## Author

Junior Mukiza
[Portfolio link]
