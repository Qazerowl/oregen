# Oregen

Configuration datapack base that removes vanilla ore and stone-variant generation using Forge biome modifiers.

## Purpose
This pack is intended as the starting point for a Forge 1.20.1 worldgen overhaul. It removes vanilla ore/stone placed features so that custom, rare, large veins (from another datapack or mod) can take over.

## Structure
- `pack.mcmeta`: Datapack metadata.
- `data/forge/biome_modifier/remove_vanilla_ore_and_stone_features.json`: Forge biome modifier that removes vanilla underground ore/stone placed features in Overworld and Nether biomes.

## Next steps
Add your own placed/configured features (or a mod) that introduces the large, rare, spread-out veins down to Y=-128 and any modded ore features you want to replace.
