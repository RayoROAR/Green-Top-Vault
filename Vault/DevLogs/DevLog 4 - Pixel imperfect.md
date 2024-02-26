---
ctime:: 2024-01-21
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 4 - Pixel imperfect

#JamBuild #v0_1 

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 3 - Robot is born | Prev]] \] - \[ [[DevLog 5 - Fire and Water| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Removed movement jitter, complete tileset WIP ![[rayo-signature]]
```
(no description)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/2557ebd2ad45e809394e880f31443306938f722a)

- Tried some addons for smoothing (removing jitter)
- Added piskel file of tileset
- Removed jitter after changing the engine's physics ticks from 60 to 120

---

#### Tried to implement pixel perfect shader ![[rayo-signature]]
```
Shader is still not finished, I want to make it texture space instead of screen space to apply it to individual sprites intead of EVERYTHING. It also fucks up the UI so it's a no-no.

Working on: Custom Tile data, interacting with tiles from the tileset, (and maybe spread/infection from neighboring tiles)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/01c8ef0d717ce4861eda579b38b43b455b5c6aa6)

- Added simple custom cursor
- Player now has moving arms
- Tried to code a pixel perfect shader

![[cursor.png]]

##### Without pixel perfect shader:
![[2024-01-21 13-19-19.mp4]]

##### With pixel perfect shader:
![[2024-01-21 13-19-54.mp4]]

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 3 - Robot is born | Prev]] \] - \[ [[DevLog 5 - Fire and Water| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]