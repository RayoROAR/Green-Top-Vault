---
ctime:: 2024-01-22
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 5 - Fire and Water

#JamBuild #v0_1 

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 4 - Pixel imperfect| Prev]] \] - \[ [[DevLog 6 - It's spreading| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Budget pixel perfect, fire and water ![[rayo-signature]]
```
Applied a fast solution to the pixel perfect problem (reduced the viewport's size instead of applying a shader (faster both in terms of computing time and time spent thinking about it, win/win!)). Also made the robot shoot water and fire (water collisions are still buggy, idk what causes it)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/f18beb4739a4746aed026e9bd550c658e7460311)

- Added TileStatusHandler with the METAL, GRASSY and BURNT states
- Updated cursor sprite
- Added fire and water particles
- Implemented fire and water shooting

![[cursor (1).png]]
![[2024-01-22 01-18-17.mp4]]

---

#### Water bug fixed, player speed affects initial velocity of particles a… ![[rayo-signature]]
```
…nd fire shooting boost

FUCK YESSSSSSSSSSSSSSSSSSSSSSSSSSSS
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/2659f3165d7ec61b63ed33d7487d605c532ef2be)
**Rayo**

- Added circular shape to water particles and some other tweaks
- Updated cursor to be dynamic
- Fixed water bug by rewriting the whole particle shooting code and making the particle system stay in place
- Some viewport size tweaks (now 384x216)
- Added fire boosting
- Particles shot now depend on player speed

![[cursor (2).png]] ![[cursor_f.png]] ![[cursor_w.png]] ![[cursor_wf.png]]
![[2024-01-22 18-03-48.mp4]]

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 4 - Pixel imperfect| Prev]] \] - \[ [[DevLog 6 - It's spreading| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]