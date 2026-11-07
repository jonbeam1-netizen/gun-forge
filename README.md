# Gun Forge

A free, in-browser pixel gun sprite maker for the **ZED ZONE** MOD Editor.

**Open it:** https://jonbeam1-netizen.github.io/gun-forge/

## What it does

- Build a gun from parts: body, barrel, handguard, muzzle, stock, grip, magazine, sight and moving part.
- Each part has styles, size sliders, position nudges and colors.
- Start from presets (assault rifle, SMG, pistol, revolver, shotgun, sniper, LMG) or hit **Random gun**.
- Touch up pixels with the pencil, eraser and color picker.
- Export a ZIP containing:
  - the full image
  - one PNG per MOD Editor slot (Main Body, Moving Part, Barrel, Aimer, Gunstock, Magazine)
  - a `layout.txt` with sizes and mount offsets
  - your design file

## Using the PNGs in ZED ZONE

1. Unzip the download.
2. In the game, open **MOD Hub → MOD Editor → NEW**, then **Import Template** with a similar gun.
3. Under **[ TEXTURE ] → IMPORT PNG**, paste the file path of `_full.png`. In File Explorer, Shift + right-click the PNG and choose **Copy as path**.
4. Keep **PPU 64** for 1× exports.
5. Set the stats in **[ PARAMS ]**, then **SAVE**.

Sprites face right, and 64 px is 1 m in game. Everything runs in your browser, and your current gun is remembered on your device.

Fan-made tool. Not affiliated with the ZED ZONE developers.
