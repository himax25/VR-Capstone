# VR Capstone Project, Virtual PingPong Game Overview
This is the final capstone project for High Immersion Unity with VR Development Nanodegree, called Virtual PingPong Game. 
![screenshot](https://github.com/himax25/VR-Capstone/blob/master/Screenshots/VRCapstoneGame_Screenshot0.JPG)

## Description:
The theme of this VR capstone project is emotionally touched by a joyful sports game, Virtual PingPong, with 6DoF locomotion. 
I am trying to build up how to make a game with Fitness Training in VR domain. 
This might be the first try for High Immersion Unity with VR development as a FT game.

## Persona: a typical user
I assume the target audience of this Virtual PingPong Game as the followings:
* **Hilary Lee**, 12, a Girl, Middle School student.
> Hilary is very excited to try on such new device based game,  High Immersion HMD VR, to play at these days. 

## Game Control
Oculus' Rift Touch Contorller based movements supports.
* Left Controller: control locomotion and hit the ball.
>> <li><b>Trigger button</b> hold & release: Hit the ball by the left hand to head to the target. </li>
>> <li><b>Grab button</b> holdding: Walking locomotion to the left direction. </li>
>> <li><b>A button</b> press: Tune on the menu. </li>

* Right Controller: control locomotion and hit the ball.
>> <li><b>Trigger button</b> hold & release: Hit the ball by right hand to head to the target. </li>
>> <li><b>Grab button</b> holdding: Walking locomotion to the right direction. </li>
>> <li><b>X button</b> press: Tune off the menu. </li>

* Voice Control: using a game item by calling massage.
>> <li><b>Say "Max"</b> during playing game to make the one step bigger room when the player is in danger.</li>

## How to play the Game
1. The player should defence the behide wall from bouncing balls in the game room by 2 hands.
2. The player should defend behind the wall from re-bouncing balls in the game room with two hands.
3. The game room will be getting narrower from the left and the right sides if the player got failed 
 to defend these bounced balls from bounding.
4. The game room will be getting bigger back at both sides if the player either grabs the golden ball or says "Max".
5. Saying "Max" to use the game item, which is only available 3 times in playing.
![youtubelink](https://github.com/himax25/VR-Capstone/Screenshots/YouTubesitelink.JPG)
[for playing Youtube video here](https://youtu.be/Wb9o5GQAqC8)

# Design of this project
![screenshot](https://github.com/himax25/VR-Capstone/blob/master/Screenshots/GameScenarioSketch.JPG)

## Building up Virtual PingPong game mechanism, Features and Dependencies: 
1. 3D Models for 2 hands local avatars to play the game.
2. Cube Skybox for game room with Obstacle brick walls.
3. Recording the highest score on the local computer.
![screenshot](https://github.com/himax25/VR-Capstone/blob/master/Screenshots/VRCapstoneGame_Screenshot1.JPG))

## The Virtual PingPong Game Loop
The game consists of 4 stages; Tutorial stage, Level 1, Level 2, and Level 3. It also shows a calculated score 
which consumed player physical movement calories with the survival time on the scoreboard. 
* In the Tutorial stage, teaching how to defend coming balls from rebounding with two hands.
* Each level has some challenging obstacles with structures to make some difficulties on the game for the player.

## Other Effects
1. Particle Effects on ball coming & ball re-bouncing from walls.
2. Sound FX Effects for bouncing.
3. Background Music for playing.
4. Random Obstacle brick wall to come out from the each wall as the game difficulties.
5. Spawning 2 balls from 1 ball after bouncing from the special keystone wall.

## Training Room
* Set up the ball throwing position to get ready to play the game by the locomotion transform.
* Throwing a ball to hit the target thru bouncing walls.
* Say "Ok go" to play the level 1.

## Level I

## Level II

## Level III

## The target platform for this capstone project
The target platform of this project is Oculus' Rift with Touch controllers.

# Optimizing of this Virtual PingPoing game
## Tuning up the performance and game design
1. Maintain Target Device Frame rate as 90 FPS.
>> 90 FPS 스크린샷 그림.
2. Applying Anti-Aliasing as MSAA 4x.
>> MSAA 스크린샷 그림.
3. Applying 3 spatial audio clips.
>> 오디오소스 스크린샷
4. Applying an interactive experience  
>> 플레이어가 선택하는 입력이 필요.

# Conclusion
## Lesson and learning from this Capstone project.
It is a pretty tough o..........

## **Author of this coding**
* Hyo Lee, linkedin [here](https://www.linkedin.com/in/hyomaxlee/)
 
## Versions
- Unity 2017.2.0f3
- GVR Unity SDK v1.60.0
- Oculus Utilities v1.25.1 
- OVRPlugin v1.27.0 & Bundled version 1.14.1 
- Oculus Avatar SDK v1.28.0
- Test Platform: Windows 10 Home Edition 64 Bit OS /w Oculus Rift HMD

## Free Assets to download from online Store for this game. 
- ownload Oculus SDK Package v1.27.0 and v1.28.0 from Oculus website;
>> (1) Oculus Avatar SDK and Oculus Integration SDK scripts for OVRPlayer Controllers and OVRCameraRig
- Download Background Music from Unity Asset Store;
>> (1) Absolutely Free Music, Vertex Studio
