# Mods for the game

The game reads one optional file, `active.json`, in this folder. It adds the signs, lights,
stop lines, zebra crossings, trees and street lamps made in the builder.

1. Open the builder (`npm run dev`, then `/builder.html`), place items, and save a version.
2. Click **Export mod (apply to game)**. It downloads `active.json`.
3. Copy that file into this folder as `active.json` and reload the game.

If the file is missing or not a MapNG mod, the game runs exactly as before.
Signs and lines are still hidden by the game's clean-map setting (`CLEAN_MAP` in `src/mapng/boot.ts`)
until that setting is turned off.
