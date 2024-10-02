Dataset Overview
This project utilizes two primary datasets: matches and deliveries, which collectively provide a comprehensive view of the Indian Premier League (IPL). Below is a detailed description of each dataset:
Link:https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020


Matches Dataset
Filename: matches.csv
Description: This dataset contains summary information for each IPL match, including details such as:
match_id: Unique identifier for each match
season: Year of the IPL season
date: Date when the match was played
team1: First team participating in the match
team2: Second team participating in the match
toss_winner: Team that won the toss
toss_decision: Toss decision made by the winning team (bat or bowl)
winner: Team that won the match
player_of_the_match: Player awarded for outstanding performance
venue: Location where the match took place


Deliveries Dataset
Filename: deliveries.csv
Description: This dataset provides detailed ball-by-ball information for each match, allowing for in-depth analysis of match dynamics. Key columns include:
match_id: Unique identifier linking to the corresponding match
inning: Inning number (1 or 2) in which the delivery was bowled
over: Over number in the innings
ball: Delivery number within the over
batsman: Player batting at the time of the delivery
bowler: Player bowling the delivery
runs: Runs scored off the delivery (including extras)
extra_runs: Additional runs (e.g., wides, no-balls)
dismissal: Type of dismissal if applicable (e.g., bowled, caught)
