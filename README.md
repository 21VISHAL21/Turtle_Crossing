# Turtle_Crossing
This is a Python implementation of a simple game using the Turtle graphics library. In this game, the player controls a turtle and must navigate it across a busy road, avoiding oncoming cars. The player's goal is to reach the other side of the road safely while increasing their level as they progress.

## Files

- `main.py`: The main game script that initializes the game, creates the player, car manager, and scoreboard objects, and manages the game loop.

- `scoreboard.py`: Defines the Scoreboard class to keep track of the player's level and display game over messages.

- `car_manager.py`: Contains the CarManager class responsible for generating and managing the car objects that the player must avoid.

- `player.py`: Defines the Player class that represents the player's character (turtle) and contains methods for moving, going to the starting position, and checking if the player has reached the finish line.

## How to Play

1. Run the `main.py` script to start the game.
2. Control the turtle using the 'Up' arrow key to navigate it across the road.
3. Avoid the cars moving from right to left.
4. Try to reach the finish line without colliding with any cars.
5. The level increases as you successfully reach the finish line.
6. If you collide with a car, the game displays a "GAME OVER" message.
7. To exit the game, click on the game window.

## Dependencies

This game uses the Python `turtle` library for graphics and animation. Make sure you have Python installed with the standard library that includes `turtle`.

## Screenshots

<img width="454" alt="image" src="https://github.com/21VISHAL21/Turtle_Crossing/assets/71026896/eac318c3-cb28-46f8-81f0-035d78a59d58">
<img width="448" alt="image" src="https://github.com/21VISHAL21/Turtle_Crossing/assets/71026896/ec447369-4bcc-425e-b59e-89f7b1a619bd">

## Acknowledgments

This game is inspired by the classic "Frogger" arcade game and has been created for educational and entertainment purposes.

Enjoy playing the game, and feel free to modify and enhance it as you like! 
