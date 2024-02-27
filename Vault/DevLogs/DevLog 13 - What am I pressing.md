---
ctime:: 2024-02-14
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 13 - What am I pressing?

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 12 - Grassier grass | Prev]] \] - \[ [[DevLog 14 - Controlling chaos| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### check description ![[rayo-signature]]
```
- Changed tile_status of grassBlades to -2 to avoid spreading
- Changed block type checkers of tileStatusHandler accordingly
- Added debug tools that display current action
- Started mapping some controller actions
- Added jump buffer
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/aacaf5284109f62e4e3e4b322df1317268aba8e4)

- Fixed a bug where grass blades would be treated as grass blocks and would spread the green. There are still some bugs when burning the grass blades
- Tweaked TileStatusHandler's block type checker functions
- Added a list of action labels on screen as a debugging tool that displays what actions are being pressed. Controller support is pretty much ready to be worked on!
- Started mapping some controller actions
- Added a jump buffer
- Changed some get_node()s to get_node_or_null()s to avoid clogging the output with invalid reference errors

![[action-labels_screenshot.png]]

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 12 - Grassier grass | Prev]] \] - \[ [[DevLog 14 - Controlling chaos| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]