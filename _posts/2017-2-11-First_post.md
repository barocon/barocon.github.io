---
layout: post
title: Some unfinished prototype ideas for a dungeon crawler
---

A few months ago I made I a very simple dungeon generator. It basically iterates a list of doors and creates rooms for them.

<div style='position:relative;padding-bottom:56%'><iframe src='https://gfycat.com/ifr/SplendidThisBluebird' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

Since then I have trying to think how I can make interesting gameplay for the dungeons.

The biggest problem I faced is that the dungeons are too simple to be fun to explore. It creates too many dead ends. Even if I juice up the dungeons, it won't help with the issues. Recently I saw a [talk about Cyclic Dungeon Generation](https://www.youtube.com/watch?v=mA6PacEZX9M) by Joris Dormans. That sounds great but I would have to rewrite my generator pretty much from scratch to use to use grids and mesh generation. I don't have the time and motivation to do that right now. Maybe I'll try to later.

Anyway, here are some things I tried:

## First person dungeon exploration
The only weapon of the player was a bow that shoots shining light-arrows. It also had some platforming and blob-enemies that drop gold. The dungeon was pitch black so you had to use the arrows to see where you were walking.

I was thinking about making this into a 1st person roguelike. I didn't explore this idea much, because I wanted to try top-down perspective. Now looking back at it, I think I want to explore the 1st person dungeon idea more.

## Top-down melee / turret building games
I used an old temp model I made for the player and made a quick melee attack for it. I also made a item/turret menu that pops up when you hold Space.

I needed interesting goals for the game, so first I made a "boss" unit that travels from the beginning of the dungeon to the end. The goal was to kill the boss before it reaches the end. Before the boss spawns you had time to prepare by gathering gold so you could build turrets. Gold can be gathered by killing slime blob enemies and found in crates in some of the rooms.

I quickly realized that the boss idea lacked player agency and the boss was easy to beat by just saving some gold and building a few turrets by the path.

Second idea was to replace the boss with a payload you had to protect. I made some simple ranged enemiesa and made them spawn periodically from the beginning room. It was mostly the same as the boss encounter but you had be more active to protect the payload, so at least it was a small improvement.

## Simplified RTS
Next and latest idea was to try some RTS mechanics. Instead of player character I could buy lots of units and command them to attack-move to a point on the dungeon. I made some spawners that spawn periodically enemies that try to destroy your base.

I quickly ran into design issues again. The gameplay is pretty boring and lacks variation.