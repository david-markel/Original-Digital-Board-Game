# Digital-Board-Game
Original Board game for 2 to 4 players

****FOR CONTEXT****
First and foremost, I have only uploaded this so that any recruiters/employers may examine this game that I have created. If you are not a recruiter/employer, or somebody I have personally invited to view this code, then 1) How on earth did you find this? 2) Please click away. I am not ready to release the game, although it is fully operational. Notice that I have not said that is complete in that I wrote this code before I started college as a way to teach myself python while also creating a passion project to play with friends and family. While it is not all bad, it certainly needs to be cleaned up, (there are a couple of global variables declared, for ex.). Nonetheless, the code works and I have played the game a countless amount of times. I will go back when I have the time to optimize it and make it adhere to conventions using my newfound coding knowledge from my education. I am very proud of this project, as unpolished as it may be, as it demonstrates that I know how to program an ambitious project from start to finish. 

Alrighty, with that out of the way, here's what you need to know about the game: 

To run, you will need to simply compile and run the Digital_Board_Game.py file and pygame will take care of the rest. For the record, I have used the pygame library in python to make this, and it was sufficient to make the entire thing code-wise. You can ingore all of the other files as most of them are sprite animations for the 20 different units that are in the game. 

Once the game is running you will see this: 
<img width="771" alt="BG_MENU" src="https://user-images.githubusercontent.com/60165504/159140973-d2d6a9b2-2cdb-4910-baa0-81ecc5fa336d.PNG">

This is the game start up menu, where (2 - 4) players each select a team of 6 units from the available 20 classes. They can also choose the number of players, the level of music volume, and the board "geography." In the above picture, it is the red team's turn, indicated by the red sword pointing to the read squares. What does this mean? Well, the board is the same as a chess board. Overall, this game is basically 4 players chess except you choose a unique combination of "pieces" or units. These units have stats--health, attack, range, and movement--as opposed the move and capture mechanics of chess. 

So, what are those colored squares? They are the castles of each team, and because they are where your units will start out in the game, they have extra tiles surrounding the castle where units can start. If you are trying this out for yourself, click select, then click a square of your team's color (again whose turn it is indicated by the colored sword) then click one of they gray units from the top to populate that square with that unit. The numbers on the unit icons represent their stats, see the key in the top left (Health, attack, move, range). To clear that unit, click clear and click any of your units. Poof, they are gone. 

Select and clear have dual functionality: click on the white empty space in the grid, and it will add an obstacle- a tile once the game starts that most units cannot traverse. Clearing these black tiles will erase them. Finally, Click the "X PLAYER" button to toggle the amount of players, and the board with update automatically. Next, the cascadiing bars affect the percentage the music is played at. Finally, the colored arrow when clicked will pass the turn to the next team, and hide the the team that you just prepared. Start will start. 


<img width="771" alt="BG TEAM" src="https://user-images.githubusercontent.com/60165504/159141332-9fbe26c4-1411-41dd-b495-92428ca81ec5.PNG">


