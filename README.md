# Asteroids Game (C++ / SFML)

## Overview

A classic Asteroids-style arcade game built using C++ and SFML. The game includes real-time movement, shooting mechanics, asteroid spawning, and collision detection.

## Features

- Player-controlled spaceship with rotation and thrust
- Shooting system with bullets
- Random asteroid generation
- Collision detection system
- Score tracking
- Increasing difficulty over time
- Smooth 2D rendering using SFML

## Technologies Used

- C++
- SFML (Simple and Fast Multimedia Library)

## Project Structure
SpaceShooterGame/
│
├── Debug/
│   └── x64/                          
│
├── Assets/                        
│   ├── font.ttf
│   └── shoot.wav
│
├── score.dat                      
│
├── Source Files/                   
│   ├── Main.cpp
│   ├── Game.cpp
│   ├── Player.cpp
│   ├── Asteroid.cpp
│   ├── Bullet.cpp
│   └── Physics.cpp
│
├── Header Files/
│   ├── Entity.h
│   ├── Game.h
│   ├── Global.h
│   ├── Player.h
│   ├── Asteroid.h
│   ├── Bullet.h
│   └── Physics.h
│
├── Project Files/
│   ├── SpaceShooterGame.sln          
│   ├── SpaceShooterGame.vcxproj     
│   ├── SpaceShooterGame.vcxproj.filters
│   └── SpaceShooterGame.vcxproj.user
│
└── README.md

## Controls

Left Arrow - Rotate left  
Right Arrow - Rotate right  
Up Arrow - Thrust forward  
Space - Shoot  
Escape - Exit game  

## Installation

### Install SFML

Linux (Ubuntu/Debian):
sudo apt-get install libsfml-dev

Windows:
Download SFML from https://www.sfml-dev.org/download.php  
Then link it with your compiler (MinGW or Visual Studio)

## Build Instructions

mkdir build  
cd build  
cmake ..  
make  

## Run Game

./AsteroidsGame  

## Game Logic

- Spaceship uses velocity-based movement with inertia
- Asteroids spawn randomly and move across the screen
- Bullets have a limited lifetime
- Collision detection uses hitboxes
- Large asteroids split into smaller ones when destroyed

## Future Improvements

- Sound effects and background music
- Main menu system
- Pause and restart system
- Power-ups (shield, rapid fire, etc.)
- Particle explosion effects
- High score saving system

## Author

Ayman Shaheen
