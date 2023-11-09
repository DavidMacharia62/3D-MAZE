# 3D-MAZE

# 3D Maze Game

![Game Screenshot](screenshot.png)

## Description

3D Maze Game is an immersive gaming experience that challenges players to navigate through intricate mazes. Built using SDL2 and primarily written in C, this game offers a visually engaging journey through dynamic 3D environments. Explore the depths of complex mazes, encounter challenging obstacles, and engage in thrilling combat sequences with integrated enemies.

## Features

- Seamless 3D gameplay experience with intricate maze designs and challenging puzzles.
- Smooth camera movements and interactions within the 3D environment for a realistic gaming experience.
- Immersive visual elements, including textured walls, ground, and ceiling, enhancing the overall game atmosphere.
- Dynamic enemy encounters and engaging combat mechanics, providing an adrenaline-fueled gaming experience.
- Weather effects, including rain, to add an extra layer of realism and intensity to the gameplay.
- Advanced features such as shadows and special lighting effects, contributing to the game's captivating atmosphere.

## Getting Started

### Prerequisites

- C Compiler
- SDL2 Library

 - Sdl2 installation
download the installation script [install_SDL2.sh](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/graphics_programming/install_SDL2.sh) and run it in your ubuntu Terminal as follows:
root@h:cd ~/Downloads$ ls
install_SDL2.sh
root@h:cd ~/Downloads$chmod 755 install_SDL2.sh
root@h:cd ~/Downloads$sudo ./install_SDL2.sh

# Play the game
 - clone the [github repository](https://github.com/Susiniosgit/3D_Maze.git)
 - Compile all .c files in the maze directory:
  ```
  gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm $(sdl2-config --cflags --libs) -lSDL_image -o maze
   ```
 - Execute ./mazea and play game.
 - Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
 - Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)
# Controls
 W or up arrow key - Moving forward
 S or down arrow - Moving backward
 left arrow key - to rotate the player in counter clock wise direction
 right arrow key - to rotate the player in clock wise direction

### Usage

- Use the arrow keys to navigate through the maze.
- Press the spacebar to interact with objects or engage in combat.
- Explore the maze, solve puzzles, and defeat enemies to progress through the game.

## Data Model

[To include a brief overview or link to the data model diagram, explaining how data is stored within the game.]

## User Stories

1. As a player, I want to immerse myself in a challenging 3D maze environment, solving puzzles and overcoming obstacles to progress through the game.
2. As a gaming enthusiast, I want to enjoy smooth camera movements and interactive gameplay, enhancing the overall gaming experience.
3. As a fan of combat games, I want to engage in thrilling combat sequences with dynamic enemies, testing my skills and strategy in the game.

## Technology Stack

- C
- SDL2

## Contributors

- [David Macharia

![Game introduction video](3D_maze_intro.mp4)

## License

This project is licensed under the [MIT]. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [SDL2 Documentation](https://wiki.libsdl.org/)
- [C Programming Tutorial](https://www.learn-c.org/)
