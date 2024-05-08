## Maze
![The Maze ](https://github.com/KamoEllen/Game-3D-Maze/blob/main/game.png)

# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world! this is a portfolio project for Holberton School.

The Maze was written was written in C ussing SDL2 library. Deveploment was performed using Ubuntu 20 LTS

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Instalation 
```sh
$ git clone https://github.com/KamoEllen/Game-3D-Maze.git
```
## Collaborators
* Kamogelo Ellen Kganakga

## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera around (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/t0MxNni.png)


## Demo
[![The Maze Demo](https://github.com/KamoEllen/Game-3D-Maze/blob/main/game.png)](https://www.youtube.com/watch?v=sp3uA6rvSjw)
