---
ctime:: 2024-03-13
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 17 - Stainless steel

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 16 - FL0-W3R T0-W3R| Prev]] \] - \[ [[DevLog 18 - Slopes and belts| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Fixed level, a lotta new stuff ![[rayo-signature]]
```
Too tired to compile stuff done, I'll just log it tomorrow
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/9f813d2da0d950347f5660ab2f8786e97434c96f)

- **TileStatusHandler**
	- Unified all status consultors into one is_status() function for simplicity
	- Added STEEL and CLIMBABLE_STEEL and respective consultors
	- Fixed some atlas coordinates because tileset was tweaked
	- Added dynamically spawning zippers (just like grass blades but for CLIMBABLE_STEEL)
	- Made grass blades spawn on all layers
	- Tweaked infection logic so it targets other layers aside from Layer0
	- Block changes take into account the SourceID (if they're from the tileset with collisions or the one solely used for decorations)
- Updated water particle shape texture (preparation for particles overhaul)
- **Player**
	- Created some small blocks of code to make tech easier to pull off while debugging
	- Updated all climbing related functions to be more scalable with new climbable block types
	- Made climbable steel... climbable
- Tweaked particles' z_index
- Added letters as tiles
- Updated IngameScene to showcase tech
- Updated tileset with STEEL tiles and zippers (also moved some stuff around)
- Added TestLevel as a playground for level design and tile combinations

![[alphabet_tileset.png]]
![[tileset (5).png]]


---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 16 - FL0-W3R T0-W3R| Prev]] \] - \[ [[DevLog 18 - Slopes and belts| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]