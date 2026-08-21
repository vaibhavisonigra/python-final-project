# python-final-project
Free Fire Data Analysis & Visualization
A comprehensive exploratory data analysis (EDA) project on player statistics and in-game performance metrics from Free Fire.

Overview
This project performs data cleaning, exploratory analysis, and visual trends identification on a Free Fire player dataset containing over 400,000 records. Key insights include character usage popularity, rank distributions, and player performance metrics like K/D ratio versus total kills.

Dataset Features
The dataset contains player profile details including:

player_id / username: Unique player identifiers

level / rank: In-game progression and competitive rank (Bronze, Platinum, Diamond, Heroic, etc.)

kills / matches / wins / kd: Combat statistics and win performance

character / weapon: Preferred character selection and primary weapon

region: Player regional servers (India, Brazil, SEA, EU, etc.)

Project Workflow
Data Loading & Inspection: Loaded large-scale .csv data using pandas, inspected dataset schema, and handled missing values.

Exploratory Data Analysis: Analyzed statistical distributions for player levels, kills, and win rates.

Data Visualization: Built visual representations using matplotlib and seaborn:

Character Popularity: Count plots displaying most frequently selected characters (e.g., Alok, Chrono).

Rank Distribution: Categorical breakdowns across competitive tiers.

Performance Metrics: Scatter plots mapping player kills against K/D ratios grouped by rank.

Tools & Libraries
Python 3.x

Pandas: Data manipulation and structure handling

NumPy: Numerical computations

Matplotlib & Seaborn: Data visualization and plot styling

How to Run
Clone this repository:

Bash
git clone https://github.com/your-username/free-fire-data-analysis.git
Open the Jupyter Notebook / VS Code environment:

Bash
jupyter notebook "final project.ipynb"
Run all cells sequentially from top to bottom.
