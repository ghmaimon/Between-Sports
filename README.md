# Winning-In-one-spots-means-winning-in-others-

This project is about testing the relation ship between the winning ratio in one sport and the winning ratio in others in a specific metropolitan area.

the project is based on a TTest between the winning ratios in a specific sport in different countties.
the results is a pandas DataFrame where the columns an index is ['NFL', 'NBA', 'NHL', 'MLB']

and each cell gives the p-value of the ttest between the two sports specifed in the column and index. for exemple in the cell (NFL,NBA) we find the p-value from the ttest between nfl and nba winning ratios.

PS : the p-value between nba and nba is Nan.

# functions used:

mlb():
  returns a pandas Series in which the index is the metropolitan area and the columns are winning ratio of this area in the MLB, the population in the area, and the number of       teams of MLB in the area.
  same with nba(), nhl(), mlb().

sports_team_performance():
  uses the 4 previous fonctions and returns the DataFrame wanted.
  
# DataSets used:

NFL.csv, NBA.csv, NHL.csv, MLB.csv : in which we find the data about the winnings and loses of differents teams in those sports.

wikipedia_data.html : an html file from which we extract the informations of each metropolitan area (population ...).

  
