# SunnyLand 1.0

Developed by Alexander Philippopoulos

Artwork and music by Ansimuz

# Description
SunnyLand is a 2D platformer made with the Unity game engine. The goal of the game is to go through different levels while avoiding enemies and collecting gems. As of now, there are only two levels, but I do plan on making more in the future. Any feedback is appreciated. Have fun playing.

![image](https://github.com/ajax815/SunnyLand-1.0/assets/161390808/4e4cb9e6-9da9-4bf5-89b0-6df5b5bb86a8)

![image](https://github.com/ajax815/SunnyLand-1.0/assets/161390808/c9574c5d-cf79-45c3-8417-1309dd7ab592)

![image](https://github.com/ajax815/SunnyLand-1.0/assets/161390808/7ac7cb2e-9a8c-4398-ba86-d7d2d5326f82)

![image](https://github.com/ajax815/SunnyLand-1.0/assets/161390808/2e179da9-4627-4d8f-8ac7-7a1afcd247be)

![image](https://github.com/ajax815/SunnyLand-1.0/assets/161390808/42d7de29-4830-45f2-a7ed-8dc49015b1b0)

# Controls
Move Left: A

Move Right: D

Duck: S

Climb Up Ladder: W

Climb Down Ladder: S

Jump: Space

Double Jump: Space 2x


# Programming
All the games programming and design was done by me. I used the C# programming language with the Visual Studio IDE to create the dynamic aspects of the game.

I programmed a script for allowing user input to control the player character, utilizing input mappings from Unity's input system. I also programmed scripts for enemies to roam around. The frogs were specifically programmed to jump after a certain interval. The pigs, beetles, opossums, and bats were all programmed to run side to side. I used interfaces to have a clean architecture with my code.

I implemented mechanics to further enhance the flow of the controls, such as a double jump and ducking. There are many platforms that do not incorporate double jump, which makes for sloppy gameplay and frustration. A double jump always makes up for platforms that are just to long for a single jump. The ducking mechanic was added to allow the player to avoid flying enemies, such as beetles and bats.


# Design
I designed the levels using tile maps, and the UI using the canvas tool. 

Tile maps are a feature in Unity that allow for the use of tile-based map assets. The asset pack I used contained tiles, in which I used to create the maps for the level. I used colliders to add collision for the tiles, so that the player would collide with floor and wall tiles. I added overlaps for the ladder tiles, so that the player can climb up the ladder tiles. 

The canvas tool is a feature in Unity that allows for the creation of UI. The UI displays the total number of lives the player has, as well as the total number of gems the player has collected. The goal of the game is to complete the level, while also acquiring as many gems as possible. 

# Artwork and Music
The artwork and music is not owned by me. The respectable owner of the games art and music is Ansimuz. I got all his art and music from his free asset pack.

https://assetstore.unity.com/packages/2d/characters/sunny-land-103349/reviews?sr...


# Download Instructions
1. Select "Code" on the upper right and then select "Download ZIP"
2. Once downloaded, right click on the zipped folder and click "Extract All"
3. Open the extracted folder and click on "SunnyLand.exe"
4. Play the game


# Source Code
https://github.com/aphilippopoulos248/My_Platformer/tree/main
