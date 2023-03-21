
# Come on！Build your spot

YouTube link：https://youtu.be/4lpnZrvU4Tw 

Game Project download link：https://drive.google.com/drive/folders/1GWJE7qeiMPFzgaEr75stVgRvGGeNx6gV?usp=sharing

Github Link：https://github.com/RunqiZhao21031188/Come-on-Build-your-spot-

<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(16).png" width="860px" height="500px" alt="lab00-01"/>
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(14).png" width="860px" height="500px" alt="lab00-01"/>

## Inspiration
During the group brainstorming, we took the daily life status and needs of the people around us as the key to the research, and found that most people feel the pressure of the environment and their own anxiety in the trivial daily life, and everyone is eager to seek a relaxing  Way.  One of our group members, undergraduate major was environmental design,she is more aware of the psychological effects of the environment. So that we came up with the idea of designing an interactive game with LeapMotion.  Its purpose is to enhance the understanding and communication between people and the environment, and relieve people's stress and anxiety in the environment.  Starting from this design concept that we agreed on as the key, we also agreed on the story of the characters and the cute and healing style of the game, and started our teamwork journey.


## Description

This is a game with a combination of unity and leap motion that has a building function through hand movements. In the game, the player can choose different scenarios. We have set up four scenes: kindergarten, office scene, park and community. Each scene is built and rendered by blender. Before each scene we interspersed dialogue to help the player immerse themselves in the scene. In the scenes we set up 10 different styles of modules that the player can grab and move through hand grasping movements and keyboard to achieve the module overlay function. We have also set up the button to add modules in each environment through c#, dropping modules in order according to the display show board in the scenes. In addition to the added module can be modify color by clicking on a button.

### 4 Scene
The game has four scenes, each corresponding to the content and environment of four different dialogues. Players are free to choose what they want to experience.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(18).png" width="860px" height="500px" alt="lab00-01"/>

#### 1.Park
The scene is set on an island and the player is blown by the sea breeze and enjoys the sound of water lapping on the beach. Players can experience the leisure and relaxation of a holiday in this scene.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(21).png" width="860px" height="500px" alt="lab00-01"/>

#### 2.Community 
In this scenario, the player is back at home, listening to birds and fountains.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(23).png" width="860px" height="500px" alt="lab00-01"/>
#### 3.Office
Downstairs in the office, players can build their own space with blocks. The scene has a weather simulation system. Under the night sky, covered with twinkling stars. Enjoy some quiet time to yourself after work.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(24).png" width="860px" height="500px" alt="lab00-01"/>
#### 4.Kindergarten
The player is free to roam and fiddle with blocks on the ground, with wind chimes playing in the background. The towering toys and lovely decorations around bring players back to their childhood memories and immerse them in the romance of childhood.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(25).png" width="860px" height="500px" alt="lab00-01"/>

During the design process, the visual effect of text appearing word by word in the dialog box took a long time, and we also encountered some difficulties in setting up the border of collider and camera view  . These problems were solved by learning from the videos and with the help of fellow students.
The game did not have a specific goal and the way it was played was defined by the players themselves. So in the exhibition, the participants hacked more ways for the game.



## Features
### Grab and build
The player can grab and move blocks by hands. Good hand capture results in a realistic simulation of physical interactions. The player can use blocks for any interaction.Build a block into a building, push a block into the ocean, throw a block into the distance, or bowl with a block. You can do anything if you want.
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(29).png" width="860px" height="500px" alt="lab00-01"/> 
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(34).png" width="860px" height="500px" alt="lab00-01"/>
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(35).png" width="860px" height="500px" alt="lab00-01"/>

### Talk with NPC
The player can listen to the character's dialogue for key information
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(19).png" width="860px" height="500px" alt="lab00-01"/>
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(20).png" width="860px" height="500px" alt="lab00-01"/>

### Add more blocks
If you want to build something bigger and you don't have enough blocks? You are free to add more blocks based on the order of the signage
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(22).png" width="860px" height="500px" alt="lab00-01"/>

### Players customize the block colors
Players can change the block color to their liking

Before

<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(32).png" width="860px" height="500px" alt="lab00-01"/>
After

<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(33).png" width="860px" height="500px" alt="lab00-01"/>

### Weather change system
In the Office scenario, we added a weather simulation system
<img src="https://github.com/RunqiZhao21031188/1/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE(36).png" width="860px" height="500px" alt="lab00-01"/>


## Division of the project
Team members：Lei Cao, Danhui Li, Yamin Li, Runqi Zhao(team's representative)

Planner：Runqi Zhao（Discover the theme and form of the game）, Lei Cao（Discuss interaction forms）

Modeling： Runqi Zhao（Scene of Park and Kindergarten）, Danhui Li（Scene of Office，Modeling of blocks）, Yamin Li（Scene of Community，Modeling of blocks）

Coding：Lei Cao（Add background image, background music and other functions in unity.Using c# in unity to complete the scene conversion.scene click events, dialog box effects and add modules and change the color of the modules),Runqi Zhao(Debug leapMotion parameters and devices, weather simulation)

Video Clip：Yamin Li（Homepage video）

Copy Writer: Danhui Li（Dialogue and looking for BGM）

## Support
Unity 2021.3f1
LeapMotion
Windows64bit

### What could we do better?
In making the game, we found that leap Motion wasn't as accurate as we'd hoped. Also, people don't feel comfortable using LeapMotion for the first time and don't interact well with it. In the future, we want to focus on optimizing the way LeapMotion interacts with games and finding an interactive game that is more playable and easy to play with LeapMotion

Before that we tried to make a narrative game and spent a lot of time on organising the story, characterisation, skeleton binding and mini-games demo. We changed the plan because of the amount of work involved, and we will continue to try later~


