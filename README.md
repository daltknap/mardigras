EECS 493 ASSIGNMENT 2:

BONUS FEATURES:

Parade Float:
-If the player is in front of the parade float, there will be 
 a honking sound played that tells the user to get out of the 
 way. 
-The parade float will also stop throwing candy if the player 
 is in front of it, and wont continue again until the player
 is out of the way.


Game State:
-The finale game state option has been added to the game.
-The user can specify in settings, what the final score needeed to 
 win is going to be. The default value for this is 5000 points.
-The number to play until has to be greater than 0.
-If the player collects that many points, the game will be over and 
 a screen will apear that says "You Win" over where the player was.
-When you win, it also plays some background music for fun.
-In the settings screen, it will also display the total amount of
 spaces that you traveled during the game, in pixels.


Picking up candy/beads:
-If you get hit by the beads/candy, you will lose those points
 that it would have been worth instead of gaining them. Being 
 hit adds one to the total number of objects hit count, displayed
 on the right of the game window.
-If you get hit, a womp sound is also played (located in the audio
 folder)
-Getting hit also will be displayed by the object being highlighted
 in red, instead of yellow.
-When you run over a piece of candy it will play a ca-ching sound 
 (located in the audio folder)
-When you run over a set of beads, it will play a woo sound
 (located in the audio folder)


Game Audio:
-In the settings pannel, you have an option to "Play Music"
-If selected, this will trigger a loop of back-ground music to play
-Be ready to get very annoyed with the same loop of music playing
-There is also a "Stop Music" button, that will stop it from playing.


Item Duration:
-In the settings pannel, there is now an option to control how long 
 until an item begins to disappear. The minimum accepted value for 
 this is 1, and it controls how long the object will sit there before
 it begins the disappear process.


SUPERPOWERS:

Speed Mode:
-About every 20th object thrown is a superpower called speedmode.
-If you pick up this object, which is a red or orange clock looking
 thing, the players speed is doubled to 50 pixels per click of the keyboard.
-The sound will say speed mode when you first get it, and then there is
 a clock that tiks for 10 seconds, until the voice comes back to say 
 speed mode over.
-This power allows you to move around the map at double the speed, making
 it easier to collect items.
-This item is highlighted blue when you get it, instead of yellow or red.

Unstoppable:
-About every 20th object thrown is a superpower called unstoppable.
-If you pick up this object, which is a black image of a arm,
 the player will be able to move through objects such as the float.
-The sound will say unstoppable mode when you first get it, and then
 there is a clock that tiks for 10 seconds, until the voice comes back
 to say unstoppable mode over.
-If the player is colliding with the float when the 10 seconds are up, 
 he will continue to stay in unstoppable mode until the player is no
 longer colliding with either floats.
-This item is highlighted blue when you get it, instead of yellow or red.

Double points:
-About every 20th object thrown is a super power called double points.
-If you pick up this object, which is a x2 image, all point values for
 candy and bead objects will be doubled and worth 200, instead of 100.
-This power lasts for 10 seconds, before turning off and going back to
 having objects worth 100 points.
-The sound will say double points, with credit to Call of Duty: Zombies,
 and have a clock tick for 10 seconds, and then the voice will say
 double points over. 
-This item is highlighted blue when you get it, instead of yellow or red.


Status Window:
-On the right side during the game, in the status screen there is now 
 a count that shows you how many objects you have been hit by.
-If you get hit by beads/candy, it counts as an object hitting you
 and you do not get to pick up that object, and you lost points for it.


Play Again:
-After winning the game, there is a button that appears next to the 
 game window that says "Play Again". When the user selects this, it
 reloads the screen and starts a new game.


Quit Game:
-On the main screen, under the open settings option is a button to 
 quit the game. 
-If pressed, it immediately ends the game and brings you to a final
 screen. It has a red screen that says Game Over, and it also gives
 you the option to play again and shows the stats from the last game.
-The button appears only after the original splash screen has 
 disappeared.
-When the game is over, a sad song is also played. The goal is to make
 the user sad and to get them to look at the screen and want to play
 again.


Settings Menu:
-In the settings menu, we now have the options to change the following:
    -Item thrown from parade time length
    -Score until you win and the game is over
    -Item thrown duration time
    -Play background music
    -Stop background music
    -Save and close settings pannel
    -Discard and close settings pannel
