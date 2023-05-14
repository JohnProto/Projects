# Projects
Some self projects I've been working on for the past 2 years

## **Stratego Game**

https://user-images.githubusercontent.com/131659599/234344421-70d79967-07f9-4903-800a-799dc51dd8fc.mp4

Made a Stratego game from scratch with Java. You can click each piece to reveal the available squares the clicked piece can go to. You can also attack the other player's pieces. The attacking phase works like this: Each piece has a number indicating his rank. The higher the rank, the more powerful the piece. When a higher rank piece attacks a lower rank piece, the second dies and dissappears from the map. Also some pieces have special abilities such as moving more squares or attacking higher ranked pieces. The winner is decided when the other player's flag has been captured.\
You can find the code [here](https://github.com/JohnProto/stratego_game)

## **Sudoku solver and generator**

https://user-images.githubusercontent.com/131659599/234402810-7bd1aa6c-2951-497f-b4f0-52143e2af02c.mp4

Made a sudoku solver which can also generate a random sudoku with C. You can insert an unsolved sudoku through the command line, and it'll print the solved sudoku and also if the solution is unique or not. It solves the sudoku with a backtracking algorithm I made and various other functions that help with finding errors and checking if the sudoku is correct. The program can also generate a completely new sudoku with as many non-zero cells as you want and you can also specify if the generated sudoku will have a unique solution or not.\
You can find the code [here](https://github.com/JohnProto/sudoku_solver)

## **Blogger like app**

https://user-images.githubusercontent.com/131659599/234401998-d3975598-faf1-45f5-8a19-05adfaf9b086.mp4

Made the back-end code of an app with C that resembles the Blogger subscription system. There are creators and consumers. The creators can post content and see statistics of their various channels that they've created. The consumers can subscribe to a channel and consume the content it has, and even see which content they already consumed and proceed to read the new content. With a complex system of leaf oriented trees and lists, each action inserted by the user through the command line, whether he is a consumer or a creator, can affect the relations between each tree, resulting in a very good structured subscription system.\
You can find the code [here](https://github.com/JohnProto/blogger_app)

## **Tank Game**
Made a World of Tanks similar game using Unity and utilizing C#. You can move your tank with the arrow keys in the keyboard and attack the enemy tank with the left click of the mouse. The tank has a health bar and each time it gets hit the health decreases. There are also some power-ups inside the arena that give your tank certain powers like faster movement. Lastly I developed an achievement system that when you complete certain tasks the achievement is added to your completed tasks list. This is a two player game that the two players play from the same keyboard using the arrow keys or the WASD keys.

## **Keylogger**
Made a keylogger using the c language that logs all the keystrokes of the keyboard to a .txt file. I also compiled it to an .exe file so it can run without needing VSCode to be open. First i open up a cmd window and close it instantly and then after each keystroke, I check if the key pressed is a special key (Space, Backspace, Alt, Ctrl, Tab, Capslock, Shift) and I do the corresponding adjustments to the .txt file.\
You can find the code [here](https://github.com/JohnProto/Keylogger)
