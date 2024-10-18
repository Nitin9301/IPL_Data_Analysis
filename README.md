 IPL 2022 Player Data Analysis Project

This project performs data analysis on a dataset containing IPL (Indian Premier League) player information. The dataset includes details such as player name, base price, type (batter, bowler, all-rounder, etc.), team, cost, and previous squad information. The analysis is conducted using Python libraries like 'pandas', 'matplotlib', and 'seaborn'.

## Project Overview

The goal of this project is to:
- Explore the dataset and understand the various features.
- Perform basic data cleaning and preprocessing.
- Analyze player distribution across teams and types.
- Visualize trends in player costs and team compositions.
- Generate insights to assist with IPL auction strategies and team formation.

## Dataset Description

The dataset includes the following columns:
- **Player**: Name of the player.
- **Base Price**: The base price set for the player.
- **TYPE**: The role of the player (e.g., BOWLER, BATTER, ALL-ROUNDER, WICKETKEEPER).
- **COST IN ₹ (CR.)**: The final cost at which the player was acquired, in crores.
- **Cost IN $ (000)**: The final cost in thousands of dollars.
- **2021 Squad**: The team the player was a part of in the previous season.
- **Team**: The current team that acquired the player in the auction.

## Requirements

- Python 3.x
- Libraries: 
  - pandas
  - matplotlib
  - seaborn
  
You can install the required libraries using:

pip install pandas matplotlib seaborn

## Project Structure

The project includes the following main steps:

1. **Data Loading**: Load the CSV file into a Pandas DataFrame.
2. **Data Exploration**:
   - Display the first few rows of the dataset.
   - Check for null values and data types.
   - Basic statistical analysis of the dataset.
3. **Data Cleaning and Preprocessing**:
   - Handle missing values if any.
   - Convert data types where necessary.
4. **Data Analysis**:
   - Filtering data based on player types and costs.
   - Grouping data to understand team compositions and player distribution.
5. **Data Visualization**:
   - Bar plots, pie charts, scatter plots, and box plots to visualize trends.
6. **Saving Results**: Save the cleaned dataset and generated visualizations.

## How to Run the Project

1. Clone this repository:
   
   git clone https://github.com/Nitin9301/IPL_Data_Analysis.git
   
2. Navigate to the project directory:

   cd ipl-player-analysis
   
3. Ensure all dependencies are installed:
   
   pip install -r requirements.txt
  
4. Run the Jupyter notebook or Python script provided:
   
   jupyter notebook analysis.ipynb
  
  

## Example Visualizations

The project includes various visualizations such as:
- **Bar Plot**: Number of players by team.
- **Pie Chart**: Distribution of player roles.
- **Scatter Plot**: Cost vs. base price of players.
- **Box Plot**: Cost distribution by player type.

## Insights and Findings

- Teams with a higher budget tend to acquire more high-cost players.
- There is a significant variation in player costs across different roles.
- The base price does not always correlate with the final acquisition cost, indicating bidding wars.

## Future Enhancements

- Incorporate additional data, such as player performance metrics.
- Build a machine learning model to predict player costs based on historical data.
- Add interactive visualizations using tools like 'Plotly' or 'Dash'.
