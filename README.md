## Introduction

<p align="center">
  <a href="https://github.com/brandonconcepcion">
   <img src = assets/splash.png alt="MasterHead" width="750"/>
  </a>
</p>


I Used Object Oriented Programming (OOP) to implement 13 defensive units for a tower defense game I call **Colony Chronicles: Bee Gone**. I worked on this project when I took COMPSCI 61A: "Structure and Interpretation of Computer Programs" at UC Berkeley. A demo of the final game can seen [here!](https://youtu.be/noZKTQ23QBs)

<table>
  <tr>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_fire.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_laser.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_wall.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/bee.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_queen.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_hungry.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_shortthrower.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_scary.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_harvester.gif>
    </td>
    <td valign="middle" align="left" width="10%">
        <img src = assets/insects/ant_ninja.gif>
    </td>
  </tr>
</table>


This game takes inspiration from PopCap Games' [Plants Vs. Zombies](https://www.ea.com/games/plants-vs-zombies/plants-vs-zombies#description). 

## The description of the **Colony Chronicles: Bee Gone** is as follows: 

As the ant queen, you populate your colony with the bravest ants you can muster. Your ants must protect their queen from the evil bees that invade your territory. Irritate the bees enough by throwing leaves at them, and they will be vanquished. Fail to pester the airborne intruders adequately, and your queen will succumb to the bees' wrath.


## The Game
A game of Ants Vs. SomeBees consists of a series of turns. In each turn, new bees may enter the ant colony. Then, new ants are placed to defend their colony. Finally, all insects (ants, then bees) take individual actions. Bees either try to move toward the end of the tunnel or sting ants in their way. Ants perform a different action depending on their type, such as collecting more food, or throwing leaves at the bees. The game ends either when a bee reaches the end of a tunnel (you lose), or the entire bee fleet has been vanquished (you win).

## Files
The files I worked on in this project include were:

* `ants.py`: The game logic of Ants Vs. SomeBees
* `ants_gui.py`: The original GUI for Ants Vs. SomeBees
* `graphics.py`: Utilities for displaying simple two-dimensional animations
* `utils.py`: Some functions to facilitate the game interface
* `ucb.py`: Utility functions for CS 61A
* `assets`: A directory of images and files used by `gui.py`
* `img`: A directory of images used by `ants_gui.py`

## Playing the Game
The game can be run in two modes: as a text-based game or using a graphical user interface (GUI). The game logic is the same in either case, but the GUI enforces a turn time limit that makes playing the game more exciting. The text-based interface is provided for debugging and development.

To start a text-based game, run
```sh
$ python3 ants_text.py
````
To start a graphical game, run
```sh
$ python3 gui.py
````
    usage: ants_text.py [-h] [-d DIFFICULTY] [-w] [--food FOOD]
    
    Play Ants vs. SomeBees
    
    optional arguments:
      -h, --help     show this help message and exit
      -d DIFFICULTY  sets difficulty of game (test/easy/medium/hard/extra-hard)
      -w, --water    loads a full layout with water
      --food FOOD    number of food to start with when testing

<img src = assets/new-ants-gui.png>

### Project Spec
[Spring 2023 Implementation](https://inst.eecs.berkeley.edu/~cs61a/sp23/proj/ants/)

### Acknowledgements
Acknowledgments: Tom Magrino and Eric Tzeng developed this project with John DeNero. Jessica Wan contributed the original artwork. Joy Jeng and Mark Miyashita invented the queen ant. Many others have contributed to the project as well!

The new concept artwork was drawn by Alana Tran, Andrew Huang, Emilee Chen, Jessie Salas, Jingyi Li, Katherine Xu, Meena Vempaty, Michelle Chang, and Ryan Davis.
