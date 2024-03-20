---
ctime:: 2024-02-21
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 15 - Mouse no more

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 14 - Controlling chaos | Prev]] \] - \[ [[DevLog 16 - FL0-W3R T0-W3R| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Controller support v1.0, cursor and autopause ![[rayo-signature]]
```
- Bugfix: mouse is now confined to the game window but can easily escape it while the game is paused. This solves a previous issue where players would try to shoot when their mouse was 1px outside the game window.
- Game automatically pauses when the game window loses focus (Alt+TABbing or other).
- Controller support v1.0:
 - The cursor's behaviour changes right when the controller is connected. "Controller mode" can be disabled by simply unplugging it. **TODO?**: Turn it off when irl mouse starts moving
 - **Free Aim Mode** with changing speed depending if the cursor is close to the player (slower for more precision) or far away (faster). Useful for puzzles.
 - **Snappy Aim Mode** with fixed length, cursor orbits player. Useful for parkour.
 - Joystick cursor is limited to game window's bounds.
 - Jump is both (X) and (L3) for a more comfortable platforming experience (right thumb is already using RStick to aim the arms, it can't press X).
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/34993e9a888108e2884405f99c7b958e7f3b3c4a)

- Fixed a bug where players would try to shoot when their mouse was 1px outside the game window and it wouldn't register the click. Now the mouse is confined to the game window but can easily escape it only while the game is paused
- Game automatically pauses when the game window loses focus (Alt+TABbing or other).
- **Controller support v1.0:**
	- The cursor's behaviour changes right when the controller is connected. "Controller mode" can be disabled by simply unplugging it. #TODO?: Turn it off when irl mouse starts moving
	- **Free Aim Mode** with changing speed depending if the cursor is close to the player (slower for more precision) or far away (faster). Useful for puzzles
	- **Snappy Aim Mode** with fixed length, cursor orbits center of screen. #TODO: Make it orbit player instead. Useful for parkour
	- Joystick cursor is limited to game window's bounds.
	- Jump is both (X) and (L3) for a more comfortable platforming experience (right thumb is already using RStick to aim the arms, it can't press X).

![[2024-02-21 17-25-44.mp4]]

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 14 - Controlling chaos | Prev]] \] - \[ [[DevLog 16 - FL0-W3R T0-W3R| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]