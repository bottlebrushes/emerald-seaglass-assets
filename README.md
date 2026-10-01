# Pokémon Emerald Seaglass — extracted graphics

Graphics from **Pokémon Emerald Seaglass** by Nemo622, a Game Boy Advance (Pokémon Emerald base) fan game, organised as plain image files for reference, study and fan projects.

## Contents

| Folder | What | Count |
|---|---|---|
| `pokemon/` | Pokémon battle sprites | 500 |
| `overworld/` | overworld sprite sheets | 485 |
| `tilesets/` | map tilesets | 35 |

Each folder has a contact sheet (`_contact_*.png`) for browsing, and `manifest.json` lists every asset with notes.

## Format

- `pokemon/<name>/` — `front.png` (64×64 frames stacked vertically, palette applied, transparent background), `front_indexed.png` (same as a 16-colour indexed PNG), `back.png` / `back_indexed.png`, `shiny.png`, and `preview.gif`.
- `overworld/<sprite>/` — horizontal strip of frames at native size.
- `tilesets/<tileset>/` — `tiles.png` (tile sheet, 16 tiles wide) with its palette, plus the raw `metatiles.bin` / `attributes.bin` where present.

## What is (and isn't) here

Only art that belongs to this game is included. Sprites, backs, interface pieces and icons that are identical to the official Pokémon Emerald graphics were left out, as were anything that could not be decoded reliably.

Overworld sprites are shown in a neutral palette (their in-game palettes are assigned at runtime). Tilesets are published as tile sheets only; composed block renders are not included.

## Credits

- Pokémon Emerald Seaglass: Nemo622.
- Pokémon and all related characters and designs: © Nintendo, Creatures Inc. and GAME FREAK inc.

## Disclaimer

This is an unofficial fan archive. It contains no ROMs and no game code, only extracted images and palettes. All art remains the property of its creators; credit them if you use anything from here. Not affiliated with Nintendo, The Pokémon Company or the original fan-game authors. If you are an author and want something removed, open an issue.
