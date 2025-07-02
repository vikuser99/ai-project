# ai-project
1. **How does age influence a player's stats?** age vs pts, reb, ast, net_rating, usg_pct, ts_pct.
3. **Does player height impact how much a player scores per game and total points in their career?** player_height vs pts
4. **How does the number of games played impact a players stats?** gp, pts, reb, ast, net_rating, usg_pct
5. **How does net rating correlate with other performance stats for high-scoring players?** net_rating, ast, reb, usg_pct, ts_pct, pts.
6. **What combination of stats shows a star player?** pts, reb, ast, usg_pct, net_rating, ts_pct, ast_pct
7. **How do undrafted players compare to drafted players in terms of season performance?** draft_number, pts, reb, ast, net_rating, ts_pct, gp
8. Do players from major college programs get drafted higher and are more likely to succeed?
9.**Are European players more skilled then American players based on stats and net rating?** country, pts, ast, ts_pct, net_rating, usg_pct
10. **What factors like age, draft pick, height, or usage percentage are related to higher points per game?** pts age, draft_number, player_height, usg_pct, ts_pct, net_rating
11. **Who is the best shooter in this data set whent taking account the ts %?** player_name vs ts_pct, pts, usg_pct, gp
To Do -
1. Add details -- what columns do we want to use for each question.

# Explanation of each column in the dataset:

player_name: The full name of the basketball player in the NBA.

team_abbreviation: The standard 2-3 letter code representing the NBA team
(e.g., LAL for Los Angeles Lakers, GSW for Golden State Warriors, HOU for Houston Rockets).
                                                                                                           
age: Player's age in years during the referenced season.

player_height: Player's height measurement in centimeters.
                                 
player_weight: Player's weight measurement in kilograms.
                                 
college: The college or university the player attended before entering the NBA. May be blank for international players
who didn't play college basketball in the US.
                                                                                      
country: The player's country of origin or nationality.
                                                                                      
draft_year: The year in which the player was selected in the NBA draft.
                                                                                      
draft_round: The round of the NBA draft in which the player was selected (1 or 2 in the modern NBA).
                                                                                      
draft_number: The overall pick number within the draft (1-60 in the modern NBA).
                                                                                      
gp: Games Played - the total number of games the player participated in during the season.
                                                                                      
pts: Points Per Game - the average number of points scored by the player per game.
                                                                                      
reb: Rebounds Per Game - the average number of rebounds (both offensive and defensive) collected by the player per game.
                                                                                      
ast: Assists Per Game - the average number of assists recorded by the player per game.
                                                                                      
net_rating: Net Rating - the point differential per 100 possessions when the player is on the court (team points scored minus team points allowed).
                                                                                      
oreb_pct: Offensive Rebound Percentage - the estimated percentage of available offensive rebounds the player grabbed while on the floor.
                                                                                      
dreb_pct: Defensive Rebound Percentage - the estimated percentage of available defensive rebounds the player grabbed while on the floor.
                                                                                      
usg_pct: Usage Percentage - the percentage of team plays used by a player while on the floor (through shots, free throws, and turnovers).
                                                                                      
ts_pct: True Shooting Percentage - a measure of shooting efficiency that takes into account field goals, three-point field goals, and free throws.
ast_pct: Assist Percentage - the percentage of teammate field goals a player assisted while on the court.
                                                                                      
season: The NBA season represented by the data, typically shown as a range spanning two calendar years (e.g., "1996-97" for the 1996-1997 season).
