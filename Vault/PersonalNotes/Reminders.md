# Reminders

- ghost_particle.gd has a different method than TileStatusHandler.gd for infecting and burning tiles (it uses addition instead of mod). Remember to update this if you (for some god forsaken reason) decide to update the tilemap and move stuff around.
- addToChangedTiles from TileStatusHandler has an erased boolean
- Find out after fixing the hovering 1px glitch if a lowest hop can be achieved where the player only jumps 1px
- Remember that the encryption on save/load files is disabled