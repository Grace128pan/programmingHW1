Student Name: Zhen Pan(ID.231AHG002)
Project Name: "Cat Catching the Rat Game" python game(using pygame)
Email: Zhen.Pan@edu.rtu.lv/gracepan922@gmail.com

Project description:
1. Win or lose rule: 
When the cat catches the rat within 10 turns, the cat wins the game; otherwise, the cat loses the game.
The cat should make the first move. 
The cat_position and rat_position should be random, and they can move randomly, but the rat should not move to the cat cell
when they are adjacement.

2. Functionalities:
1) Background music: background.mp3("super mario" sound effect) is used during the game playing time and it will stop when "pause" button is pressed.

2) win_sound: when the cat wins, there will be win.mp3 playing("hampster dance" sound effect).

3) lose_sound: when the cat loses, there will be lose.mp3 playing("angry cat meowing" sound effect).

4) Graphic and text effects: 
I. When the cat wins, there will be award.jpg popping up.
II. The playing layout will be 5 * 5 window_size in black background
III. The buttons will be in #0FA4AF color with some border-radius to make them rounder
IV. When the game is over, the background will be white, the black text for users to choose an image as the cat player will show up(when win); otherwise, the black text"out of turns, the rat got away!" and then "game over!" will show up with "try again" and "exit" options to choose from.
V. The text will be in "Times New Roman" font

VI. When the player wins the game, the player can choose the cat player from option 0 to 5(user-keyboard input features)
0: default(a jumping orange cat)
1: dollar(an European short-hair cat)
2: flower(a normal pet dog)
3: lucky(an adult orange cat)
4: niu(a calico cat)
5: sunny(a normal hybrid cat)
1-5 options are actually my pets(4 cats and one dog, the names are their actual names. "Flower" is a real male dog name, not a flower or a cat)

VII. rat.jpg(rat character in the game) and jumpingCat.jpg(default cat character) are free online sources
VIII. When the cat wins, black text "Cat caught the rat! Congraduations!" will be shown with white background.

5) Button effects:  5 different buttons as follows
I. During playing, "Instructions", "Pause", " Continue", "Exit" options can be chosen.
II. When game is finished, "Try again" and "Exit" options are available.
"Instructions": when clicked, there will be 7 instructions to tell how the player can play the game.
"Pause": during the playing, the player can "pause" to have some rest.
"Continue": after the pause time, the player can click "continue" to continue the previous paused game.
"Exit": during the playing, the player can click "exit" button to exit the game; when the player loses the game, the player can also press "exit" to exit the game.
"Try again": When the player loses the game, the player can press "try again" button to replay the game.

3. Additional infos:
1) Import pygame and random libraries to run the game
2) Additional audio and image materials should be included in order to make all functionalities work smoothly
3) The audio folder includes 3 sound sources(background.mp3; lose.mp3; win.mp3)；
   the image folder includes 8 images: award.jpg, jumpingCat.jpg, dollar.jpg, lucky.jpg, sunny.jpeg, rat.jpg, flower.png, niu.jpg。
4) The program include a main.py and a functions.py. There is a functionPackages folder including necessary files(functions.py, _init_.py, _pycache_).

PS: there is a Cat Catching the Rat Project.pptx file to pinpoint the key ideas of the project.