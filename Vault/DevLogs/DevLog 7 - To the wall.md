---
"ctime:": 2024-01-25
cssclasses:
  - clean-embeds
  - "|"
  - Prev
  - "|"
  - Next
---

# DevLog 7 - To the wall

#JamBuild #v0_1 

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 6 - It's spreading | Prev]] \] - \[ [[DevLog 8 - Ship it!| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Commits

#### Advanced movement and climbing ![[Rayo signature]]
```
Also changed up the ingame scene a bit and added Level scene for the actual level
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/94fccd101820f5f4981c42513b5e8553e10253a6)

- **Copper and Iron**
	- Made the distinction between COPPER and IRON instead of grouping them as METAL Now only COPPER is infected by grass
	- Updated tileset's tile_status data layer accordingly (COPPER stays at 0, IRON is now -1)
	- Updated ghost particles' behaviour so they only turn COPPER into GRASS
- **Climbing**
	- Added custom floor RayCast2Ds to Player 
	- Grass detection below player's wheels
	- Added custom is_grounded function for all surface calculations (on_surface_check())
	- Added climbing functionality using a floor normal vector for any surface inclination
	- Moved animation updating to \_physics_process() to avoid some weird twitching and also because of the velocity.x now being relative to the surface the player is using as floor
	- Tweaked fire boost to not unattach player from surfaces and changed friction depending if the player is mid-air or "grounded"
- Added respawn button (which restarts the level) and a SpawnPoint
- Started creating the Level scene
- Added camera script that follows the Player smoothly
- Tweaked the visibility_rect of particles so they don't stop rendering when player is not that far away from the world origin
- Fixed a bug where neighbors of charred tiles would still spread grass (because infectable neighbors were never de-queued)

***(No showcase was recorded at the time, check a more recent DevLog to see the Climbing functionality or the new Copper/Iron behaviour)***

---

#### new tileset v0.6 ![[Rayo signature]]
```
(no description)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/fcd34d025556df53aca1dd03ec1df8849bb99933)

- Added some walls, blends, edges, chains and bars

![[tileset (2).png]]

---

#### Starting out level ![[Nasty signature]]
```
(no description)
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/6644fcfe1140a462569d69197f94dae4833ca27a)

- Started blocking the starting area and some platforms, playing around with the current tiles and creating some combinations

![[Level_screenshot.png]]
*(This screenshot is from a more updated version of Level, *v0.1 *a.k.a. #JamBuild)*

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 6 - It's spreading | Prev]] \] - \[ [[DevLog 8 - Ship it!| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]