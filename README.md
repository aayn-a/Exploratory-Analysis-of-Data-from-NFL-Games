# Outcome Prediction NFL

This project analyzes NFL game and player data to explore trends, test hypotheses, and build predictive models related to game outcomes and team performance.

## Features

- **Data Cleaning & Exploration:**  
  Initial analysis and cleaning of NFL game data from the last decade.

- **Statistical Analysis:**

  - Correlation analysis between variables (e.g., turnovers, rankings, yards).
  - Hypothesis testing:
    - 1-proportion z-test for home field advantage.
    - Two-sample t-tests for turnovers and passing yards per game.

- **Predictive Modeling:**  
  Logistic regression with backward elimination to predict home team wins based on game stats.

- **Historical Trends:**  
  Analysis of how passing has changed from the 1990s to the 2020s using player-level data.

- **Visualization:**  
  Seaborn and matplotlib plots for distributions, trends, and model insights.

## Data

- `nflcombine.csv`: Game-level data (team stats, outcomes, rankings, etc.) (Pulled from Kaggle)
- `playerstatsYYYY.csv`: Player-level passing stats for various years (e.g., 1990, 2022, etc.) (Pulled from Pro-Football-Reference)

## Usage

1. **Install requirements**

   ```
   pip install pandas numpy matplotlib seaborn scipy statsmodels
   ```

2. **Run the analysis**  
   Open `analysis.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially.

## Notebooks

- `analysis.ipynb`: Main notebook containing all data analysis, visualizations, and statistical tests.

## Example Analyses

- Does home field advantage exist in the NFL?
- Are turnovers different for home vs. away teams?
- Which features best predict a home team win?
- Has passing become more prevalent in the modern NFL?

## License

This project is for educational and research purposes.
