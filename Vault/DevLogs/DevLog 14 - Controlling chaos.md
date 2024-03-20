---
ctime:: 2024-02-16
cssclass: clean-embeds
---
![[backtodevlogs]]
# DevLog 14 - Controlling chaos

#PreAlphaBuild #v0_2

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 13 - What am I pressing | Prev]] \] - \[ [[DevLog 15 - Mouse no more| Next]] \] - \[ [[DevLog X - The End | Last]] \]

---

## Log

Jump buffering proved to be an effective way of unveiling some bugs that have been in the game since JamBuild involving the player's momentum and jumping the same frame we land. We have discovered 2 new movement tech: the **buffer boost** and the **hyper buffer boost**.

![[buffer-boost-1.png]]
![[buffer-boost-2.png]]

---

## Commits

#### Made low hops and buffer boosting less chaotic ![[rayo-signature]]
```
Also fixed the background tileset to have tile_data = -2 (decorations)
And also updated the testing scene with some lines displaying the height of a normal jump, a buffer boost, and a hyper buffer boost
```
[See GitHub commit](https://github.com/RayoROAR/GreenTop/commit/02c1e6d948a699be3cb737160c29b9d9298814b3)

- Low hops and buffer boosting was a bug that occurred due to the buffered jump being triggered twice. Found the source of the bug, fixed it, and then added buffer boosting again intentionally while making it consistent. Decided to keep the chaotic nature of the current momentum code to make low hops and, in turn, hyper buffer boosting still possible.
- Tweaked IngameScene with height indicators for the normal jump, buffer boost and hyper buffer boost

<p style="text-align: center">
	<iframe width="560" height="315" src="https://www.youtube.com/embed/7vKatZtarLg?si=8-pDHw0PaWVklREH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</p>

---

\[ [[DevLog 1 - Creation | First]] \] - \[ [[DevLog 13 - What am I pressing | Prev]] \] - \[ [[DevLog 15 - Mouse no more| Next]] \] - \[ [[DevLog X - The End | Last]] \]

![[navbar]]