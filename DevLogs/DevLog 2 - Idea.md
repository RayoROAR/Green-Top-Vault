---
ctime:: 2024-01-18
cssclass: clean-embeds
 | Prev
 | Next
---

# DevLog 2 - Idea

#JamBuild #v0_1 

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 1 - Creation | Prev]] \] - \[ [[DevLog 3 - Robot is born | Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Log

These past few days I've been thinking about what kind of game I want to make. The plan was to incorporate some kind of unexpected twist using the jam's theme. During our daily walk, my parents and I talked about it and they suggested spreading rumours or spreading the word about something.

I told them that I had in mind some sort of story centered 3D game where you'd start off in a building as a robot infected by grass and the world was being taken over by spreading grass and you'd have to find out why. The idea to make a 3D content-heavy game was scrapped because of the tight deadline.

My mom came up with the idea to make it some sort of "bubble farmer" where bubbles would start to appear on screen spreading and multiplying like a virus. So then, the game loop would be that you need to keep the bubbles on screen for *some reason* but you'd have to control how many there are to avoid them multiplying too much and taking over. I liked this idea.

On the 15th, while still feeling sick some days after chemo, I started doing some doodles about what the grassy robot idea would look like if the game was instead a 2d tech-centered platformer. I envisioned the robot starting off inside some sort of lab or factory where the grass got to its circuits and turned it on. The end goal would be to climb this tall clock tower where a huge flower boss fight would occur. This flower was supposed to be what was spreading all the grass and defeating it would free the clock's hands which would spin back in time before the robot city was infected by the grass.

![[Green Top concept sketch.jpg]]

This idea was internalized and I started to think where should I begin. I now had the game's main mechanics:
1. Water spreads grass
2. Fire burns grass (and gives a boost)
3. Grass spreads to adjacent tiles
4. Grass is climbable

Today, I've started working on this idea by playing around a bit with Godot, getting the hang of stuff (I hadn't touched it in almost 2 years).

---

## Commits

#### playing around ![[Rayo signature]]
```
init
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/fb2bd5e5216915ffb8000dcd7757258313c005f2)

- Changed the translation table and added spanish, tried to implement it without success
- Changed some project config to fit the new game: Green Top

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 1 - Creation | Prev]] \] - \[ [[DevLog 3 - Robot is born | Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]