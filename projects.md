---
layout: default
title: Eryl Kenner
---
# Projects

Here are a few of my more developed projects. Other side projects can be found on my <a href="https://github.com/Eryl2000">GitHub</a>.

<h2>Space Age</h2>
Space themed local co-op game where two players must manage three subsystems while trying to survive as long as possible. The three subsystems are Gunner, pilot, and Repair, but each player can only control one at a time. The Pilot navigates a hazardous map of procedurally-generated asteroids and enemies, the Gunner shoots down enemy ships, and Repair sprints around the ship fixing damaged subsystems before they go offline. Enemies get stronger and more dangerous over time so decision-making and teamwork are key. The game was written with three other teammates over the span of 24 hours for the 2019 Reno's Biggest Little Hackathon event. It was written in Unity using C#. I wrote the enemy's AI and kiting behaviors, the procedural terrain generation, our wave spawning mechanics, some of the map design, and overall game design. Our repository can be found <a href="https://github.com/kylebrain/hackathon-2019">here</a>.
<img class="project_image" src="/assets/images/space-age.png" width="484" height="216">
<hr>

<h2>Leviathan</h2>
Virtual reality simulation for the Vive SteamVR System that teaches naval officers to determine ship type and angle using ship lighting. Tests their knowledge using a quiz mode implementing a variety of scenarios. Written in Unity using C#.
<br>
<hr>

<h2>Evolutionary Solver</h2>
Created a genetic algorithm which uses a population of neural networks to learn to play games. Written from scratch in C++. Currently Tic-tac-toe and <a href="https://en.wikipedia.org/wiki/Ultimate_tic-tac-toe">Ultimate tic-tac-toe</a> are implemented as games. While tic-tac-toe is fully solvable using algorithms such as minimax, a player's move in Ultimate tic-tac-toe affects the available moves an opponents has meaning the game cannot easily be solved using DFS (partly because it is hard to find a good heuristic for the strength of a board position). My approach therefore does not attempt to fully solve the game, but instead learns to find acceptable moves through a random exploration of the game space. This has been a long-term passion project of mine which I began after first learning about genetic algorithms. My repository can be found <a href="https://github.com/Eryl2000/EvolutionarySolver">here</a>.
<br>

<hr>

<h2>Planet Ball</h2>
A fast-paced local competitive arcade game. Players send a big ball flying into their opponent's goal by hitting themselves into it, but players cannot directly control their own movement. Instead they can grapple to pivots throughout the map and then time their release to propel themselves forward. The game was written with a teammate over the span of 24 hours for the 2018 Reno's Biggest Little Hackathon event. It was written in Unity using C#. I wrote the grapple physics, including tether connection/separation, how players can change their tether length, and how they interact with other players on the same pivot. I also designed one of the maps and helped with overall game design. Our repository can be found <a href="https://github.com/Eryl2000/Hackathon2018">here</a>.
