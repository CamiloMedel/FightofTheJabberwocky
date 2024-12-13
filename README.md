# FightofTheJabberwocky
_Project for AET 358 Next Level Arcade, UT AUSTIN_ 

"You step into the role of Jerry, a misunderstood jabberwocky just trying to enjoy some peace in his forest home. But those ANNOYING villagers, knights, and—ugh—children just won’t leave you alone! Put on the jabberwocky mask and use your terrifying roar, visual cues, and audio cues to scare off those pesky humans."

# Teaser Trailer:
[![Teaser Trailer for Fight of the Jabberwocky](https://img.youtube.com/vi/UZWPnQezJ_s/0.jpg)](https://www.youtube.com/watch?v=UZWPnQezJ_s)

**Link: https://youtu.be/UZWPnQezJ_s?si=5T3AsC08QaiVsYYk**

# Game Description:
Transform into Jerry the Jabberwocky by putting on a controller mask with a built in microphone.  Along with that, three monitors surround you... each with approaching villagers. Be on the lookout as they want to end you! Yell and roar as loud as you can to scare them away. Step on one of three foot pedals as you roar to target your roar to one of the three screens. Each foot pedal corresponds with one screen. Before you roar, make sure the villagers are within Jerry's roar range by waiting for a white outline to surround the villager.

The strength of your roar determines the rate at which you lower villagers health. Kid villagers are fast but have the least health. While knights are slow and have the most health. Choose wisely for which screen you roar at if you get cornered by many villagers, as it may determine the fate of Jerry! One villager attack isn't enough to take you out though! Get hit by 3 villagers and you are out.

# My Role
I worked as a game developer in charge of the programming and technical sides of the project. I used the Unity engine with C# to create the foundations and structures of the game. Some structures I created or implemented include and are not limited to:
- Spawn Manager
- Phase System (morning, afternoon, evening phases)
- Enemy Controllers, Enemy Prefabs, Enemy Pathing and Movement System
- Multi-Display Compability,  Multi Screen Functionality
- Health System
- Microphone Input and Loudness Detection

Besided these structures, I also implemented audio and visual assets which I received from my fellow group members. I implemented the following type of assets:
- 2D Sprites (Enemy and Jerry sprites)
- 2D Animations
- 2D Effects (Enemy Outlines, Enemy UI Alerts)
- SFX (Water flowing, enemy dialouge)
- Music FX (Background music)
  
One key thing I did for the project involves setting up a version control system. I implemented Unity's version of version control, "Unity Version Control" for our project. This version control system allowed me and a 3D environment and modeling specialist on my team to collaborate on Unity outside of class time. We would work seperately on Unity as he made 3D asset changes, and I implemented my changes. We would then merge our changes together.

Outside of Unity, I configured a setup for the game to be played with usin 3 monitors, 3 screens, and one microphone.
![3 monitors, 3 screens setup](https://github.com/CamiloMedel/FightofTheJabberwocky/blob/main/SetupPreview.gif)

# Link To Project
**itch.io:** https://timmy-fan-club.itch.io/fight-of-the-jabberwocky

# Process Overview
For the project, we split our schedule into 3 main deadlines. A deliverable 1 deadline, deliverable 2 deadline, and a final project deadline. 
# Deliverable 1
For deliverable 1, I set up github as our version control system with Unity. I also created a simple health system:
https://youtu.be/UyGMCBMflY8?si=BneFXtxlZp1c9Y-Y 

Within this deliverable, I made the first version of the roar meter which detectcs the loudest noise heard from the microphone and then displays it onto a UI bar:
https://youtu.be/E1KcRlyE5lg?si=84fUT2KeXJhogK2a 

While working towards the deliverable, I had made a version of the roar meter where the player would have to charge up their roar and then release it.
https://youtu.be/RhmEmU02Z_c?si=SlyoUGBf5YIpe8vX 

This later got changed as we added foot pedals to determine which area the player would roar at. We went with this new direction as it felt that the player was not getting any direct feedback as they yelled to roar. I also added basic enemies in this deliverable. Pathing for this enemies was based on three layers of nodes. Back nodes, middle nodes, and front nodes. A enemy would choose one node from each layer at random, and would then move towards each node in each layer from back to middle to front and then to the player's position.

# Deliverable 2
For deliverable 2, I changed our version control system to the "Unity Version Control" system as it was becoming difficult to merge work done on the same scene. Unity Version Control made it easy to merge most changes, and it included a interface that didn't require us to leave Unity in order to push, pull, or check commit history. 

In this deliverable, I created a morning, afternoon, and evening cycle which included growing difficulty as the game progresses. I created morre difficulty by making enemies get faster over time and making them spawn in faster intervals overtime. I also focused on implementing audio and animation assets.

![image alt](https://github.com/CamiloMedel/FightofTheJabberwocky/blob/main/PhasesPreview.gif)

A major change I made for this deliverable is chaning enemy pathing. The previous version of pathing had an effect where enemies would be moving left to right and then towards to the player. I made a new version of pathing that includes pre-made paths which the enemy would choose one of the premade paths on randoms as they were spawned in. These premade paths allowed me to better control the movement of enemies. It also allowed me to create a effect where it seems that the enemies are running towards the player, and it allowed me to make the enemies avoid certain areas by setting the nodes in the premade paths to where I wanted to.

**Deliverable 2 Short Demo:**

[![Deliverable 2 Short Demo](https://img.youtube.com/vi/9FoYqBgRhcI/0.jpg)](https://www.youtube.com/watch?v=9FoYqBgRhcI)

https://youtu.be/9FoYqBgRhcI?si=iF5QYNEWfQC0bYw5 

# Final Project
Working towards the final project was mostly centered around polishing the feel of the game. I tuned the spawn manager to make the enemies come towards the player in rates that balance action and difficulty. I edited outlines that will surround the enemies as they are within the range of roaring to be more apparent. I also implemented a lot of 2D assets and UI assets. Me and my team also did a lot of testing with the three monitors and foot pedals to make sure we have it working, and to make sure that we have the correct hardware. 

**Final Project Gameplay Preview:**

[![Final Project Gameplay Preview](https://img.youtube.com/vi/GPHRbhCFqfc/0.jpg)](https://www.youtube.com/watch?v=GPHRbhCFqfc)

https://youtu.be/GPHRbhCFqfc?si=QVXZifkrglqDJ52c

**Link To Final Project:** https://timmy-fan-club.itch.io/fight-of-the-jabberwocky

