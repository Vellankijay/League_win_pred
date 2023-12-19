# League Win Predictor

This is a collaborative take on the analysis of a popular game named League of Legends.

League of Legends (LoL), commonly referred to as League, is a 2009 multiplayer online battle arena video game developed and published by Riot Games. Inspired by Defense of the Ancients, a custom map for Warcraft III, Riot's founders sought to develop a stand-alone game in the same genre. Since its release in October 2009, League has been free-to-play and is monetized through purchasable character customization.

There are around 160 champions in the game currently and the gameplay happens in a 5v5 mode in a tournament style. The game's results depends on the champions choice, their ability with teamwork, the resources they accumilate (such as gold and items) etc. Since there are many variables that determine a team's victory, our group decided to perform an analysis of the gameplays and predict who would win the game during the first half of the gameplay.

# Objective
Our objective are as follows
1) Predict the outcome at the first-half of the gameplay
2) Determine which variables are influential in the outcome of the game

# Data Sources
To do this we downloaded data from Kaggle here: https://www.kaggle.com/datasets/fernandorubiogarcia/league-of-legends-high-elo-patch-1016/

The dataset consists of around 60k rows, each representing a game of high ELO League of Legends from various regions of the world.

The data has around 600 columns, better thought of as 60 columns per each of the 10 players, 5 on each team. These included but were not limited to
 damage done, damage taken, gold gained, kills, and the ELO of each player. 
