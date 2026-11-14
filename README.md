# Dog Water Minecraft



Shared CurseForge client profile for Dog Water Minecraft, based on All the Mods 9.



**[Download the latest profile ZIP](https://github.com/dellmas/dog-water-minecraft/releases/latest/download/Dog-Water-Minecraft.zip)**



[Latest release and version notes](https://github.com/dellmas/dog-water-minecraft/releases/latest)



This repository is public. Friends can download the profile without a GitHub account.



## Join the server



1. Close Minecraft. In CurseForge, select Minecraft, then **Import** and choose the downloaded ZIP.

2. Import it as a **new profile**. Do not extract the ZIP, install ATM9 separately, or use Update All.

3. Launch **Dog Water Minecraft**. Choose **Multiplayer > Dog Water Minecraft > Join Server**.



A new CurseForge instance does not automatically copy local maps, saves or personal settings from an older instance. Transfer any wanted personal data once; server-side player progress is retained.

The server entry is included: `server.dogwaterdev.com:25566`.



The profile uses Minecraft **1.20.1**, Forge **47.4.0**, and ATM9 **1.1.1**, with the server's custom mod additions/removals and compatibility settings. Each player needs their own Minecraft Java account.



## Current profile 1.0.39

Use the Butcher Knife on a Twilight Forest deer and process its carcass on the Meat Hook for 12 to 18 raw venison. Server activation follows its next startup.

Light a standard obsidian Nether portal in Lost Cities. Use the same Nether portal to return to Lost Cities. Server activation follows its next startup.

SimpleBoats adds nine vessels, including passenger boats, cargo barges, and larger ships. [SimpleBoats on CurseForge](https://www.curseforge.com/minecraft/mc-mods/simpleboats/files/9246647).



### November 9 profile changes

**Moving filled storage:** Sophisticated Storage chests and barrels now retain contents automatically when broken, using the native packed-drop setting. Live on the server without a restart; matching client config delivered through AutoModpack. Ordinary Minecraft chests still require Packing Tape or an in-place Basic Tier Upgrade before moving them. No new mod.


**Automatic updates (AutoModpack4.0.7):** import profile1.0.32 once, join Dog Water Minecraft, review the server certificate/pack and complete the initial enrollment/restart. Later launches compare the server-hosted mirror of the published GitHub release and fetch only new/changed managed files; obsolete managed files are removed. Ctrl+Home, required pack configs and our scripts are included. Personal controls, graphics, maps, JEI preferences and saves are excluded. Updates to unlisted custom JARs can require in-game review and a restart. Exact managed-file hashes are published in `profile-files.json`. Active on the server after an empty-server backup/restart. Production manifest paths/hashes/sizes exactly match all 1,410 published managed files. First real-player enrollment remains to be completed.



The **`/warp cities`** dimension now generates without spawners. **2,243 existing city spawners** removed; loot and city buildings retained. Spawners in other dimensions remain. This is active server-side; existing players need no client/profile update for this change. Shared 1.0.31 includes matching city-only generation settings.




Added Light Engine to extend ordinary floor/wall torch light from 14 to 24. This changes actual block lighting, with light level 8 measured 16 blocks away in the native server audit. Other light sources keep their levels. Owner client and server updated; fully restart Minecraft, and friends should import profile **1.0.30**. Existing cached torch light may require breaking/replacing that torch. Client visual verification remains pending.



The MIT-licensed mod includes a packaging-only compatibility fix for the pack’s MixinExtras dependency; all 97 gameplay classes are unchanged. Twelve native lighting/lifecycle checks passed.



### November 8 profile changes



Claim allowance doubled from **500 to 1,000 chunks per team**. Force-loading remains **25**. Applied live to both existing players; current claims are preserved. No client update needed for this server setting.



One player sleeping now skips night. `/tpa <player>` or `/tpto <player>` teleports only you to that online player without an acceptance request, using FTB Essentials' existing cooldown and `/back` history. `/tpahere` still requests permission to bring someone to you. Active live on the server; no client update required for these settings.



Enabled an intact-city adventure dimension alongside the existing Overworld. Use **`/warp cities`** to visit and **`/home`** to return to your saved home. Buildings and loot are enabled; city spawners have since been removed and disabled. Normal combat still applies. The public arrival is on a lit street. Existing Overworld builds/progress are preserved. Existing clients already have Lost Cities and can visit without adding a mod. Shared configuration now matches the server’s city preset.



Added **Ctrl + Home** (the Home key) to run `/home` without typing. It fires once per press while playing, stays inactive in chat/inventories/menus and keeps normal server permissions/cooldown. Fully restart Minecraft to activate this client-only shortcut. Ten installed Rhino/native Forge keyboard-event checks passed; a real in-game key press has not been tested.



Added a Take All button to the Twilight Forest Uncrafting Table. It collects recoverable materials from one recipe batch through normal slot actions. Red/lost ingredients stay lost; full inventories preserve the input and partial inventories leave the remainder in the table. Existing zero-XP settings remain. Fully restart Minecraft to load the client-only button; no server restart is needed. Twenty native inventory checks and eleven native button/Rhino checks passed; live display verification is pending.



Fixed client startup failing with ResourcePackInfo for the backpack pickup bridge. Bridge 1.0.1 includes required Minecraft 1.20.1 resource-pack metadata. Native metadata parsing and a full client launch to the main menu passed. Gameplay and network code are unchanged.



### November 7 profile changes



Fixed temporary quest reward pickup visuals being kept around by the one-hour drop timer. Real drops still last an hour; quest/give animation copies expire normally. Nine old visuals were cleared live, with no server/client restart needed for existing players. Thirteen native lifecycle checks passed.



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



Profile 1.0.22 adds a small MIT-licensed bridge for the pinned Sophisticated Backpacks and Loot Journal versions. Pickup and magnet upgrades use the normal journal notice with a backpack badge. Full bags report nothing; partial pickups report only accepted items. The bridge must be loaded by the server and client. Fully restart Minecraft after importing/updating. The server bridge is active following an empty-server backup and restart. Fully restart your client to load the bridge; live badge/display verification is pending.


## Profile 1.0.34 — Twilight Forest portals from cities

Twilight Forest portal creation is enabled outside the Overworld, including the cities dimension. Standard water/flowers/diamond activation applies. Twilight Forest return portals still lead to the Overworld; use `/warp cities` to return to cities. Applied live; no server restart or new mod. AutoModpack delivers the matching config on a later launch.

Profile 1.0.35 updates Jade to 11.13.3 and Jade Addons to 5.5.1.

Profile 1.0.36 adds Butchercraft and Extra Delight with Forge compatibility fixes and a Farmer's Delight world migration.
