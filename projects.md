---
layout: default
title: Eryl Kenner
---
# Projects

Here are a few of my developed projects. Other side projects can be found on my <a href="https://github.com/Eryl2000">GitHub</a>.
<br><br>
<hr>

<h2>Space Age</h2>
Space themed local co-op game where two players must manage three subsystems while trying to survive as long as possible. The three subsystems are Gunner, pilot, and Repair, but each player can only control one at a time. The Pilot navigates a hazardous map of procedurally-generated asteroids and enemies, the Gunner shoots down enemy ships, and Repair sprints around the ship fixing damaged subsystems before they go offline. Enemies get stronger and more dangerous over time so decision-making and teamwork are key.

The game was written in Unity using C# with three other teammates over the span of 24 hours for the 2019 Reno's Biggest Little Hackathon event. I wrote the enemy's AI and kiting behavior, the procedural terrain generation, wave spawning mechanics, some of the map designs, and helped with overall game design.
<img class="project_image" src="/assets/images/space-age.png" width="560" height="315">
<a href="https://github.com/kylebrain/hackathon-2019">GitHub Repository</a>
<br><br>
<hr>

<h2>Leviathan</h2>
Virtual reality simulation for the Vive SteamVR System that teaches naval officers to determine ship type and angle using ship lighting. Tests their knowledge using a quiz mode implementing a variety of scenarios. Written in Unity using C#.
<iframe width="560" height="315" src="https://www.youtube.com/embed/u38aZBRUzsU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="560" height="315" src="https://www.youtube.com/embed/yzTdZjPLN1Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
<hr>

<h2>Evolutionary Solver</h2>
Created a genetic algorithm which uses a population of neural networks to learn to play games. Written from scratch in C++. Currently Tic-tac-toe and <a href="https://en.wikipedia.org/wiki/Ultimate_tic-tac-toe">Ultimate tic-tac-toe</a> are implemented as games. This has been a long-term passion project of mine which I began after first learning about genetic algorithms.

While tic-tac-toe is fully solvable using algorithms such as minimax, a player's move in Ultimate tic-tac-toe affects the available moves an opponent has, meaning the game cannot easily be solved using DFS (partly because it is hard to find a good heuristic for the strength of a board position). My approach therefore does not attempt to fully solve the game. Instead it learns to find acceptable moves through a random exploration of the game space.
<br>
<a href="https://github.com/Eryl2000/EvolutionarySolver">GitHub Repository</a>
<br><br>
<hr>

<h2>Planet Ball</h2>
Winner of the games category for the 2018 Reno's Biggest Little Hackathon event. A fast-paced competitive arcade game played on a single computer where players knock a big ball into their opponent's goal. Players cannot directly control their own movement, however. Instead, they are tethered to pivots and can grapple to new pivots throughout the map, then time their release from the pivot to propel themselves forward. The first to score three balls in their opponent's goal wins!

Players also have two powerful cooldown abilites, Boost and Iron. Boost increases the player's speed for a short duration, while Iron increases the player's mass for a short duration. Good management of these abilites can allow players to skillfully block shots or quickly launch across the map to score a goal.

The game was written with a teammate over the span of 24 hours in Unity using C#. I wrote the grapple physics, tether connection/separation mechanics, the changing of tether lengths, and player interaction with other players on the same pivot. I also helped design maps and helped with overall game design.
<img class="project_image" src="/assets/images/planet-ball.png" width="560" height="315">
<a href="https://github.com/Eryl2000/Planet-Ball">GitHub Repository</a>
<br><br>
<hr>

<h2>Ninja Apocalypse</h2>
Stylized top-down survival shooter. Survive increasingly stronger waves of ninjas using guns found throughout the map. Each gun starts with a limited amount of ammo. When a gun runs out of ammo it cannot be used anymore, however it can be thrown at an emeny for a 1-shot as its final attack.

If the player survives enough waves, they will be transported to a boss arena where a powerful boss will try to defeat them. If they manage to survive the terrible monster, they will teleport to the final map. The game is then infinite as the player tries to survive as long for as possible.

The game was written in C++ using a custom game engine built off of the Ogre graphics engine. I implemented a rigid-body collision system which handles collisions and queues callback functions. Rectangle and circle colliders are implemented currently. I also added static terrain path-planning so enemies can navigate arbitrary maps. This makes adding additional maps simple.

