![image](https://github.com/6willum/battleshipgame/assets/150245958/003a6529-e605-4358-b89e-6a2b2a884f81)

Two game boards are created for each player and it creates empty lists to hold each players ship positions

![image](https://github.com/6willum/battleshipgame/assets/150245958/7a86c483-f0fd-474e-a3f4-352b3fdd69dd)

Checks who the opponent is based on current player. Prints the players guesses and then prints the grid with the guesses using 'x' for a successful hit, 'o' for a miss and ' ' for an unmarked position.

![image](https://github.com/6willum/battleshipgame/assets/150245958/2f07721b-3281-44c5-9c4f-c02e613db026)

This asks the player to place their 4 ships by using a for loop. It checks whether the data is valid or not by checking whether there is already a ship there or if its actually within the grid. If there is an error with the input then it prompts the player to reinput the data.

![image](https://github.com/6willum/battleshipgame/assets/150245958/b378e0ce-10c3-494f-ba98-977a3677a0a3)

It asks for an input to guess the location of the opponents ships and has some validation to ensure the data input works with the code, looping if the data is incorrect. It checks if its within the bounds of the grid aswell If the players guess was correct and it hits a ship then it prints 'Hit!', if it misses then it prints 'Miss!'. The grid is updated to have 'x' or 'o' based on the outcome. There is also a check for whether the opponents final ship has been sunk using a Boolean Value.

![image](https://github.com/6willum/battleshipgame/assets/150245958/23101ef4-83a5-4c21-902f-903fa9073175)

There is an introduction message and the players are prompted to place their ships. The game loop begins and player 1 is the first player. The loop continues until either player has won.

![image](https://github.com/6willum/battleshipgame/assets/150245958/d46d7328-1639-42a4-9061-72ac538e9599)

There is an input for the grid size. The play() method is called and the game actually starts.

I also used these two websites as reference for some of my programming: 1: https://codereview.stackexchange.com/questions/232013/a-simple-battleship-game 2: https://www.sourcecodester.com/python/15752/simple-battleship-gamevs-ai-python-free-source-code.html
