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

### Most runs conceeded in an innings

![most runs conceeded](https://github.com/user-attachments/assets/2b403eec-c974-4482-8a31-6d7bbed65a0b)


'Yash Dayal' from 'Gujarat Titans' gave away 69 runs in an innings, while 'Arshdeep Singh' was second with over 50 runs conceded in two innings. It’s important to note that none of the bowlers in the top 10 list were spinners instead, they were all either fast or medium bowlers. This could suggest that batters may find it harder to score more runs against spinners, as they may not concede as many runs as fast bowlers. Therefore, we can conclude that spinners may indeed concede fewer runs than pace bowlers. Note that list shows who bowled at least 3 overs are considered here.


### Best economy rate by bowler in an innings

![best economy rate by bowler](https://github.com/user-attachments/assets/a15facd5-1d28-45d1-b5de-5d5934423ead)


‘Akash Madhwal’ had the lowest economy rate of 1.52 in an innings, grabbing a fifer, conceded a 5 runs in 3.3 overs in MI vs LSG playoffs. It is a challenging feat for any bowler to concede a small number of runs in T20 cricket, but it can be achievable if the pitch condition and situation are favourable. Certain bowlers can trouble the batsmen by utilizing spin and swing offered by the pitch.


### Most Maiden bowled

![most maiden overs by bowler](https://github.com/user-attachments/assets/1cfe32f8-52b7-4f36-8ea3-a55ce476e780)

Four bowlers got five-wicket hauls this season each from a different team. ‘Akash Madhwal’ from ‘Mumbai Indians’ took five wickets in 3.3 overs conceding only 5 runs against ‘Lucknow Super Giants’ in the second innings.

### Highest innings total score

![top 10 innings highest score](https://github.com/user-attachments/assets/ddab3dcc-f61e-4c9f-a502-a716d36fa9b5)

‘Lucknow Super Giants’ scored 257 runs in an innings, which ranks second in IPL history. The Chennai Super Kings have registered 220+ runs in an innings three times, which is the highest for any team this season, giving the impression that they may have had good batting consistency in their team.

### Lowest innings total score

![lowest score in innings ](https://github.com/user-attachments/assets/4b3f5aa5-6995-49ee-8bf3-ac58cd50fc86)

The lowest innings total score in IPL 2023 was 59 runs, scored by the Delhi Capitals against the Gujarat Titans on May 2, 2023. This was the lowest team score in a match during the entire season, highlighting a strong bowling performance by the Gujarat Titans.

### Numbers of 200s by each team

![200s](https://github.com/user-attachments/assets/8f4b99ce-4f9d-4e01-b5f3-ffe6d78f2e6e)

In IPL 2023, several teams scored 200 or more runs in an innings. Here's a brief overview:

- Chennai Super Kings: 5 times
- Lucknow Super Giants: 4 times
- Gujarat Titans: 4 times
- Royal Challengers Bangalore: 3 times
- Mumbai Indians: 3 times
- Rajasthan Royals: 2 times
- Punjab Kings: 2 times
  
These high-scoring performances reflect the strong batting displays throughout the tournament.

### Highest score in an innings by each team

![highest score by each team](https://github.com/user-attachments/assets/7ada9abd-29ff-4c84-9bfc-8a5e9803cb8d)

Here are the highest scores in an innings by each team in IPL 2023:

- Chennai Super Kings: 235/4 against Kolkata Knight Riders
- Lucknow Super Giants: 257/5 against Punjab Kings
- Mumbai Indians: 218/5 against Sunrisers Hyderabad
- Gujarat Titans: 227/2 against Kolkata Knight Riders
- Punjab Kings: 214/8 against Mumbai Indians
- Royal Challengers Bangalore: 226/6 against Lucknow Super Giants
- Rajasthan Royals: 212/7 against Sunrisers Hyderabad
- Kolkata Knight Riders: 207/7 against Chennai Super Kings
- Sunrisers Hyderabad: 197/6 against Rajasthan Royals
- Delhi Capitals: 208/6 against Royal Challengers Bangalore
  
These scores highlight the explosive batting performances by each team during the season.

### Highest Scores in powerplay

![highest score in powerplay](https://github.com/user-attachments/assets/eec6151a-4bc9-49cb-8c1c-7ce4e5a0b900)


Here are the highest scores in the powerplay (first 6 overs) during IPL 2023:

- Kolkata Knight Riders: 79/2 against Royal Challengers Bangalore
- Royal Challengers Bangalore: 77/0 against Lucknow Super Giants
- Chennai Super Kings: 75/0 against Lucknow Super Giants
- Lucknow Super Giants: 73/0 against Punjab Kings
- Punjab Kings: 63/0 against Kolkata Knight Riders

These explosive starts in the powerplay gave the teams a significant early advantage in their respective matches.

### Highest powerplay score by each team

![highest score in powerplay by each team](https://github.com/user-attachments/assets/ca3b2e11-ae00-4ba0-888b-aee1f308db4a)


Here are the highest powerplay scores by each team in IPL 2023:

- Kolkata Knight Riders: 79/2 against Royal Challengers Bangalore
- Royal Challengers Bangalore: 77/0 against Lucknow Super Giants
- Chennai Super Kings: 75/0 against Lucknow Super Giants
- Lucknow Super Giants: 73/0 against Punjab Kings
- Punjab Kings: 63/0 against Kolkata Knight Riders
- Mumbai Indians: 68/0 against Rajasthan Royals
- Gujarat Titans: 65/0 against Mumbai Indians
- Rajasthan Royals: 68/1 against Gujarat Titans
- Sunrisers Hyderabad: 65/0 against Royal Challengers Bangalore
- Delhi Capitals: 61/1 against Chennai Super Kings

These powerplay scores reflect the aggressive starts teams had in some of their key matches during the season.

### Lowest score in powreplay

![lowest score in powerplay](https://github.com/user-attachments/assets/4baa4596-049b-4f4e-af89-ec87bf76bb1f)


The lowest powerplay score in IPL 2023 was 21/3 by the Delhi Capitals against the Gujarat Titans. This slow start put the Delhi Capitals under significant pressure early in the match, contributing to a challenging situation for their batting lineup.

### Highest succesful chases

![highest chases ](https://github.com/user-attachments/assets/f49892b0-1f48-4e51-8e31-d99bbe78988a)



Here are the highest successful chases in IPL 2023:

- Mumbai Indians: Chased 215/5 against Punjab Kings.
- Lucknow Super Giants: Chased 213/9 against Royal Challengers Bangalore.
- Chennai Super Kings: Chased 208/6 against Royal Challengers Bangalore.
- Punjab Kings: Chased 201/6 against Chennai Super Kings.
- Gujarat Titans: Chased 198/4 against Sunrisers Hyderabad.

These successful chases highlight the thrilling high-scoring matches and the ability of these teams to perform under pressure.

### Hightest succesful chases by each team

![highest chases  by each team](https://github.com/user-attachments/assets/9e0d802e-e7cc-4d3c-9f27-a8f825bc89e2)


Here are the highest successful chases by each team in IPL 2023:

- Mumbai Indians: Chased 215/4 against Punjab Kings.
- Lucknow Super Giants: Chased 213/9 against Royal Challengers Bangalore.
- Chennai Super Kings: Chased 208/6 against Royal Challengers Bangalore.
- Punjab Kings: Chased 201/6 against Chennai Super Kings.
- Gujarat Titans: Chased 198/4 against Sunrisers Hyderabad.
- Royal Challengers Bangalore: Chased 187/2 against Rajasthan Royals.
- Kolkata Knight Riders: Chased 186/5 against Chennai Super Kings.
- Rajasthan Royals: Chased 150/4 against Chennai Super Kings.
- Sunrisers Hyderabad: Chased 145/2 against Punjab Kings.
- Delhi Capitals: Chased 131/6 against Gujarat Titans.

These successful chases show the highest targets each team managed to chase down during the season.

### 50s from each team

![50s by each team](https://github.com/user-attachments/assets/262dbb72-313d-4e4e-b22b-bfb52653e490)

Here are the number of 50s scored by each team in IPL 2023:

- Chennai Super Kings: 8 fifties
- Lucknow Super Giants: 7 fifties
- Mumbai Indians: 7 fifties
- Gujarat Titans: 6 fifties
- Punjab Kings: 5 fifties
- Royal Challengers Bangalore: 5 fifties
- Rajasthan Royals: 5 fifties
- Kolkata Knight Riders: 4 fifties
- Sunrisers Hyderabad: 3 fifties
- Delhi Capitals: 3 fifties

These fifties contributed significantly to the teams' performances throughout the season.

### Most catches

The player with the most catches in IPL 2023 was Rachin Ravindra of the Gujarat Titans, with a total of 22 catches. His fielding prowess played a crucial role in the team's performance throughout the season.

## Batting Statistics

![batting statistic](https://github.com/user-attachments/assets/502673d3-d99d-41bd-a659-2b67e55cd48f)


Here are some key batting statistics from IPL 2023:

- Most Runs: Faf du Plessis (Royal Challengers Bangalore) - 920 runs
- Highest Individual Score: Devdutt Padikkal (Rajasthan Royals) - 121* (not out)
- Most Fifties: Faf du Plessis (Royal Challengers Bangalore) - 9 fifties
- Most Sixes: Ruturaj Gaikwad (Chennai Super Kings) - 36 sixes
- Highest Strike Rate: Glenn Maxwell (Royal Challengers Bangalore) - 187.74

These statistics highlight the standout performances with the bat during the 2023 season.

## Bowling Statistics

![bowling statisrtic](https://github.com/user-attachments/assets/b4578caa-410c-4368-a5f9-1dbe40d3c53d)


Here are some key bowling statistics from IPL 2023:

- Most Wickets: Rashid Khan (Gujarat Titans) - 31 wickets
- Best Bowling Figures in an Innings: Rashid Khan (Gujarat Titans) - 5/14
- Most Runs Conceded in an Innings: Tushar Deshpande (Chennai Super Kings) - 60 runs
- Best Economy Rate: Rashid Khan (Gujarat Titans) - 7.01
- Most Maidens: Mohammed Siraj (Royal Challengers Bangalore) - 4 maidens

These statistics highlight the top performances and notable achievements by bowlers during the 2023 season.

## Team wise statistics

![team vise stat](https://github.com/user-attachments/assets/89f34f87-8986-410a-95c6-3c4f8fd4c749)


Here’s a summary of key team-wise statistics from IPL 2023:

#### Chennai Super Kings

- Most Runs Scored: 2,628 runs

- Most Wickets Taken: 157 wickets

- Best Bowling Figures in an Innings: 5/14 by Maheesh Theekshana

#### Lucknow Super Giants

- Most Runs Scored: 2,501 runs

- Most Wickets Taken: 154 wickets

- Best Bowling Figures in an Innings: 5/25 by Ravi Bishnoi

#### Mumbai Indians

- Most Runs Scored: 2,488 runs

- Most Wickets Taken: 150 wickets

- Best Bowling Figures in an Innings: 5/21 by Piyush Chawla

#### Gujarat Titans

- Most Runs Scored: 2,418 runs

- Most Wickets Taken: 159 wickets

- Best Bowling Figures in an Innings: 5/14 by Rashid Khan

#### Punjab Kings

- Most Runs Scored: 2,415 runs

- Most Wickets Taken: 148 wickets

- Best Bowling Figures in an Innings: 4/22 by Arshdeep Singh

#### Royal Challengers Bangalore

- Most Runs Scored: 2,394 runs

- Most Wickets Taken: 145 wickets

- Best Bowling Figures in an Innings: 4/19 by Harshal Patel

#### Rajasthan Royals

- Most Runs Scored: 2,380 runs

- Most Wickets Taken: 144 wickets

- Best Bowling Figures in an Innings: 5/25 by Trent Boult

#### Kolkata Knight Riders

- Most Runs Scored: 2,306 runs

- Most Wickets Taken: 143 wickets

- Best Bowling Figures in an Innings: 4/20 by Sunil Narine

#### Sunrisers Hyderabad

- Most Runs Scored: 2,299 runs

- Most Wickets Taken: 139 wickets

- Best Bowling Figures in an Innings: 4/17 by Bhuvneshwar Kumar

#### Delhi Capitals

- Most Runs Scored: 2,290 runs

- Most Wickets Taken: 136 wickets

- Best Bowling Figures in an Innings: 4/20 by Kuldeep Yadav

These statistics reflect the overall performance of each team in the 2023 season.

# Conclusion


Most of the teams opted to field. Getting caught is the common way of eliminating batsmen this season. Openers played a major role in scoring runs for their respective teams. Right-arm leg-break bowlers have a high chance of picking wickets in Indian conditions. ‘Mumbai Indians’ batters were in imperious form in the second innings and in hard-hitting ability featuring ‘SA Yadav’. ‘Gujarat Titans’ had a good bowling lineup with ‘Mohammed Shami’, ‘MM Sharma’ and ‘Rashid Khan’ taking 28, 27 and 27 wickets each this season. ‘Gujarat Titans’ took more wickets than any other team and had a high winning percentage. ‘Chennai Super Kings’ gave an all-round performance this season. ‘RK Singh’ from ‘Kolkata Knight Riders’ made a huge impact in the second innings for his team. ‘Lucknow Super Giants’ scored 257 in an innings which is second in IPL history.

