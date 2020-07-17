### ATP Tennis Match Data Analysis (In Progress)

Authors: Adam Rohde

Date: 7/17/2020

Description: We’ll explore ATP match level data from 1991 to 2020. The work will include

* Explore the data.
* Cleaning the data and building a database.
* Calculating Elo Ratings.
* Performing simple analyses that I found interesting. There will surely be more of these to come. 
    * Are older players doing better?  
    * How many matches are typically in a player's career and how many years does a typical career last?
    * How many players have been ranked number 1 and how can we visualize which players dominated during different periods of time?
    * How do the results for best-of-three versus best-of-five set matches differ? (In Progress)
    * How does handedness effect matchups? (In Progress)
* Build models for predicting match winner incorporating match and player information, head-to-head statistics, as well as Elo ratings. (In Progress but there is some initial work on this.)
* Build a web app that provides player profiles, match up predictions, match up histories, Elo ratings, other fun things.  (In Progress)

Data Source: [JeffSackmann/tennis_atp](https://github.com/JeffSackmann/tennis_atp)

Files:

* Jupyter Notebooks: ATP_Match_Data_Explore.ipynb, ATP_Match_Data_Clean_and_Database_Creation.ipynb, ATP_Match_Data_Elo_Ratings.ipynb

* Data: atp_matches_\*.csv, atp_players.csv, atp_rankings_\*.csv (Note the data live in Google Drive.)

Extensions:

* Update Elo ratings to account for surface, best of 3 vs 5, score in sets or games, and players missing long stretches. 
* Incorporate more years of data. Specifically, to improve Elo ratings. 
* Do more to repopoulate some missing data. 

