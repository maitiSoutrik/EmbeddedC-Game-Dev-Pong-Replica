# Handheld video game system

#### Things required :
* 1 TI MSP-EXP432P401R Microcontroller
* 1 Educational BoosterPack MKII
* 1 USB 2.0 A to Micro B Cable
* Code Composer Studio running on either Windows or Mac
---

#### How to build and run the game
1. Clone this repository into your current workspace
2. Open Code Composer Studio with your current workspace as your path
3. Go to File>Open project from file system
4. Add the github repo directory in the import field
5. Code Composer Studio will recognize the project and add it to the workspace.
6. Build the project and start debugging to flash the game onto the MSP432 MCU.
___

#### Motivation :
In order to understand how Embedded systems work, this project was taken up.
Furthermore learning video game development by writing replicas of old legacy games help us understand how a computer generates graphics and processes information even with constrained resources.

---


#### Gameplay
![alt-text](https://github.com/maitiSoutrik/EmbeddedC-Game-Dev-Pong-Replica/blob/master/images/gameplay.gif)
#### Future Work
* Implement multithreading using RTOS
* Improve AI logic and make the game faster
---
#### References :
1. Forked from [Git Repo](https://github.com/obergog/MSP432_Game_System)
2. Pong replica in C++ from this [Youtube Tutorial](https://youtube.com/playlist?list=PL7Ej6SUky135IAAR3PFCFyiVwanauRqj3)
3. MSP432 Technical Reference Manual
4. BoosterPack user guide