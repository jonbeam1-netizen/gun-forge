# Gun Forge

A free, in-browser pixel gun sprite maker for the **ZED ZONE** MOD Editor.

**Open it:** https://jonbeam1-netizen.github.io/gun-forge/

## What it does

- **Build a gun from 10 parts:** body, barrel, handguard, muzzle, stock, grip, magazine, sight, moving part and under-barrel. Each part has styles, size sliders, position nudges and colors.
- **Seven themes, each with its own parts:**
  - Military (realistic)
  - Cyberpunk
  - Steampunk
  - Fantasy
  - Laser
  - Space blaster
  - All + Chaos, which mixes everything
- **41 presets**, from assault rifles, bullpups and lever-actions to rune crossbows, dragon muskets, tesla cannons and heavy blasters.
- **Random gun** for the selected theme, or **Chaos gun** to mix every theme.
- **Glow color, trim metal and glow halo.** Glowing parts light up, and the soft halo is saved into the PNG.
- **Test fire preview** with muzzle flash, blaster bolt, laser beam, magic bolt, steam blast or crossbow bolt.
- **Pixel tools:** pencil, eraser and color picker, with undo/redo.
- **Gun codes:** copy a short text code or a share link that opens your exact gun. Paste a code to load someone else's.
- **Export** a ZIP with:
  - the full image
  - one PNG per MOD Editor slot (Main Body, Moving Part, Barrel, Aimer, Gunstock, Magazine)
  - a `layout.txt` with sizes, mount offsets and the gun code
  - a JSON design file

## Using the PNGs in ZED ZONE

1. Unzip the download.
2. In the game, open **MOD Hub → MOD Editor → NEW**, then **Import Template** with a similar gun.
3. Under **[ TEXTURE ] → IMPORT PNG**, paste the file path of `_full.png`. In File Explorer, Shift + right-click the PNG and choose **Copy as path**.
4. Keep **PPU 64** for 1× exports.
5. Set the stats in **[ PARAMS ]**, then **SAVE**.

Sprites face right, and 64 px is 1 m in game. Everything runs in your browser, and your current gun is remembered on your device.

Fan-made tool. Not affiliated with the ZED ZONE developers. All gun designs are original pixel art.
