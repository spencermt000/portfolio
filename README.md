# Welcome to My Portfolio!
##### My name is Spencer Thompson and I am a Senior at Baylor University majoring in Marketing and Business Analytics. I am currently planning on pursuing a Master's degree in Business Analytics or Data Science at TBD University. As a lifelong fan and athlete, sports is one of my biggest passions and the source for the majority of my projects. I have experience using a variety of methodologies from clustering to binary classifications to predictive modeling. My primary focus is in the field of player evaluation and player valuation. Below is a list my current and past projects along with a brief overview. Thank you for checking me out!

## My Projects 
### [Classifying and Predicting Stunts on NFL Pass Plays](https://github.com/spencermt000/portfolio/blob/main/_posts/NFL_stunts.md)
**Overview**: This project focused on identifying and classifying pass rush stunts (see example) using player tracking data from the NFL Big Data Bowl. The goal was to automate the detection of stunts across thousands of plays to enable deeper player evaluation and defensive analysis. I began by cleaning and preprocessing the raw player tracking data in R, then visualized every pass rush snap to highlight defenders’ movement paths. I developed an interactive Shiny app that allowed for manual classification of 200 plays based on visual inspection of rush patterns. The core of the modeling pipeline was a fusion model built in Python that combined an image classification model (trained on visual representations of the plays) with a gradient boosted model leveraging situational features like down, distance, time, etc. This hybrid approach achieved 76% accuracy on the test data. After applying the model to the full dataset, I used the predicted stunt classifications to isolate and analyze performance on those plays—opening up avenues for assessing player impact in complex defensive schemes. Potential future improvements include integrating more features, incorporating raw tracking data directly into the model to reduce classification noise, and expanding the labeled training dataset for better generalization. 

### [Evaluting NBA Player's Defensive Performance using PCA Clustering](https://github.com/spencermt000/portfolio/blob/main/_posts/NBA_def_pca.md)
**Overview**: I built a player clustering model using NBA data to uncover player roles based on both individual performance and team context. I collected detailed play-by-play and box score data through the hoopR package in R and augmented the dataset with external player statistics from Basketball Reference. After cleaning and merging the data sources, I engineered a set of features that capture both individual metrics (STLs+BLKs, Opp FG%, etc.) and team-dependent metrics (team DEF rating, plus minus, etc.). I then applied Principal Component Analysis (PCA), intentionally structuring the first two components to reflect these two dimensions: PC1 as an “individual impact” axis and PC2 as a “team context” axis. Using these principal components, I clustered players into four distinct groups, revealing patterns in player usage and team fit. This kind of analysis can help front offices, analysts, or fans identify undervalued contributors, role fit in different systems, or spot potential mismatches between player skill sets and team strategies.

### Scraping Fantasy Football League & Draft Data using SleeperAPI (in progress)
**Overview**: 

### [Analyzing Chess Games](https://github.com/spencermt000/portfolio/blob/main/_posts/chess_myself.md)
**Overview**: I downloaded the .pgn files of over 2000 of my chess games and nearly 30,000 games from Grandmaster Hikaru Nakimura. I wrote code in Python to loop through each game in the files, tracking each pieces' location, and calculating the "scope" of the piece. I used R to further clean and organize the data before using Tableau for the visualizations. Scope refers to how many squares a piece can see, excluding pawns. I also kept additional data like the ECO code for the opening played, the unique piece ID (since there's 2 bishops, knights, rooks), the winner of the game, and the ELO of the players. I wanted to see if there is any interesting trends regarding piece activity throughout the game and how openings might affect that.

### [Calculating WAR in NFL using RAPM and Hierarchical Bayesian Models](https://github.com/spencermt000/portfolio/blob/main/_posts/NFL_war.md) (planned) 
**Overview**: 






