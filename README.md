# 2020: Survival
## Abstract
The main idea of the game is to navigate through a terrain without catching COVID virus. A player enters the game at the begining of the terrain with a mask on and fully sanitized. Once the game starts, the player has to navigate through the terrain and reach a crossroad, at which a player can deciede if they want to choose a risky path or an easy path to reach the finish. As the player progresses through the terrain, they have to dodge various particles of viruses in the air (whose occurrence depends on how populous the environment is). In case they encounter a virus once, they lose their mask. When they encounter the virus again, they lose health points and eventually get infected (loose the game). The player can find sanitizer stations and masks along the way at a few places to restock and replenish their health. The end goal is for the player to reach the finish point.

## Game Rules
### Player:
- Main objective is to navigate from start to finish with mask and threshold health.
- The game is lost when the player loses complete health.

### COVID Virus Particles: (Loses 50 Points from health)
- Negates mask mask upon contact
- Depletes health of player 

### Route:
- Navigation path selected by the player from the available options on the map to reach finish 

### Direction arrows:
- Show players how to navigate the map once route is selected 

### Masks: (Saves once from COVID virus)
- Supplies masks to players 
- Masks can protect players from being infected / attacked
- Appearance decreases as the risk go up 

### Sanitizer station: (Adds 30 points to health)
- Sanitizer kills virus and Replenishes health
- Lets player sanitize
- Appearance decreases as the risk go up

### Other people:
- Act as obstacles, as they're surrounded by a lot of virus particles

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

## Changes in the idea
Initially we had a different idea for this project and were thinking around TTU campus. After some discussion, we decieded to go with something different. The final idea focuses on being an educational tool, especially for kids, to understand the safety regulations of COVID pandemic. Also, for a broader reach, we have implemented a more common terrain for an environment. To give it a more realistic and relatable aspect, we have implemented a risky path (representing busy streets) and a safer path (representing low populated areas)

## Checking the boxes
- Innovative and Transformative: Represents a good educational tool for children to grasp COVID safety guidelines
- Educating: Brings understanding on the COVID safety guidelines (Masks, Sanitize frequently, Social Distancing)
- Interesting: Dodging bad guys is fun for kids! (cue: PacMan)
- Visual appealing: We thought it was cute, did you?
- Sound effects: We have them too!
- Usability: It can be used as an educational tool and it is pretty simple to use too!
- Technical challenges: Bringing together elements that worked perfectly, independently, was hard.
Making the virus particles move was a challenge.
Scripting health, virus and masks was a bit of a challenge
- Effort: We went through a thousand tutorials to figure out Unity!
- Teamwork: We hit a dead end with Unity Teams (Not enough ram on some of our laptops for Unity to run smoothly), so we had to work on one single laptop and we made it work. If that doesn't say teamwork, I don't know what will.

## Game Overview:
We have made a few changes to the idea that we initially proposed, So the player has to start from a initial point to the final destination dodging various COVID particles that come along the players way. Whenever the player encounters with a covid particle they lose a significant part (50%) of their life and it can be shown on the healthbar above the player. Also for the first time when the player encounters the covid he loses the mask, and the mask on present near the healthbar disappers from the game, and whenever the player reaches a sanitizer he/she boosts their health by 30%, and also during the course of the game the player can also acess the masks present in the game environment.

## Sneak Peek 

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.54.40%20PM.png)
The above is the first screen of the Game. Contains the Main Menu

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.55.19%20PM.png)
The above is the Options Screen

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.55.39%20PM.png)
The above is the Help screen

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.57.07%20PM.png)
The above is a peek on how the Demo looks like

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.58.36%20PM.png)
The above is an another look at Demo

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.59.27%20PM.png)
The above is what you see when you win!

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%203.59.35%20PM.png)
The above is what you see when you lose.

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%204.02.22%20PM.png)
The above shows the screen at START

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%204.06.13%20PM.png)
The above is the crossroad at which you can pick your path.

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%204.06.37%20PM.png)
The above shows a Sanitizer in the game

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%204.07.10%20PM.png)
The above shows a Mask in the game

![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/Screen%20Shot%202020-11-29%20at%204.18.44%20PM.png)
The above shows a peek at the risky path

The below shows the last part of the game
![Demo Design Sketch](https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/Screenshots/moving_viruses.gif)

## Final Contributions
- Nikhila: Terrain Design, Healthbar Design and Camera Settings.
- Rohith: Assets Collection, Model designs and Report.
- Karishma: UI Design, Safe path and Report.
- Vamsi: Scripting, Risky path and functionality.

## Mid Review Feedback
- This sounds like a Mario VR. Do the virus move? Are the masks hidden?
-> PacMan was kind of our inspiration. Some virus particles move and some don't. Masks are openly available and are not hidden.

- Are there any guidance on screen like a map Or how can we find or avoid items on the navigation paths? 
-> There are navigation arrow board to guide the player. Items are visible and have to be manually avoided by the player.

- Please make these clear and support users on navigating. Also, health status should be available. Are there any timer as in Super Mario?
-> Support for navigation is provided. Health status is available. There are no timers.

## Future Scope
- Including more levels in different settings
- Using voice as interface (speech recognition to select options)

## Useful Links
- Report -> https://github.com/karishmagarikapalli/VirtualReality_Project_2/blob/main/README.md
- Project -> https://drive.google.com/drive/folders/15Bq252rsLsoCRYnG0LidkUb7pIt6Bn24?usp=sharing
- Video Demo -> https://drive.google.com/file/d/1WdiV71jb3Wl1ecRUWXYECTvmZE7lBUmK/view?usp=sharing
- Safe Path -> https://drive.google.com/file/d/15cjYJG-8qBTEmrEbbXCPeCaGV3UVlK9Y/view?usp=sharing
- Risky Path -> https://drive.google.com/file/d/1Cp1-7d03s4DkP418RFhKsDFHbLp8S6e0/view?usp=sharing
- Youtube Link -> https://www.youtube.com/embed/9iHY3TClzcs
