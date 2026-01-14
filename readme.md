# Oregen

Vanilla datapack that disables all vanilla ore and stone-variant placed features by overriding their placed feature definitions with a zero count.

## Purpose
This pack removes vanilla ore and stone-variant generation without requiring Forge. It works by replacing the vanilla placed feature JSON files with versions that have a placement count of `0`.

## Structure
- `pack.mcmeta`: Datapack metadata.
- `data/minecraft/worldgen/placed_feature/*.json`: Overrides for each vanilla ore/stone placed feature that set count to zero.

## Notes
- This only affects vanilla placed features. Modded ores require additional overrides for their own placed feature IDs.
