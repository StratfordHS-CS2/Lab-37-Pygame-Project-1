# Lab 37 - Pygame Project 1

## Grading 

**This is a major grade.**

Due Date: Wednesday, April 14th at 11:59 pm

Late labs will receive: 

* -10% until Wednesday, April 21st at 11:59 pm.  
* -20% until Wednesday, April 28th at 11:59 pm.
* Treated as a retest (max of 70) afterwards.

## Introduction

Make a game using what we have learned about Pygame so far.  A game has a purpose and an ending.  The purpose could be earning a high score, collecting all of the coins, guessing a number, etc.  The ending could be successful (achieved the goal), or ending in failure (no more lives, no more guesses).

## Requirements

1. You may use either a window or fullscreen.
2. Frames per second should be used.
2. There must be a background that makes sense.  It could be a color or an image (we haven't covered images as backgrounds, but you can look it up).
3. There must be rendered text.
4. There must be user input from either the keyboard or the mouse or both.  This could be clicking a button to start a game, then using the keyboard to play.
5. There must be moving objects on the screen, otherwise this will be a very boring game.
6. There must be a goal.
7. There must be obstacles to the goal.  These may be enemies, catching the wrong falling object, hitting a barrier, guessing wrong, etc.

**DO NOT BE OVER AMBITIOUS!**  Keep in mind what you have learned and the time allowed.  Feel free to ask me if I think your idea is reasonable.  You may have a great idea, but it may not be doable in the time allowed.

## Possible Ideas

You do not have to pick one of these ideas.  These are intended to give you ideas and a starting point for thinking.  You may use these ideas if you want to.

1. Objects fall from the top of the screen.  The player must click certain objects to gain points while not clicking others that would lose points.  Goal is a certain number of points, or the game ends after a certain number of bad objects are clicked.

2. Whack-a-mole.  An object shows up on the screen for varying amounts of time (possibly getting shorter as their score gets higher) and the player tries to click it before it disappears.

3. Player tries to click as quickly as they can when an image shows on the screen.  Higher points for quicker clicks.

4. Player tries to click as many times as they can in a certain time limit.  High scores are tracked and celebrated.  Click speed is shown.

5. Juggling.  Click a falling ball to send it upwards.  Use a random range of possible upward directions, simulate gravity (downward acceleration).

6. Avoid the moving objects.  The player uses keyboard controls to avoid objects moving on the screen.  Could be bouncing around the screen, falling from the top, moving from the side, etc.

## Cite Sources

I don't expect you to limit yourself to the content on It'sLearning.  However, if you get help from a website you need to put the URL as a comment in your code near where you used its help.

For example, I want to use a background image instead of just a color so I search online and find a website that helps me.  I should cite that source something like this:

```
# Learned how to use a background image.
# http://programarcadegames.com/index.php?chapter=bitmapped_graphics_and_sound&lang=en
background_image = pygame.image.load("stars.jpg").convert()
screen.blit(background_image, [0, 0])
```

You can also cite a person if someone helps teach you something.

You do not need to cite little things like "Looked up a color code" or "Looked up a Pygame Key Code"