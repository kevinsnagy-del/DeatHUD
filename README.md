# DeatHUD

A HUD and minimap plug-in for **LET IT DIE**, built on [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000). Everything is set in the game, under **Options, then Mod Drive 9000, then DeatHUD**. A fresh install changes nothing until you do.

## Features

### Minimap
- **Always there:** the minimap builds its own area map as you explore, so you no longer have to open the area map first.
- **Two sizes:** a big map and a small map, each with its own size; the map button cycles between them.
- **Placement:** anchor it to any corner or edge, then fine-tune with X / Y offsets.
- **Zoom**, and **rotate with the player** (or keep north up).
- **Shape:** rectangle or circle, with an adjustable circle size.
- **Icons:** icon size, and icons kept upright (or not) while the map rotates.
- **Counters:** treasure count, enemy count and explored %, each with its own position, and one offset for the whole row on each map size.
- **Opened boxes** get their own colour on the map, so you can see what you have already looted.

### HUD layout
Every HUD element can be set on its own: the **left weapon slot**, the **right weapon slot**, the **item selector**, **health status**, **skill decals** and **status effects**.
- **Style:** Original, Minimal (for example only the active weapon slot) or Hidden.
- **Anchor:** the game's own place or any of six screen positions, plus X / Y offsets.
- **Size** in %.
- **Item selector:** switch speed, and where its button guides sit.
- **Skill decals:** a horizontal or vertical row, with or without their background boxes.
- **Status effects:** a preview, to place them without waiting for a real one.
- **Reset** any element, or everything at once.

### Messages
- The **message and currency pop-ups** can be moved or hidden, with example messages to preview the placement.
- The **DH Express Pass** can show in the pause menu (the original), in the DH Service menu at a position you choose, or be hidden.

### Colours
- **15 colour targets:** health bar, health bar at low health, rage gauge, weapon boxes, item selector boxes, skill decal boxes, health status box, general frames, general boxes, minimap floor, minimap fog, minimap background, minimap icons, minimap player arrow and opened boxes on the map.
- A palette of colours for each (white, red, orange, yellow, lime, green, cyan, blue, purple, pink, black and more), or the game's own.
- **Image painter:** every HUD image the game draws is recorded and listed by family, with the one under the cursor highlighted on screen. Recolour any of them, or lock one to its original colour.

### Presets
- **Three preset slots**, each saving your whole layout: positions, sizes, colours, painted images and the minimap.
- A ready-made **DeatHUD Extreme Layout** preset.

### Controls
- **Select / D-pad swap:** swaps D-pad down and Select during gameplay only; menus keep the normal buttons.

### Recipe tracker
- In the Laboratory's R&D list, **Y tracks a recipe** (the level on offer and its materials).
- On a floor, when you stand next to a material or mushroom, a panel lists every tracked recipe that needs it, with the amount needed and how many you already have.
- A finished research automatically moves on to the next level's materials.

## Install

1. Install [Mod Drive 9000](https://github.com/kevinsnagy-del/ModDrive9000) first.
2. Download `DeatHUD-<version>.zip` from [Releases](../../releases), close the game, and unzip it into the LET IT DIE folder.
3. Open `ModDriveInstaller\ModDrive9000.exe` and choose **Apply mods to the game**. It adds DeatHUD's textures (the colour textures and a greyscale icon sheet) to your game files, after backing them up.

**Updates and removal:** in `ModDriveInstaller\ModDrive9000.exe`, under **Mods**.

LET IT DIE belongs to GungHo Online Entertainment / Supertrick Games. This is an unofficial fan project.
