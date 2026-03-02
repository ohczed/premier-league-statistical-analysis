Markdown

# Premier League Statistical Analysis (Beginner Project)

## Project Goal
The goal of this project is to examine whether the average (mean) number of goals per match
is a good representation of typical Premier League matches.

## Academic Disclaimer
This project is purely academic and uses publicly available match results for statistical analysis only.

## Dataset
- Source: Football-Data.co.uk (Premier League results)
- File used: data/E0.csv
- Key columns:
  - FTHG = Full Time Home Goals
  - FTAG = Full Time Away Goals

## Methods (Math & Analysis)
In the Jupyter notebook:
1. Created total_goals = FTHG + FTAG
2. Calculated the mean total goals per match
3. Calculated empirical probabilities (count / total matches)
4. Measured how many matches are close to the mean (2 or 3 goals)
5. Visualized the distribution of total goals
6. Calculated the standard deviation to describe variability

## Key Results
- Mean total goals per match: 2.85
- Matches with 2 or 3 goals: 44%
- Standard deviation: 1.79

## Files in this Repository
- premier_league_math_project.ipynb — main analysis
- data/E0.csv — dataset used

## How to Run
Open the notebook in Jupyter and run all cells from top to bottom.
