# Data_Analysis


Data set link:
It contains 3 data set.
https://drive.google.com/drive/folders/15bxTXn4XRYNs4KmHDnRECR1Gj61SMFTd

2.The EDA of the Dataset and the python file.
https://colab.research.google.com/drive/1nP4SFPqGi_hPF9yG7_zJaaOe1Ynj5EyB


# FIFA World Cup Exploratory Data Analysis (EDA)

This project is a comprehensive exploratory data analysis (EDA) on FIFA World Cup data. By analyzing historical match data, team rankings, and tournament attendance, this project aims to uncover patterns, trends, and insights across the history of the FIFA World Cup.

## Project Overview

The project includes:
1. **Data Loading**: Importing multiple datasets to examine the history, performance, and trends in FIFA World Cup events.
2. **Exploratory Data Analysis (EDA)**: A deep dive into historical records and statistics to explore different facets of the World Cup.
3. **Visualization**: Creating interactive and static visualizations to better understand and communicate the findings.

## Installation

To set up the project locally, you'll need:
- **Python 3.2**
-  **Google Colab**
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`



## Data Sources

The project relies on three key datasets:
- **world_cup.xlsx**: Contains details about each World Cup tournament, including year, host country, champion, runner-up, top scorer, attendance, and matches played.
- **matches_1930_2022.csv**: Detailed information about individual matches held from 1930 to 2022.
- **fifa_ranking_2022.csv**: Official FIFA rankings for teams as of October 2022, with ranking data by team and association.

## Exploratory Data Analysis (EDA)

### 1. **Data Preprocessing**
   - **Data Cleaning**: Handling missing values, correcting inconsistencies, and filtering out irrelevant data.
   - **Data Merging**: Integrating datasets where necessary to enhance analysis, such as merging ranking data with match data.
   - **Feature Engineering**: Creating new features, like win ratios or average attendance per team, for more insightful analysis.

### 2. **Exploration of Tournament Trends**
   - **Host Country Analysis**: Visualizing the distribution of World Cup events by host country to observe how hosting has evolved and its geographical distribution.
   - **Champion and Runner-Up Analysis**: Examining the success rates of different countries and visualizing patterns in championships and runner-up placements over the years.
   - **Top Scorer Analysis**: Identifying and analyzing players with the highest goal counts each year to examine patterns in top performance.

### 3. **Attendance Analysis**
   - **Total and Average Attendance**: Calculating and visualizing the total and average match attendance per tournament to observe changes in audience engagement over time.
   - **Attendance Comparison by Host Country**: Analyzing attendance data to see how host countries impact audience size, with visualizations highlighting attendance peaks and trends.

### 4. **Match Performance Analysis**
   - **Goal Analysis**: Exploring goal statistics, such as average goals per match and total goals by team or player, to identify trends in offensive play.
   - **Win/Loss Ratios**: Calculating and comparing the win/loss ratios of different teams across tournaments.
   - **Match Outcome Distribution**: Visualizing the distribution of wins, draws, and losses across different tournaments to understand competition dynamics.

### 5. **FIFA Ranking Analysis**
   - **Top Teams Analysis**: Identifying and visualizing the top-ranking teams globally as of 2022 and how their ranks have changed historically.
   - **Ranking by Association**: Analyzing the distribution of top teams by continental associations (e.g., UEFA, CONMEBOL) to assess regional strengths and shifts in team rankings.
   - **Ranking Stability and Volatility**: Studying changes in team rankings over time to identify stable versus fluctuating teams.

### 6. **Interactive Visualizations**
   - **Plotly Interactive Graphs**: Using `Plotly` to create interactive plots, such as tournament timelines and ranking changes, to make insights accessible and engaging.

## Results

This EDA reveals significant insights into the history and evolution of the FIFA World Cup, including:
- **Historical Success**: Identifying the most successful teams and players over time.
- **Audience Trends**: Understanding how fan engagement, measured through attendance, has varied based on location, year, and other factors.
- **Performance Dynamics**: Assessing how team and player performances have influenced FIFA rankings and shaped tournament outcomes.

## Usage

1. Open the Jupyter Notebook `EDA_FifaWorldcup.ipynb`.
2. Run each cell sequentially to load data, process it, and generate visualizations.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch .
3. Make your changes and commit them.
4. Push your branch and submit a pull request.
