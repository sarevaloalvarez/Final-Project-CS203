# Final-Project-CS203

My project sorts NFL teams according to guidelines set set for the NFL standings found here, https://en.wikipedia.org/wiki/NFL_playoffs#Breaking_ties. In short Teams are sorted according to their win Percentage(games won divided by total games played), if two teams have an equal win percentage, then the teams get sorted according to
1) winner of head-to-head games
2) best record within respective divisions
3) best record between common opponents
4) best record within respective conferences
5) Strength of Victory (win/loss record of teams defeated)
6) Strength of Schedule (win/loss record of all teams played)

these steps are followed until a tie is broken. The NFL_Schedule.csv file comes from here,https://www.pro-football-reference.com/years/2020/games.htm and is modifyed slightly. The nflTeams.txt file is also derived from NFL_Schedule.csv 
