# General

## Adapted Goals
- Overworld with one section
- Characters without state (memory of pat conversations)
- Simple inventory management (Only one slot per category)
- Stats: No adaptive learning from combat, no damage-specific attacks for different enemies
- Simple saving in menu (No savepoints)
- No or only basic audio
- Only simple Main Menu

## Libraries
(So far)
- SFML: Graphics, input
- ImGui: UI
- Tiled / tileson: Create map
- spdlog: Logging
- Assets: Ninja adventure asset pack

![](images/ninja_adventure_preview.png)

## Steps overall
- Create, parse and display simple world
- Implement main character that can move around on map
- Inventory management
- NPCs (and enemies)
- Turn-based combat
- Saving and loading
- Final world with story

# Week 1

## Done
- Investigated libraries
- Built basic project/cmake structure, manage library imports
- Closer look at map parsing and rendering with Tiled/tileson/ImGui-sfml
- Create placeholder map with Tiled
- Planned future steps

## Next steps
- Create, parse and display simple world
- (Implement main character that can move around on map)
