# A New Metric to Evaluate Defensive Tackles in NFL
This repository project adapts from a Kaggle competition (NFL Big Data Bowl 2024). “American football is a complex sport, but once an offensive player receives a handoff or catches a pass, all 11 defenders focus on one task -- tackle that ball carrier as soon as possible” [1]. This year’s competition focuses on creating a practical and novel metric to evaluate tackling performance of game plays. \\

The novel evaluation metric I created is called “pivotal factor” and is constructed based on a variety of detailed play statistics, such as game clock, position of the football, and play results etc. The metric reflects the importance of each tackling play and its contribution to the entire game. “Pivotal factor” could be a metric that football fans are most interested and has the potential to holistically evaluate defensive players in terms of their tackling contribution to the team. Details can be found in **project.pdf**.

## Data
This year’s competition is mainly built upon the NFL Next Gen Stat data for Week 1-9 of the 2022 NFL season. Each week’s dataset (a csv. file) consists of frame-by-frame tracking data of each player’s field status (such as location, speed, acceleration, team formation…), game situations (such as game clock, field positions, real-time score and win probability of home/visitor’s team…), and play outcomes (such as resulted yardage, penalties, and fouls…). Other supplementary dataset includes player’s information, game’s information, and PFF scouting data.

## Conclusion
This project addresses the need for a comprehensive and novel metric to evaluate tackling performance in the context of NFL. Even as a fundamental aspect of the game, tackling has lacked a standardized evaluation metric. The newly proposed metric could fill in the gap of the absence of tackling evaluation. The “pivotal factor” metric combines single factors such as game time, team score differences, downs, play results, and spatial relationships on the field, using combined weights to calculate the new metric in terms of player’s tackling performance. The metric is further validated with the natural distribution of tackle performance.

## Reference
1.	Kaggle competition description page:
https://www.kaggle.com/competitions/nfl-big-data-bowl-2024/data
