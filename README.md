``Reupload project from 2014 : This project was recovered so don't take commits into accounts``

<h1 align="center">🐍 Snake SDL 🐍</h1>
<p align="center">
   <a href="https://fr.wikipedia.org/wiki/C%2B%2B"> 
        <img src="https://img.shields.io/badge/C++17-%204--2--1?style=for-the-badge&label=language&color=blue">
    </a>
    <a href="https://fr.wikipedia.org/wiki/Simple_DirectMedia_Layer"> 
        <img src="https://img.shields.io/badge/2--0--9-SDL%204--2--1?style=for-the-badge&logo=SDL&logoColor=white&label=SDL%20version&color=darkblue">
    </a>
  
</p>

<p align="center">
 <img  src="https://i.ibb.co/rdCj8Lp/ezgif-2-fe1efe54b0.gif">
</p>


## Overview
This project is a C++ implementation of the famous [Snake Game](https://en.wikipedia.org/wiki/Snake_(video_game_genre)) using SDL.

## Run it
The github file already provide the ``.exe`` and a ``binary linux file`` just double click on the file regarding your OS

You can also open a terminal and run ``make run`` at the root of the project

## How to play
Arrow -> Turn the snake

The rule are simple, eat the white square to grow and avoid touching edge of the screen or your own tail and go as far as you can


## Build the project
If you want to build the project you can follow the steps below :

- Ensure you have ``GCC`` installed
- ( For ``Windows`` users install ``MinGw`` )
- Download [SDL-2.0.9](https://sourceforge.net/projects/libsdl/files/SDL/2.0.9/)
- Open the Makefile and set the var ``SDL_FOLDER`` at the path where your SDL folder is
- And then just run ``make compile`` (`` MinGw32-make compile``  for windows users ) command this will replace the binary in the output folder that match your OS
- Then you can launch the app or run ``make run``  


Note : Build with G++11.4.0 using SDL-2.0.9
