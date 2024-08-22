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

![most runs](https://github.com/user-attachments/assets/1597956b-2e28-489b-b6fe-8e3b8704e810)


Based on the graph, it can be observed that in IPL23, all the batsmen, except for ‘SA Yadav’ and ‘RK Singh’, were openers for their respective teams. This implies that 8 out of the top 10 scorers in IPL23 were openers. The reason for this could be that openers face more balls, increasing their chances of scoring more runs. Additionally, two players from each of the following teams reached the top 10 scorers list: Mumbai Indians, Chennai Super Kings, and Royal Challengers Bangalore. In addition, four of the ten batsmen were left-handed.


### Centuries in IPL 2023

![100s in IPL ](https://github.com/user-attachments/assets/5b660b25-7621-49f8-ae7c-4d445da6929d)


Regarding the graph above, IPL23 had a total of 12 centuries recorded. Shubman Gill achieved this feat three times, while V Kohli accomplished it twice during the tournament. The graph also shows that only two players managed to score 120+ runs. This could be due to a player getting dismissed after scoring a century or not having enough balls left to add more to their score.


### Most 50s

![50S in IPL ](https://github.com/user-attachments/assets/53ead41d-e39e-4c8d-97a7-15289722535f)


In IPL23, three players from the ‘Royal Challengers Bangalore’ team were among the list of top 10 players who scored more than 50 runs. This suggests that the team had a vigorous batting lineup. Furthermore, it's noteworthy that nine of the 10 players who made the list were openers for their respective teams.

### Most 4s

![4s ](https://github.com/user-attachments/assets/d13e63f5-993e-43fd-80cb-1b3f8cfced1f)


9 out of 10 players in the top list of fours were openers to their respective teams.

### Most 6s

![6s ](https://github.com/user-attachments/assets/65b19794-4734-4b56-8411-5f5c44f26a40)


Four out of ten players on this list were openers. The remaining players were hard-hitters for their respective teams in IPL23. If a player hits more sixes, we can infer that the player had hard-hitting skill and may have a higher strike rate in the game. Hard-hitters are very helpful for the squad.


### Best batting average

![best avg](https://github.com/user-attachments/assets/72c9f6b0-619f-45f1-ba8e-01730da6f357)


‘Vivrant Sharma’ from ‘Sunrisers Hyderabad’ played only match in this season in which he scored 69 runs leading to an average of 69. That’s the reason he had topped the batting average list. Two players each from ‘Gujarat Titans’ and ‘Royal Challengers Bangalore’ topped the list which tells that these teams had certain batters with good batting consistency. Average depends on the number of times a batsmen was out and the number of runs scored.

### Best Average Striker Rate

A limit is kept to the balls faced because there might be a chance that a lower-order batsman can score a boundary from one ball which leads to a spike in strike rate. So, a threshold value is necessary to find out who had the best batting average strike rate in IPL23. I considered the threshold value as 100 here.

![highest strike rate ](https://github.com/user-attachments/assets/e85efdab-e774-4e91-a0aa-adc73fa48f6b)


From the above graph, most of the players maintained a strike rate of around 150–160. Only one player, ‘H Klassen’ from ‘Sunrisers Hyderabad’ had the strike rate above 180 in IPL23. There is a difference of approximately 20 in strike rate with the second player on the list, which suggests that he had a good skill to send the ball to the boundary. Strike rate also depends on the number of balls faced. Players who can score more runs with facing less number of balls will help to put more runs on scoreboard.

### Most ducks
It can help players to improve their batting skills and can know where a player is lacking.

![most ducks](https://github.com/user-attachments/assets/4db660f2-86e4-4d78-b8c7-1e37b50bd2e2)


From the above graph, ‘JC Buttler’ from ‘Rajasthan Royals’ was out without scoring a run five times with ‘KD Karthik’ second. Although, ‘JC Buttler’ was the highest run scorer in IPL22. He even led his team to IPL22 finals.

### Most wickets taken

![highest wicket ](https://github.com/user-attachments/assets/1da59f3a-671b-4983-bd8e-82dceb3076bc)


The highest-ranking players on the list were from 'Gujarat Titans' team, indicating that they had a stronger bowling lineup compared to other teams. Further down the list, three players from the 'Chennai Super Kings' team also made the cut, suggesting that they too had a good bowling unit. Out of the ten players, five were spinners, with four of them being right-arm leg break bowlers. Based on this data, it can be inferred that right-arm leg break bowlers have a higher chance of taking more wickets under Indian conditions.


