# IPL Data Analysis Using Python

## Project Overview
This project explores Indian Premier League (IPL) cricket data using Python to identify match trends, team performance, batting statistics, bowling performance, and toss-related patterns.

## Objectives
- Analyze IPL matches across seasons.
- Identify teams with the most match wins.
- Find the leading run scorers and wicket takers.
- Explore toss decisions and the relationship between toss outcomes and match results.
- Present findings using data visualizations.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The project uses two CSV files:
- `matches.csv`: Match-level information, including teams, seasons, toss decisions, and results.
- `deliveries.csv`: Ball-by-ball information, including batters, bowlers, runs, and dismissals.

## Project Structure
- `data/`: Input datasets
- `notebooks/`: Data analysis notebook
- `results/`: Exported charts and analysis outputs
- `requirements.txt`: Python dependencies

## Key Findings

Analysis of the IPL dataset produced the following findings:

- **Dataset size:** Analyzed 1,095 match records and 260,920 ball-by-ball delivery records.
- **Team performance:** Mumbai Indians recorded the most wins in this dataset, with 144, followed by Chennai Super Kings with 138.
- **Batting performance:** V Kohli topped the recorded run-scoring list with 8,014 runs, followed by S Dhawan with 6,769.
- **Toss decisions:** Teams chose to field 704 times and bat 391 times, showing a preference for fielding after winning the toss in this dataset.
- **Player awards:** AB de Villiers received the most Player of the Match awards in the dataset, with 25.

### Visualizations

The project includes charts for:
- Number of matches by season
- Team wins
- Top run scorers
- Top wicket takers
- Toss decisions

### Limitations

The findings depend on the dataset's coverage, column definitions, and data quality. They describe the records analyzed and should not automatically be interpreted as current all-time IPL statistics.

## How to Run
1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Open `notebooks/ipl_analysis.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells in order.

## What I Learned
- Loading and exploring real-world CSV datasets.
- Using Pandas for grouping, aggregation, and statistical analysis.
- Creating visualizations to communicate findings.
- Interpreting cricket statistics and distinguishing correlation from causation.
