### ATP Tennis Match Data Analysis (In Progress)

Authors: Adam Rohde

Date: 7/8/2020

Description: We’ll explore ATP match level data from 1991 to 2020. The work will include

* Explore the data.
* Cleaning the data and building a database.
* Calculating Elo Ratings.
* Performing simple analyses: Are older players doing better? What are the most important statistics for winning? How well does previous season’s preformance determine current season preformance? How do the results for best-of-three versus best-of-five set matches differ? How does handedness effect matchups?
    * Right now olny the first of these has been explored.
* Build models for predicting match winner incorporating player and head-to-head statistics as well as Elo ratings.
* Build a web app that provides player profiles, match up predictions, match up histories, Elo ratings, other fun things.  

Data Source: [JeffSackmann/tennis_atp](https://github.com/JeffSackmann/tennis_atp)

Files:

* Jupyter Notebooks: ATP_Match_Data_Explore.ipynb, ATP_Match_Data_Clean_and_Database_Creation.ipynb, ATP_Match_Data_Elo_Ratings.ipynb

* Data: atp_matches_\*.csv, atp_players.csv, atp_rankings_\*.csv (Note the data live in Google Drive.)

Extensions:

* Update Elo ratings to account for surface, best of 3 vs 5, score in sets or games, and players missing long stretches. 
* Incorporate more years of data. Specifically, to improve Elo ratings. 
* Do more to repopoulate some missing data. 

