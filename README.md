#c-pokemon

---

LAUNCH THE GAME
Operating system needed : Linux

To play the game : open the terminal, head to the right folder : c-pokemon/
				   type "make" in the terminal and the game will launch !

IF IT DOESN'T WORK FOR X REASON
compilation command : gcc -o c-pokemon src/game.c src/talkbis.c src/talk.c src/physic.c src/main.c src/print.c -lncurses
execution command : ./c-pokemon

To play with the musics of the game simply download the musics of the following drive and add them to the "/ressources" directory :

https://drive.google.com/drive/folders/1zd71bI2840ISNPX0Q56OMyE7kj1kJaG0?usp=sharing

---

TECHNICAL NEEDS

For the technical aspect you'll need to have a terminal which can at least display 63x236 characters (63 lines and 236 columns) -> you can dezoom by using 'ctrl' + '-' and zoom with 'ctrl' + '+'.
For a better experience, play in fullscreen mode by pressing "F11".

ESSENTIAL : To play the game you'll have to install the ncurses library in your pc by typing "sudo apt-get install libncurses5-dev"
OPTIONAL : To play the game with its musics you'll have to get vlc media player by typing "sudo apt-get install vlc" in your terminal.

---

COMMANDS

During the entire game, when having to make a choice or do something you'll have the possibility to go back with the 'spacebar'. The spacebar will allow you to go back in your choices at most of the times, just like a 'B' or 'O' button.

The mooving controls are 'z' and 'UP_ARROW' to move forward, 's' and 'DOWN_ARROW' to move backward, 'd' and 'RIGHT_ARROW' to go to the right, 'q' and 'LEFT_ARROW' to go to the left.
The game controls are 'i' to open the inventory (NOT EVERYWHERE) and 'm' to open the menu (NOT EVERYWHERE). While in the menu and inventory you can interact with objects and pokemons (NOT ALL). The last game control is the interact button which is 'e' or 'ENTER_KEY', which will allow you to accept, interact, choose, etc...

There is an exception in the road to go to the league, after picking up a flower by pressing 'e'/'ENTER_KEY' while being on it, you can plant it again in the ground by pressing the 'p' touch.

---

THE LORE

Here are the main instructions to play the game we made but we'll try not to be too precise to let you discover the game by yourself.

Basically, this game is pokemon. All the mechanics of our game were inspired by pokemon so you'll find CT (capsule technique) to learn stat attacks to your pokemons, potions to heal them, candys to make them level up etc...
If you were used to play pokemon in your youth you'll feel just like it's a back to basics.

If not, here are the basics :

You have to know that you can buy the CT in the shop and then learn it to your pokemons at the lab by talking to the professor Chen.
You have to catch pokemons in the forest to build the best team and train your pokemons by learning them CT and making them level up and even evolve !
Once you are satisfied of your team, head to the league to challenge the greatest pokemon trainers of the region.

- The inventory ('i') shows you what's in your pocket currently and it allows you to heal your pokemons at any time by using potions and make them level up with candys, just interact with it.
- The menu ('m') shows you your trainer level, your xp, and your money. In it, you can save, quit the game and see all of your pokemons in "your team".
- The your team menu shows you all of your pokemons, it allows you to move them and change their emplacement. You can also free them and release the pokemons. The first 3 pokemons are your duel
  team, they'll be the pokemons to fight when you will launch a fight with a wild pokemon or a champion.
- In the lab, you'll find a computer in which you can put your pokemons. You have 20 slots to manage your pokemons + the 6 in your pocket. Once you're done, click on 'spacebar' to disconnect.
  Don't give you login or your password to people you don't trust ! They could steal your pokemons :(

At the very begining of the game, you'll have the choice between the 3 starters charmander (salamèche), squirtle (carapuce) and bulbasaur (bulbizarre), and you'll be leaved alone in the town of Bourgpalette. At this point you are free to do anything you want to but you'll be blocked by some obstacles, try to interact with them.

In the map, you'll find your home, in which is your mom that will be helpfull in your adventure.
You'll find other unvisitable buildings, a shop and a lab. We let you discover what's in these buildings. You can enter in by pressing the interact button next to the door.

As in pokemon, the main goal is to become the master of the league ! And, for this you can go fight wild pokemons and try to catch them to make the most powerfull team to fight the champions of the league Blue, Red and Yellow with their own personality !

Have fun playing our first game ! If you find bugs don't hesitate to let us know ! We don't think that our program is perfect. Thank you by advance ! You gotta catch 'em all !

---

KNOWN BUGS

We have a single bug repport to do, in fact sometimes when you pick a flower from the ground, it just stays there and another flower disapear and go to your inventory. It's a really rare bug, it happens 1 time on 50 so we didn't solve it because of it rarity. You just have to click again to pick the right flower so it's not a big bug but we want you to know it just in case.

---

THANKS TO

- Amine Zahaf (friend)
  We are really grateful for the help Mr Zahaf provided us. Your advices were essential to manage our team and be as effective as possible, we learned a lot from you and we want to thank you for all of your precious advices.
- Romuald Grignon (teacher)
  Sir, we apologize about the lenght of our project. We wish you a good luck with the correction. We love you sir, you're our inspiration, one day we'll also code an entire game just in a week-end. Thank you for your help and your time, this project would have never existed without you (the "top" command is on top !).
- Eva Ansermin (teacher)
  Miss, we hope you'll love the ending of this ambition. The idea of making a map came from you and we would surely didn't have done all of this without your support. It was a pleasure to see you as happy as us seing the project evolve day by day.

---

CREDITS

Adam Terrak -
Ayman Ouguerd -
Abdelah El Harsal

---

CONTACT

e.aterrak@gmail.com - aymanouguerd@gmail.com - abdelah.elharsal@gmail.com

---

RESULTS

We got 20/20 and were ranked 1/323 students

---
