# Soccer Odds Analysis

This project provides an in-depth analysis of soccer match odds across different leagues and bookmakers.

## Data Columns Explanation:

- **match_id**: Unique identifier for each match.
- **league**: The league in which the match was played.
- **match_date**: The date the match was played.
- **home_team**: Name of the home team.
- **away_team**: Name of the away team.
- **home_score**: Goals scored by the home team.
- **away_score**: Goals scored by the away team.
- **avg_odds_***: Average odds for different outcomes.
- **max_odds_***: Maximum odds found for different outcomes across bookies.
- **top_bookie_***: The bookie offering the maximum odds for different outcomes.
- **n_odds_***: The number of odds gathered for different outcomes.
- **homevsaway**: Concatenation of home and away team names.
- **lcm_value**: Calculated Lowest Common Multiple value for odds.
- **edge**: Calculated edge value based on odds.
- **edgepercent%**: Percentage edge for the match based on odds.
- **year**: The year the match took place.
- **competitiveness**: Calculated competitiveness factor for the match.

## Note:
Columns with asterisk (*) are split into three different outcomes: home win, draw, and away win.
