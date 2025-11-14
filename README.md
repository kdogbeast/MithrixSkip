# MithrixSkip

**Skip the hassle of finding a way to the top and skip straight to fight Mithrix.**  
This mod spawns a free “shrine” **outside** near the Commencement ship barrier so you can start the Mithrix encounter immediately. Works in single-player and multiplayer.

## Features
- Server-only spawn (no client duplicates)
- In-game chat messages on spawn and activation
<p align="center">
  <img src="MithrixSkip/gif mithrix" width="720" alt="MithrixSkip demo">
</p>



- Spawns close to the end of the slop, near the ship barrier
- It's free!! 
- Configurable offsets if you want to change it or something (weird)

## Config (BepInEx)
A config file is generated at `BepInEx/config/com.ked.MithrixSkip.cfg`.

Key options:
- `PlaceOutsideShipBarrier` (default **true**)
- `OutsideRightOffset` (default **45**)
- `OutsideFromShipDistance` (default **18**)
- `SnapToGround` (default **true**)
- Chat messages and general delay toggles

## Multiplayer
- The shrine is spawned **server-side only**.
- Activation broadcasts a chat message with the name of whoever activated it.

## Known Limits
- If another mod aggressively moves/renames ship objects, auto-anchoring may fall back to a safe default near arena center.

## Credits
- Enjoy the mod!
- 
