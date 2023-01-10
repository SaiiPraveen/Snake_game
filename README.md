# Snake_game
@@ -0,0 +1,5 @@
# Making Snake with Pygame

In this project, I create the game Snake using [Pygame](https://www.pygame.org/). I implemented this project mainly using Pygame, system and random libraries.
I create snake class and food class. Snake class represents moving snake and food class represents stationary block that the snake must eat to grow. Inside snake class I implement few methods like move, draw, reset, and retrive the information about the snake. In food class, the food has able to randomise the position and draw representation of it.
I declare global variables to keep track of screen width and screen height, grid width and grid height and some posible movements of the snake which are up, down, left and right.
Once game started, main loop will calls specific methods continously. I initialise the game and game clock which can keep track every action at a given time and I tick the clock at 10fps which increase the speed of the snake movement.
