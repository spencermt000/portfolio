# Analyzing Chess Piece Activity
## Overview
I downloaded the .pgn files of over 2000 of my chess games and nearly 30,000 games from Grandmaster Hikaru Nakimura. I wrote code in Python to loop through each game in the files, tracking each pieces' location, and calculating the "scope" of the piece. I used R to further clean and organize the data before using Tableau for the visualizations. Scope refers to how many squares a piece can see, excluding pawns. I also kept additional data like the ECO code for the opening played, the unique piece ID (since there's 2 bishops, knights, rooks), the winner of the game, and the ELO of the players. I wanted to see if there is any interesting trends regarding piece activity throughout the game and how openings might affect that. 

### Knights
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/b04671bc-5b24-4d47-9e68-3befb5b8c008" />
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/4ee3a6a8-41f4-496a-86e3-4b4d29cfb581" />
We can see that the hypothesis, winners typically have more active pieces, is even more prevalent in Hikaru's games than mine. 

### Bishops
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/73daa6cd-9511-4074-ba57-feee1677b4b5" />
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/4345fdd8-6091-440c-9ab6-01eabacc5d8a" />
The same is true with Bishops, to a more significant degree. Conventional chess strategy involves developing knights before bishops, I wonder if that is truly accurate advice. 

### Queens
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/85cf4bc9-b6bc-4585-ad52-ec28c2b8f3cf" />
<img width="1000" alt="image" src="https://github.com/user-attachments/assets/f23f1e4c-75d5-470d-ab1c-8c05f51fcffd" />
Interestingly it seems that the Queen's activity is much more important in my lower elo games than in Hikaru's, which makes sense. Lower level players often struggle with playing, I know I do. Additionally, the type of openings beginners typically play are different than GM-level openings. For example, both the Scandinavian Defense and Scholar's Mate involve bringing the Queen out early and are common lower-level openings. 





