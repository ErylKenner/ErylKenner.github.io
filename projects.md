---
layout: default
title: Eryl Kenner
---
# Projects

Here are a few of my more developed projects. Other side projects can be found on my <a href="https://github.com/Eryl2000">GitHub</a>.
<br><br>
<hr>

<h2>Space Age</h2>
Space Age is a space themed local co-op game that three friends and I built over the course of 24 hours for the 2019 Reno's Biggest Little Hackathon event. It is a two-player game where you must constantly manage the Gunner, Pilot, and Repair systems to survive as long as possible. Each player can only control one system at a time, so cooperation, planning, and sometimes a little bit of quick decision making are key.

The Pilot navigates a hazardous map of procedurally-generated asteroids and enemies. The Gunner controls the ship's powerful laser and shoots down enemy ships, but has no control over the movement of the ship. The Repairman sprints around the ship fixing damaged systems before they go offline. Enemies get stronger and more dangerous over time.

The game was written in Unity using C# with three other teammates. I wrote the enemy ship AI and kiting behaviors, which took into account relative position, speed, game length, and several other factors to make sure the enemies felt "strong" but were still beatable with skill. I also developed the procedural terrain generation we used for asteroids, as well as the wave spawning mechanics of enemies. I also contributed to the map design and overall game planning.
<img class="project_image" src="/assets/images/space-age.png" width="560" height="315">
<a href="https://github.com/kylebrain/hackathon-2019">GitHub Repository</a>
<br><br>
<hr>

<h2>Leviathan</h2>
It is important for naval officers to quickly determine what type of ship they are looking at, as well as its relative angle to their own ship. This is fairly straighforward process during daytime, but at night they need to use the lights hung up around the other ship to deduce these characteristics. This is such a common task that there is a standard in place for this purpose. This project is a virtual reality simulation made for the Vive SteamVR System for training naval officers this standard. 

There are two different modes the simulation can run in. In sandbox mode, players can place ships of their choosing, change ship orientation, change the time of day, and change the distance to the ship. This helps players understand how different ships look at different angles and at different light levels. At night, ships are almost impossible to see directly, so players must use the lights present on the ship to determine its class and orientation quadrant. Once a player feels ready they can enter quiz mode, which tests their knowledge in a variety of scenarios and in several levels of difficulty.

The project was written in Unity using C# using the SteamVR tool to help manage Vive communication. Below are videos of the project in action.
<iframe width="560" height="315" src="https://www.youtube.com/embed/u38aZBRUzsU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/yzTdZjPLN1Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
<hr>

<h2>Evolutionary Solver</h2>
Evolutionary Solver has been a long-term passion project of mine which I began after first learning about genetic algorithms. It uses a population of randomly generated neural networks to learn to play games as well as possible. So far I have added tic-tac-toe and <a href="https://en.wikipedia.org/wiki/Ultimate_tic-tac-toe">Ultimate tic-tac-toe</a> as playable games. Although tic-tac-toe is fully solvable using algorithms such as minimax, the goal of this project is to be a fairly generalized way of learning to play a game. The AI knows nothing about the rules of tic-tac-toe, and does not perform any DFS. It simply creates populations of random neural networks, has them play games against each other, and repopulates its players using the ones who did best.

This works even better for more complex games, such as Ultimate tic-tac-toe. In that game, your move affects the available moves your opponent has, meaning the game cannot easily be solved using DFS because it is hard to find a good heuristic for the strength of a board position. Therefore, a random exploration of the search space (which is essentially what a genetic algorithm is, just slightly more intelligent) works better than most methods for learning that game.
 
I wrote all the code for this from scratch in C++ (except for Eigen, which is a linear algebra library).
<br>
<a href="https://github.com/Eryl2000/EvolutionarySolver">GitHub Repository</a>
<br><br>
<hr>

<h2>Planet Ball</h2>
Winner of the games category for the 2018 Reno's Biggest Little Hackathon event. This is a fast-paced competitive arcade game where players knock a big ball into their opponent's goal. The difficulty is that you cannot directly control your own movement. Instead, you are tethered to a planet which you orbit around. You can release your tether at any time to go flying in a straight line, bouncing off the walls continuously, until you choose to re-tether to a new (or the same) planet. By timing your releases and re-tethers from planets you can propel yourself with great speed at the ball and hopefully score it into your opponent's goal. The first to score three balls in their opponent's goal wins!

To help you navigate, you also have two powerful cooldown abilites: Boost and Iron. Boost increases your speed for a short duration, making it much easier to score the ball or dodge your opponent. Iron increases your mass for a short duration, making your hits pack much more punch. Good management of these abilites can give you total map control.

The game was written with a friend over the span of 24 hours in Unity using C#. I wrote the grapple physics and tether connection/separation code, which were the core meachnics of the game and took many iterations of fine-tuning before they felt fun. I also worked on several small QOL features, such as the ability to change tether length, player interactions with other players, and particle effects for a variety of actions. I also worked on map design and overall game design.
<img class="project_image" src="/assets/images/planet-ball.png" width="560" height="315">
<a href="https://github.com/Eryl2000/Planet-Ball">GitHub Repository</a>
<br><br>
<hr>

<h2>Ninja Apocalypse</h2>
Ninja Apocalypse is a game I made with two friends for our game design class. It is a stylized top-down survival shooter, where you survive increasingly stronger waves of ninjas using guns found throughout the map. Each gun starts with a limited amount of ammo, meaning when a gun runs out of ammo it cannot be used anymore and must be discarded. However, weapons can be thrown at an emeny to 1-shot it.

If the you survive enough rounds, you are transported to a boss arena where a powerful boss will try to defeat you. If you manage to survive, you will be sent to the final map. The game ends when you die.

The game was written in C++ using a custom game engine built off of the Ogre graphics engine. I implemented a rigid-body collision system which handles collisions and queues callback functions for hit detection. I created both rectangle and circle colliders for this system. I also added staticly mapped terrain path-planning so enemies can navigate arbitrary maps. This makes adding additional maps simple.
<br>
<a href="https://github.com/Eryl2000/Ninja-Apocalypse">GitHub Repository</a>

