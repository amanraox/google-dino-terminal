# Dino
This repository contains a rendering of the popular chrome dinosaur game on the terminal, in C++ and curses.

## Requirements

### CMake
You will need cmake to create and use the build system.

### ncurses library

You will need to install the ncurses library using the package manager available to you in your operating system.

Ubuntu:
`sudo apt-get install libncurses5-dev libncursesw5-dev`

Arch Linux:
`sudo pacman -S ncurses`

## Installation

To install this program, clone this repository onto your local machine using the following command:

`$ git clone https://github.com/amanraox/google-dino-terminal.git`

Once you have cloned the repository, you can navigate to the repository directory.

`$ cd google-dino-terminal`

Now just create build files by running following commands-

`$ cmake -S . -B ./build`
`$ cmake --build ./build`

![Screenshot from 2024-05-04 13-28-42](https://github.com/amanraox/google-dino-terminal/assets/67886237/c2b44a49-e24d-47f9-9b7e-6eefae2b67e8)

To Run the game, the build system should create a link to the running binary in the current directory so you should be able to run the game with the following command:

`$ ./dinosaur_game`

In case that doesn't work on your system, then GOD knows what to do, try figuring out whats the problem with build files. It works perfectly in my windows 11 and Debian 12

Enjoy!

## Credits

Thanks to [fundamelon](https://github.com/fundamelon/terminal-game-tutorial) and their terminal game tutorial for an intro to terminal game development.
