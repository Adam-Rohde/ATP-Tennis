### ATP Tennis Match Data Analysis (In Progress)

Authors: Adam Rohde

Date: 2/23/2020

Description: We’ll explore ATP match level data from 1991 to 2020. Some of the questions we’ll look into include: What is the effect of age on performance and has this changed over time? (Interpertable Models) What are the most important features for identifying variation in performance? (PCA) How well does previous season’s preformance determine current season preformance? Do players have “hot” streaks where winning begets more winning? Is there more variance in the results for best-of-three versus best-of-five set matches? (Does the higher ranked player or player who has done better in head-to-head win more frequently?) How important are first serve percentage, break points saved/won, number of aces, average serve speed, … effect performance? Are big servers better? (Not controlling for other factors; does a big serve usually come at the cost of other elements that make players more successful) Do lefties perfrom better against righties or other lefties? We’ll also try to build a model for predictinig match winner. (Using DL, SVM, and/or XGBoost.)

Dataset: [JeffSackmann/tennis_atp](https://github.com/JeffSackmann/tennis_atp)

Files:

* Jupyter Notebook: ATP-Tennis Match Data Analysis.ipynb

* Data: atp_matches_*.csv
