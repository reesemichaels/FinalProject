# FinalProject
 This project will attempt to create a model to predict the effects of select variables (stadium location, weather, opponent secondary rank)
 on NFL receiver catch rate for the 2023 NFL season.

## Datasets
I will need the following datasets:
- receiver catch data
- weather logs
- stadium location for each game
- opponent secondary ranking

## Implementation
I have limited experience with regression models, so I will need to research which model best fit the data I have selected. My initial impression is that 
a Random Forest model may work best because of the numerical and categorical nature of the selected datasets.

## Outline/Project Flow
1. Acquire 2023 NFL receiving data (includes all positions)
2. For each team, filter for receivers and find the mean catch rate %
3. Generate a dataframe of weekly games (for one month) that houses weather data (conditions, temperature, wind, etc.) for each team
5. Define a classification schema for each column, then take the average for each team to correlate with the team avg. catch rate data
6. Consider other datasets to make the analysis more robust, i.e., stadium location, secondary rank, etc. The end goal is to aggregate all data into one dataframe for model and visualization purposes
7. Train the ML model

## Data Acquisition
- NFL player level data acquired from https://www.pro-football-reference.com/years/2023/receiving.htm
- Game level data acquired from https://github.com/nflverse/nfldata/blob/master/data/games.csv
