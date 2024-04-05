---
ctime:: 2024-03-19
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 18 - Slopes and belts

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 17 - Stainless steel| Prev]] \] - \[ [[DevLog 19 - X| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Level fixes, slopes, technical stuff ![[rayo-signature]]
```
log in obsidian
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/881adb773cb5bde12246060825daa0d021b3598e)

- **TileStatusHandler**
	- Added a system that saves a dictionary with every tile of a level with its original status to a baked file to load it instead of having to iterate all tiles again every time the player reloads the level (baked files are saved under user://baked/)
	- Optimized save file size by deleting tiles that have changed into their original status
	- Updated tile changing system so it doesn't try to change tiles that don't have a counterpart with other materials
	- Updated layer status checker (get_layers_with_tileStatus_at_coords) to allow checking for multiple statuses
	- Updated rust_tile() and charr_tile() to work with different sourceIDs and multiple layers
- Save files are now stored under user://saves/ and are level-specific
- **Player**
	- Fixed arm flickering when starting to climb surfaces
	- Tweaked momentum conservation so it conserves perpendicular momentum if starting to climb from air and parallel momentum if starting to climb from another surface
	- Slopes are now climbable
- Updated ghost_particle so it uses the specific functions to change tile statuses instead of handling everything inside it and upating the cell manually
- Added some animated IRON and COPPER tiles
- Added conveyor belts (not functional yet, just aesthetic)
- Fixed a memory leak in input_actions_display.gd


![[tileset_animated.gif]] ![[belts.gif]]


---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 8 - JamBuild!| Prev]] \] - \[ [[DevLog 10 - Saved| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]