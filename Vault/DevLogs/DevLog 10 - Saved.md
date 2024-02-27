---
ctime:: 2024-02-07
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 10 - Saved

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 9 - Crispy UI font| Prev]] \] - \[ [[DevLog 11 - The small things| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Save system 1.0 ![[rayo-signature]]
```
still need to fix some bugs when loading grass that should be starting to spread
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/7b38963a80fd62c3072c29f47cc87bd83340a3f1)

- Made custom save and load functions for the TileMap (in TileStatusHandler.gd) that saves/loads only tiles that have been changed from their base state
- Tweaked base save/load system from the BitBrain template to be more space-efficient and to avoid some potential bugs
- Fixed Camera and Player instantiation so that both aren't snapped into position after load but instead are instantiated after the load (the camera would zoop by from 0,0 to the player's saved position)

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 9 - Crispy UI font| Prev]] \] - \[ [[DevLog 11 - The small things| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]