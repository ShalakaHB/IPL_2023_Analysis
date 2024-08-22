# IPL_2023_Analysis
 IPL 2023 Performance and Insights Analysis

![blogs-2023-img1](https://github.com/user-attachments/assets/0ae1d3c9-abc9-4cb2-95ab-6e39067c5578)

 
## Objective:
The primary goal of this project is to analyze the Indian Premier League (IPL) 2023 season data to uncover key insights, trends, and performance metrics. The analysis will focus on identifying patterns in player performances, team strategies, and match outcomes. The findings will be used to provide actionable insights that can be valuable for teams, analysts, and fans.
## Scope:
This project will involve analyzing two main datasets:
deliveries.csv: Contains ball-by-ball details of the IPL 2023 matches.
matches.csv: Contains details about each match, including the teams, scores, and outcomes.
## Dataset Description: 
### deliveries.csv : 
This dataset contains detailed information on every ball bowled during the IPL 2023 season. Each row represents a single delivery, capturing various aspects of the play, including the batsman, bowler, runs scored, and any wickets that fell.
#### Columns:
- match_id: Unique identifier for each match.
- season: The IPL season (2023).
- start_date: The date when the match started.
- venue: The venue where the match was played.
- innings: Inning number (1 for the first inning, 2 for the second inning).
- ball: Ball number within the over.
- batting_team: Name of the team batting during that delivery.
- bowling_team: Name of the team bowling during that delivery.
- striker: Name of the batsman facing the ball.
- non_striker: Name of the batsman at the non-striker end.
- bowler: Name of the bowler delivering the ball.
- runs_off_bat: Number of runs scored off the bat.
- extras: Total number of extra runs conceded on that delivery (sum of wides, no-balls, byes, and leg-byes).
- wides: Number of runs scored due to a wide delivery.
- noballs: Number of runs scored due to a no-ball.
- byes: Number of runs scored as byes (extras not attributed to the bowler).
- legbyes: Number of runs scored as leg byes.
- penalty: Number of penalty runs awarded (usually for unfair play).
- wicket_type: Type of dismissal (e.g., bowled, caught, run out).
- player_dismissed: Name of the player dismissed on that delivery, if any.
- other_wicket_type: Type of additional dismissal (if any).
- other_player_dismissed: Name of the additional player dismissed, if any.

Note: Some columns like penalty, other_wicket_type, and other_player_dismissed have a significant number of missing values, indicating that these events are rare.

### matches.csv :
This dataset provides an overview of each match played during the IPL 2023 season. It includes information about the teams involved, the match venue, the toss, the result, and the umpires.
#### Columns:
- season: The IPL season (2023).
- team1: Name of the first team.
- team2: Name of the second team.
- date: The date on which the match was played.
- match_number: Match number in the sequence of the tournament.
- venue: The venue where the match was played.
- city: The city where the match was played.
- toss_winner: Name of the team that won the toss.
- toss_decision: Decision made by the toss-winning team (either "bat" or "field").
- player_of_match: Name of the player who was awarded "Player of the Match".
- umpire1: Name of the first on-field umpire.
- umpire2: Name of the second on-field umpire.
- reserve_umpire: Name of the reserve umpire (usually third umpire).
- match_referee: Name of the match referee.
- winner: Name of the team that won the match.
- winner_runs: Number of runs by which the winning team won, if applicable.
- winner_wickets: Number of wickets by which the winning team won, if applicable.
- match_type: Type of match (e.g., Group stage, Playoff).

## Key Areas of Analysis:
### Most runs

![WhatsApp Image 2024-08-22 at 3 44 12 PM](https://github.com/user-attachments/assets/68f5e869-8c43-43dd-a6d9-5a80d2ae1f2c)

Based on the graph, it can be observed that in IPL23, all the batsmen, except for ‘SA Yadav’ and ‘RK Singh’, were openers for their respective teams. This implies that 8 out of the top 10 scorers in IPL23 were openers. The reason for this could be that openers face more balls, increasing their chances of scoring more runs. Additionally, two players from each of the following teams reached the top 10 scorers list: Mumbai Indians, Chennai Super Kings, and Royal Challengers Bangalore. In addition, four of the ten batsmen were left-handed.


### Centuries in IPL 2023

![WhatsApp Image 2024-08-22 at 3 44 12 PM](https://github.com/user-attachments/assets/fd2677b1-3179-4b79-a2fc-8dae71702771)


Regarding the graph above, IPL23 had a total of 12 centuries recorded. Shubman Gill achieved this feat three times, while V Kohli accomplished it twice during the tournament. The graph also shows that only two players managed to score 120+ runs. This could be due to a player getting dismissed after scoring a century or not having enough balls left to add more to their score.


### Most 50s

![WhatsApp Image 2024-08-22 at 3 44 12 PM](https://github.com/user-attachments/assets/73c93ae0-4e03-4051-8fcc-3a00df4f30de)


In IPL23, three players from the ‘Royal Challengers Bangalore’ team were among the list of top 10 players who scored more than 50 runs. This suggests that the team had a vigorous batting lineup. Furthermore, it's noteworthy that nine of the 10 players who made the list were openers for their respective teams.
