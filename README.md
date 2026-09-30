# Lumber Tycoon 2 | GoDot Edition

A remake of Lumber Tycoon 2 in Godot 4. The goal is to get as close to the original Roblox game as possible - same map, same stores, same axes, same trees, same everything - but running as its own standalone game.

This is a **beta**. A lot works, a lot is still missing or rough around the edges. I'm still working on it and a full release will be out soon.

## About the code

None of the original Roblox Lua is running here. Every script has been written from scratch in GDScript for Godot. I used the original game as the reference for how things should behave (tree growth, chopping, dragging, selling, the sawmill, wiring and so on) and rebuilt each system to match it as closely as I could.

The map, item models and UI layouts were exported from the place and rebuilt in Godot.

## What's in so far

- The full map, with trees growing in every biome
- Chopping trees, cutting logs, dragging wood around
- Selling wood at the dropoff
- Wood R Us, the land store, car store, furniture store, logic store and the rest, with working NPCs you can interact with 
- Buying and expanding land
- Placing structures, sawmills, conveyors, blueprints, furniture and vehicles
- Wires and logic items (buttons, levers, gates, lasers, doors, lamps, etc.)
- Driving vehicles and hitching trailers
- Saving and loading your land (6 save slots)
- Day/night cycle, region music, graphics settings

## Known issues / not done yet

- Some sounds are missing 
- No multiplayer (single player only for now)
- Expect bugs - if you find one, open an issue

## Running it

Grab the latest exe from the Releases page and run it. No install needed. Windows only for now.

If you want to open the project yourself, you'll need Godot 4.7.

## Controls

- WASD - move
- Mouse - look / click
- Click and hold - drag items
- Shift + WASD - rotate what you're dragging
- E - interact / talk
- 1-9 - tools
- F11 - fullscreen

## Credits

- Original game: Lumber Tycoon 2 by Defaultio on Roblox. This is a fan remake and isn't affiliated with Roblox or Defaultio.
- Music: Kevin MacLeod (incompetech.com), licensed under Creative Commons: By Attribution 4.0
