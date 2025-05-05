# Evaluting NBA Player's Defensive Performance using PCA Clustering
## Overview
I built a player clustering model using NBA data to uncover player roles based on both individual performance and team context. I collected detailed play-by-play and box score data through the hoopR package in R and augmented the dataset with external player statistics from Basketball Reference. After cleaning and merging the data sources, I engineered a set of features that capture both individual metrics (STLs+BLKs, Opp FG%, etc.) and team-dependent metrics (team DEF rating, plus minus, etc.). I then applied Principal Component Analysis (PCA), intentionally structuring the first two components to reflect these two dimensions: PC1 as an “individual impact” axis and PC2 as a “team context” axis. Using these principal components, I clustered players into four distinct groups, revealing patterns in player usage and team fit. This kind of analysis can help front offices, analysts, or fans identify undervalued contributors, role fit in different systems, or spot potential mismatches between player skill sets and team strategies.


### Clustering for Forwards
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/47ddadbb-ae5f-4789-9d2d-37fac1a1ad24" />

### Clustering for Guards
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/53c224ba-b5c5-482c-b024-574afd4d8cdc" />

### Clustering for Centers
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/0952a76e-c4fc-447b-b288-f2c0fffeb6af" />

### Comparing Players
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/76d4f002-aa27-4f0e-8f63-36a42fb93886" />
