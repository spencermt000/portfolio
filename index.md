---
layout: default
---
# Welcome to My Portfolio
##### My name is Spencer Thompson and I am a Senior at Baylor University majoring in Marketing and Business Analytics. Sports has been, and will always be, a big part of my life. That combined with learning how to code in R and Python from my older brother ha



### Calculating WAR in NFL using RAPM and Hierarchical Bayesian Models 
Ideas:
- PFF Grades from previous season as "priors"
    -- could experiment with a weighted career average instead of just the year before
    -- handling rookies by using draft capital
- position specific penalization
- situational adjustments
    -- run vs pass
    -- goal to goal or redzone
- remember to check for multicollinearity. deal with that when we get there 
- incorporating box score stats potentially? either in priors alongside PFF or as covariates
    -- i think we should use any "directly" attributable play we can. meaning if a player gets a sack, interception, forced fumble, etc. that shouldn't be attributed to everyone. can we use that covariates? in the model
