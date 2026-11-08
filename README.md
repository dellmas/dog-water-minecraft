# Dog Water Minecraft

Shared CurseForge client profile for Dog Water Minecraft, based on All the Mods 9.

**[Download the latest profile ZIP](https://github.com/dellmas/dog-water-minecraft/releases/latest/download/Dog-Water-Minecraft.zip)**

[Latest release and version notes](https://github.com/dellmas/dog-water-minecraft/releases/latest)

This repository is public. Friends can download the profile without a GitHub account.

## Join the server

1. Close Minecraft. In CurseForge, select Minecraft, then **Import** and choose the downloaded ZIP.
2. Import it as a **new profile**. Do not extract the ZIP, install ATM9 separately, or use Update All.
3. Launch **Dog Water Minecraft**. Choose **Multiplayer > Dog Water Minecraft > Join Server**.

The server entry is included: `server.dogwaterdev.com:25566`.

The profile uses Minecraft **1.20.1**, Forge **47.4.0**, and ATM9 **1.1.1**, with the server's custom mod additions/removals and compatibility settings. Each player needs their own Minecraft Java account.

## Current profile: 1.0.22

### November 7 profile changes

Corrected Tool Stats showing -1 for Crystalcraft/custom mining tiers. Unresolved tiers now display the level declared by the tool mod (Platinum: 10). Recognized Forge tiers and other statistics are preserved; actual tool behavior is unchanged. Fully restart Minecraft to load this client-only correction.

Ordinary player, mining and mob drops now last one hour of loaded, ticking time. Remaining lifetime survives chunk unloads and saves. This is already active on the server; existing players need no client restart or profile update for this setting. Grave storage and special modded item lifetimes are preserved.

Added Tool Stats 16.0.10 on the client for additional equipment tooltip information. Bookshelf is already included. The Tool Stats addition itself needs only a client restart. Fully restart Minecraft to load it. Profile 1.0.22 has 369 client mods; the server has 347 JARs once the bridge is installed.

Added Crystalcraft Unlimited with prism tools, weapons and armor, using its default content. New ores generate in newly explored chunks. Fully restart Minecraft or import this updated profile before joining.

Enabled the Twilight Forest Uncrafting Table. Uncrafting, special uncrafting recipes and repairs cost zero XP. Other restrictions are unchanged.

### November 6 profile changes

Added a client correction to keep the Inventory Tweaks A-Z tab on the inventory edge when opening or closing the recipe book. Full client restart is required; live visual confirmation is pending.

Removed Quark's extra transfer buttons from Sophisticated backpack/storage screens to prevent overlapping controls and tooltips. Native Sophisticated transfers remain. Fully restart Minecraft to load the setting; live display/click confirmation is pending.

### November 5 profile changes

Removed 63 mod files today, including the redundant CC: Tweaked 1.113.1 copy. CC: Tweaked 1.116.1 remains, along with Refined Storage, EnderChests, Iron Jetpacks, Tinkers' Construct and Silent Gear. Current totals: 345 server mods and 366 client mods. Shared profile uses standard textures.

- Redundant CC: Tweaked 1.113.1 is removed; 1.116.1 remains.
- AE2 and its fourteen addons/integrations, DimStorage and Create Jetpack are removed. Refined Storage, EnderChests and Iron Jetpacks stay. Tinkers' Construct and Silent Gear are unchanged.
- Croptopia and all eight Thermal mods are removed, along with the earlier requested removals. Simple Planes is included. Ars Nouveau, Ad Astra, and Corail Tombstone remain. CoFH Core stays for Redstone Arsenal and Ensorcellation.
- All six RFTools modules, Deep Resonance, Advanced Generators, Generator Galore, Traveler's Backpack, XNet and XNet Gases are removed. Sophisticated Backpacks stays, including mob backpack loot and B to open the equipped bag.
- Alchemistry/ChemLib/AlchemyLib, Psi, Integrated Dynamics and its addons, Nature's Aura, Botania/MythicBotany and dependent addons, TownTalk and StyleColonies are removed. Retained Powah and Ars progression routes stay available.
- Sushi Go Crafting, Mystical Agriculture/Agradditions and its two dependent addons, Botany Pots/Trees, and Productive Bees/Trees are also removed. ATM progression and Time in a Bottle use retained ingredients; obsolete quests, drops, and integrations are cleaned up.
- Removed crop market entries, quests, and integrations are cleaned up. Two late-game ATM ingredients have replacements so those recipes remain craftable.
- **B** opens your equipped Sophisticated Backpack; **Alt+B** creates a JourneyMap waypoint.
- The green vanilla recipe-book button is restored, including FastWorkbench, Crafting Tweaks, KubeJS, Quark, and Patchouli settings. JEI recipe lookup remains available with **R**.
- Controller settings and the F9 shortcut conflict fix included.
- The shared profile uses standard Minecraft and mod textures. Optimum Realism and its texture overlay are omitted. The patched Complementary shader remains selected and can be disabled under **Video Settings > Shader Packs**. Frame limit is 60 FPS, VSync off.
- Grave recovery/death-marker integration included. Profile 1.0.13 corrected a client callback crash that prevented cleanup. Three checks using the installed Rhino engine and 18 logic checks passed. Fully restart Minecraft to load the fix; actual in-game cleanup verification remains pending. Ordinary waypoints and unconfirmed deaths are preserved.

## Memory

Use 8192 MB on a 16 GB PC, or 10000-12000 MB on a PC with 24 GB or more. Adjust this in the CurseForge profile options. Allow several minutes for the first launch and server join.

## Updates and checksums

Future profiles will be published as releases. The download link above always targets the latest published release. Compare the ZIP's SHA-256 with the checksum attached to that release if you need to verify the download.

The ZIP is a CurseForge manifest with configuration overrides; CurseForge downloads the referenced third-party packages from their authors. It contains no player worlds, account credentials, personal waypoint data, or server administration credentials.

## Credits

Based on [ATM9 by ATMTeam](https://www.curseforge.com/minecraft/modpacks/all-the-mods-9). Mods, resource packs, and shaders remain the work of their respective authors. This is a custom profile, not an official ATMTeam release.

### Backpack pickup notifications

Profile 1.0.22 adds a small MIT-licensed bridge for the pinned Sophisticated Backpacks and Loot Journal versions. Pickup and magnet upgrades use the normal journal notice with a backpack badge. Full bags report nothing; partial pickups report only accepted items. The bridge must be loaded by the server and client. Fully restart Minecraft after importing/updating. Server activation waits for safe maintenance; no occupied-server restart is forced.
