# Pubg-Data-Analysis

URL FOR DATASET: https://www.kaggle.com/c/pubg-finish-placement-prediction/data

File descriptions
* train_V2.csv - the training set
* test_V2.csv - the test set


PlayerUnknown's Battlegrounds (PUBG) is an online multiplayer battle royale game developed and published by PUBG Corporation
a subsidiary of South Korean video game company Bluehole.
They have the option of fighting alone (Solo), with another player (Duos), or with a team of three others (Squads).
As time progresses, the playable area within the island gradually constricts to force encounters between players
until one player or team remains, thus ending the match.
We are provided with a large number of anonymized PUBG game stats, formatted so that each row contains one player's post-game stats.
The data comes from matches of all types: solos, duos, squads, and custom; there is no guarantee of there being 100 players per match, nor at most 4 player per group.
We created a model which predicts players' finishing placement based on their final stats, on a scale from 1 (first place) to 0 (last place).
From the dataset we check the correlation of the features with the target data i.e WinPlacePerc and choose the features that has a high positive correlation
and choosing random forest regression we train the model.Resulted accuracy - 78%.
