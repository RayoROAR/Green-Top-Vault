---
ctime:: 2024-01-23
cssclass: clean-embeds
 | Prev
 | Next
---

# DevLog 6 - It's spreading

#JamBuild #v0_1 

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 5 - Fire and Water | Prev]] \] - \[ [[DevLog 7 - To the wall| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits 

#### Watering and Burning logic done ![[Rayo signature]]
```
time for spreading ( ͡° ͜ʖ ͡°)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/55041baf2feee25d979fd8b0cb584c85973fa46a)

- Tweaked TileStatusHandler enum (added BURNING, WOOD and BURNINGWOOD)
- Coded ghost particles to handle particle collisions
- Made watering and burning logic thanks to ghost particles
- Updated tileset
- Some small tweaks to the player and arms when turning around (z indexes and x positions)

![[tileset (1).png]]
![[2024-01-23 11-45-26.mp4]]
![[2024-01-23 13-43-42.mp4]]

---

#### IT'S SPREADING ![[Rayo signature]]
```
FUCKING FINALLY
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/129bb63bac1c1d920cee8044af985dcbbbf8353f)

- Made grass spread to neighboring metallic (iron or copper) tiles
- Moved cell updating logic from ghost particle to the tileset itself (also used for spreading)
- Tweaked some UI scenes

![[2024-01-23 21-49-15.mp4]]

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 5 - Fire and Water | Prev]] \] - \[ [[DevLog 7 - To the wall| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]