# 2020: Survival
## Abstract
The main idea of the game is to navigate through multiple levels of this game without catching COVID virus. A player enters each level outside of a building, with a mask on and fully sanitized. Once the game starts, the player has to navigate through a map to reach entrance of another building. As the player progresses through the level, they have to dodge various particles of viruses in the air (whose occurrence depends on how populous the environment is). In case they encounter a virus once, they lose their mask. When they encounter the virus again, they lose health points and eventually get infected (loose the game). The player can find sanitizer stations and masks along the way at a few places to restock and replenish their health. The end goal is for the player to reach the finish point with a mask on and with a threshold health level.

## Game Rules
- Ojective of the player is to reach FINISH, from START, of the level with a mask on and threshold health
- If the player loses health completely, game is lost
- Player is presented with a map in very level and has to choose a path to navigate through
- Every path has direction arrows to point the way for the player
- Sanitizer restores some health for the player by killing virus they come in contact with
- Masks help players not get infected, they disappear when in contact with virus
- Players can find Mask stands and Sanitizer stations along their path
- Players may encounter other people along the way
- They occurrance of other people will cause more virus particles to appear in the vicinity
- Other people may be masked or unmasked, the appearance of the virus particles around them increases when they are unmasked

## Initial Design Sketches
### Start Screen
This screen has options the playes can select to do the following:
- Start the Game
- Resume the Game
- Exit/Quit the Game
- View Score
- View Rules/Instructions
- Sound Settings

### Demo
The Demo gives the player an idea of how to play the game, it is automated and the player does not need to do anything. It displayes rules and descriptions of various and all elements of the game.

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Demo.jpeg)

### Beginner Level
This level shows the map from West Hall to Computer Science Building at Texas Tech University. In this level, there are a lot of Sanitizer stations and Mask stands. There are no other people in this level. The appearance of virus particles depend on how the population flow is in that area.
Here is the sketch of initial design of the level.

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Beginner%20Level.jpeg)

### Intermediate Level
This level shows the map from West Hall to Student Union Building at Texas Tech University. In this level, there are a lot of Covid virus and less Sanitizer stations and Mask stands. There are other people such as students in this level. The appearance of virus particles depend on how the population flow is in that area.
Here is the sketch of initial design of the level.
![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Medium_VR.png)

### Expert Level
This level shows the map fom West Hall to Media and Communications building at Texas tech University. In this level, we increased the population, virus and decreased sanitizers and mask stand to level up the game. Sketch of this level is given below.

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/ExpertLevel.png)

## Mid Review Presentation Roles
- Vamsi: Introduction, Abstract, Game Rules
- Rohith: Start Screen, Demo, Beginner Level, Intermediate Level, Expert Level
- Nikhila: Team Roles
- Karishma: Questions

## Changes due to time constraints
Due to the limited time contraint we have stick to only one level of the game where the player has the chance to select either one of two different levels namely, Safe and Risky. We have changed the evironment from Tech campus to a park to make it more universal and to have a broader reach and not just for Tech students and also for children.

## Why is this informative?
This game helps the player understand the covid conditions and helps one to gain precationary measures such as a wearing a mask and also about sanitization. This game can  especially children to have an understanding of the covid situations in a better way, and how they can be safe while taking the necessary precautions.


## Final Contributions
- Nikhila: Terrain Design, Healthbar Design and Camera Settings.
- Rohith: Assets Collection, Model designs and Report.
- Karishma: UI Design, Safe path and Report.
- Vamsi: Scripting, Risky path and functionality.
