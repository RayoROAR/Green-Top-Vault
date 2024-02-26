---
ctime:: 2024-02-08
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 11 - The small things

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 10 - Saved| Prev]] \] - \[ [[DevLog 12 - X | Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Fixed spreading bug and fully functional save/load
```
(no description)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/fb2d65c407c37ce01e8a201ca065fbb6d9403e58)

- Fixed the bug mentioned in the commit [[DevLog 10 - Saved#Commits#Save system 1.0]] from yesterday where grass that was loaded in would not start spreading. Did it by tweaking TileStatusHandler's ready() and load_data() functions to find spreading candidates AFTER loading

---

#### Dynamic clouds & minicursor
```
- Made dynamically changing despawn_x for clouds (depending on window aspect ratio)
- Added minicursor
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/5dc08fbadbb55de69899182b57260bc6550a4eff)

- Made dynamically changing despawn_x for clouds (depending on window aspect ratio)
- Added minicursor as guide between the regular cursor and the player (this is one of a few preparations before adding controller support)
- Added Coldfire Arm but still did nothing with it 
- Tried to add dynamic scaling to cursor but it's not supported (might try to do it somehow anyway? #TODO)

---

#### Readded Persist and minicursor to Level
```
(no description)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/d5feab395a9d30f57e4fd98407beadea075c762f)

- Wanted to wait for Nasty's green light to add the Minicursor and the Persist group (for save/loading) to Level to avoid merge conflicts

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 10 - Saved| Prev]] \] - \[ [[DevLog 12 - X | Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]