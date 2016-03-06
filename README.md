# Cluster-NBA-Players
We have data about performances of NBA players in 2013-2014 season. Data are obtained from basketball reference website. http://www.basketball-reference.com/leagues/NBA_2014_per_game.html

We are going to implement the machine learning technique called clustering to visualize the types of point guards as well as group similar point guards together. We will use 2 features to accomplish this task because it allows us to easily visualize the players and will also make it easier to grasp how clustering works. 

For point guards, it's widely accepted that the Assist to Turnover Ratio is a good indicator for performance in games as it quantifies the number of scoring opportunities that player created. Let's also use Points Per Game, since effective Point Guards not only set up scoring opportunities but also take a lot of the shots themselves.

Some selected columns are listed below.

Player: name of the player(First Last)
Pos: position of the player
Tm: team	
G: number of games played	
MP: minutes played per game	
AST: assists per game	
TOV:	turnovers per game
PTS: points per game

Cleaning and Visualization

We already have point per game data, therefore after we obtain assist turnover ratio data, we have all our data ready. And the assist turnover ratio data can be calculated by dividing the assists per game by turnovers per game. We can visualize our data set by plotting points per game versus assist turnover ratio using matplotlib, a plotting library powered by Python. 

Clustering

Checking by eyes cannot give us a precise division of groups of point guards. Here we are going to use a unsupervised machine learning techniques, called clustering, to segment all of the point guards into groups of alike players.

