# Premier League Statistical Analysis (Beginner Project)

## Project Goal
The goal of this project is to examine whether the average number of goals per match is a good representation of typical Premier League matches.

This is a beginner-friendly statistics project focused on explaining concepts clearly through football data.

## Academic Disclaimer
This project is purely academic and uses publicly available match results for statistical analysis only.
It does not promote or involve gambling.

## Dataset
- Source: Football-Data.co.uk
- Competition: Premier League
- File used: `data/E0.csv`

## Variables Used
The analysis includes the following variables:
- `FTHG` = Full Time Home Goals
- `FTAG` = Full Time Away Goals
- `FTR` = Full Time Result
- `total_goals` = total goals scored in a match (`FTHG + FTAG`)

## Methods and Analysis
In the Jupyter notebook:
1. Loaded the Premier League dataset
2. Created the variable `total_goals`
3. Calculated the mean, median, variance, and standard deviation of total goals
4. Calculated empirical probabilities using match frequencies
5. Compared home goals and away goals
6. Analyzed match results (`H`, `D`, `A`)
7. Visualized the distributions of:
   - total goals
   - home goals
   - away goals
8. Interpreted the asymmetry of the histograms
9. Discussed limitations and possible future improvements

## Main Findings
- The mean number of total goals per match is approximately **2.85**
- About **44%** of matches have **2 or 3 goals**
- Home teams score more goals on average than away teams
- Home wins occur more often than away wins
- The goal distributions are slightly right-skewed, meaning that very high-scoring matches are rare but still affect the averages

## Repository Files
- `premier_league_math_project.ipynb` — main notebook with analysis, explanations, and visualizations
- `data/E0.csv` — dataset used in the project
- `README.md` — project summary

## How to Run
Open `premier_league_math_project.ipynb` in Jupyter Notebook and run the cells from top to bottom.
