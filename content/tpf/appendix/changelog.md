---
title: "Changelog"
weight: 3
type: docs
description: >
  For all versions since the Github release (4.0 and later).
---

## Release 4.6.2

> 06/07/2021

As it turns out the [**Aspens Ablaze Billboards**](https://www.nexusmods.com/skyrimspecialedition/mods/51135) played a huge role in the performance issues present in the latest versions of TPF. The performance loss could be as high as 20FPS which I do not consider worth the visual improvement. In fact, I would argue that the original billboards blend better with the non-LOD trees. Check this [**comparison slider**](https://imgsli.com/NjAxMDM) to see the difference in both visuals and performance. The mod was removed from TPF and, as a result of that, your framerate in the Rift should be much improved.

**The performance impact of TPF 4.6.2 is still larger than in 4.5.x and earlier versions.** However, the performance guide really should fix this for most people; particularly regenerating INI files on BethINI Medium and/or regenerating DynDOLOD without 3D tree LOD should help.

Otherwise, the alchemy workbenches are fixed (reinstall and run Revamped Assets Skyrim through SSE NIF Optimizer instead of CAO) and you should no longer fall to your death during Meridia's quest (remove havok tweak from your skyrimcustom.ini file).

#### How to Update

- Regenerate TexGen and DynDOLOD ([instructions](https://thephoenixflavour.com/tpf/guide-resources/how-to-update/#dyndolod)).
- You can keep your old Occlusion output, but disable it while you regenerate TexGen and DynDOLOD.
- **Wabbajack:** Also copy over GFF again (ENBSeries binaries updated).

#### Initial Setup

- **Additional Tools:** Removed zEdit (no longer needed for any steps).

#### Mod Installation

- **Interface:** Removed Loading Screen Smoke Removed.
- **Interface:** Added Menu and Load Smoke Removed for ENB.
- **Interface:** Removed KenMOD - Time on Loading Screen (file was removed from the Nexus).
- **Graphics Baseline:** Now using SSE NIF Optimizer instead of CAO on Revamped Assets Skyrim.
- **Trees & Plants:** Removed Aspens Ablaze Add-On - DynDOLOD 3 (unreasonable performance impact).
- **Trees & Plants:** Removed INI Tweaks for Cathedral - 3D Pine Grass (they are fairly unnecessary).
- **Architecture:** Updated download instructions for Shingles - Alpha Patch (file name changed).
- **Interiors:** Now using the 1K textures instead of 2K for SD's Horn Candles.
- **Apparel & Weapons:** Fixed download instructions for Stalhrim Refrozen.
- **Improved Vanilla Quests:** Updated download instructions for Andrealphus' Tweaks - Harder Quests (file names updated).
- **Skeleton & Animations:** Updated additional instructions for Simple Dual Sheath (lines changed).
- **Skeleton & Animations:** Removed INI tweak instructions for Jumping Behaviour Overhaul (would kill you during Meridia's quest).

#### Performance Guide

- Added a new INI tweak that can be done instead of regenerating BethINI from scratch.
- Elaborated on which setting godrays should be set to in the BethINI settings.
- Added instructions to lower the fBlockLevel1Distance value when reconfiguring INIs through BethINI.
- Removed grass density tweak from the BethINI instructions (leave at default).
- Added grass density instructions to the Grass Overhaul section.
- Fixed a pretty bad typo in the DynDOLOD section (use the Performance profile, not the Optimal one).

#### Conflict Resolution Patch

- Re-enabled one of the temper recipes for the Champion's Cudgel (we have three and all three were, somehow, disabled).
- Forwarded new Adamant keywords for bound equipment (4.6.1.1).
- Disabled WACCF's alternative iron helmet (4.6.1.2).

#### Wabbajack

- Updated ENBSeries (version number unchanged)
- Updated Dlizzio's Mesh Fixes to 2.3
- Updated Shingles - Alpha Patch to 1.2.0
- Updated Adamant - A Perk Overhaul to 5.0.3
- Updated Open World Loot to 1.2.9
- Updated Dragon War - A Dragon Overhaul to 1.0.5
- Updated Misc Tweaks - Shrines Don't Cure Diseases to 1.8
- Updated Open World Loot - AVL Morrowind Glass Addon to 1.1
- Updated Simple Dual Sheath to 1.4.1
- Replaced Beast Race Vampire Fang Removal SLE with SSE version

## Release 4.6.1

> 29/06/2021

Here is the first round of fixes for TPF 4.6 as expected. Since the update was larger than usual, I seem to also have messed up more (sorry). Huge thanks go to all the wonderful people who left feedback on Discord!

We are currently investigating potential performance issues going beyond the increase that we had expected to see in the update. Anybody currently experiencing performance issues should use the performance guide/profile. If you have the time, please also leave us some feedback on Discord!

#### Mod Installation

- **Essential Mods:** Fixed download instructions for WACCF Greatsword Weapon Speed Tweaks (Misc File instead of Main File).
- **Essential Mods:** Updated download instructions and screenshot for Skyrim Particle Patch.
- **Fixes:** Fixed link for Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch (pointed to description instead of files page).
- **Interface:** Fixed additional instructions for Convenient Reading UI (setting to edit is in Line 12 instead of 11).
- **Graphics Baseline:** Fixed link and download instructions for Perfect Terrain LOD.
- **Graphics Baseline:** Fixed download instructions for Unofficial Material Fix - Assorted Mesh Fixes Patch (copy-paste error).
- **Landscape:** Fixed download instructions for Skyrim - A Mountainous Experience (file name changed).
- **Architecture:** Added Marketplace Shingles - Alpha Patch.
- **Unique Artifacts:** Removed 2K Black Bow of Fate (late note for 4.6 in which the Unique Artifacts step was also removed).
- **Creatures:** Added Particle Lights for ENB - Wisps (late note for 4.6).
- **Gameplay Overhauls:** Updated Reliquary of Myth FOMOD instructions.
- **Assorted Plugins:** Fixed link for Classic Paralysis (now properly leads to the Files section).

#### Finalisation

- **Wrapping Up:** Updated load order warning: There should be no plugin below the Facegen plugin.
- **Wrapping Up:** Removed NoMoreFollowerHuntingBow.esp from the list of plugins to ESL-ify (it was rolled into the CRP).
- **SSELODGen:** Updated the AQWM conflicts screenshot (the files now also conflict with Base Coat).
- **DynDOLOD:** Fixed the file path to the DynDOLOD_SSE.ini in the INI Adjustments section.

#### Performance Guide

- Added note to the grass overhaul section that The Phoenix Flavour - Grass Patch must also be disabled.

#### Wabbajack

- Fixed about a dozen mods being inactive because I forgot to sync with the main profile
- Updated Dlizzio's Mesh Fixes to 2.2
- Updated Adamant - A Perk Overhaul to 5.0.2
- Updated Dragon War - A Dragon Overhaul to 1.0.4

## Release 4.6

> 28/06/2021

The Phoenix Flavour 4.6 is probably the most substantial update since 4.0 came out. I'm overall very happy with everything I managed to squeeze in and for the first time since TPF originally came out, I have no immediate plans for the next update.

**Please consider 4.6 a beta release.** Like all major updates, this, too, is likely to contains oversights, typos, missing links, wrong FOMOD instructions, or my trademark cut-off sentences. Please bear with me and report your findings on Discord (`#tpf-feedback`). Wait for 4.6.1 if you'd rather have a more polished experience.

- Adamant 5 and other SimonRim updates.
- Open World Loot integration (a new loot overhaul).
- Increased performance impact due to new INI and DynDOLOD configurations.
- Rudy ENB with Rudy's Cathedral Weathers tweaks and DLVaSS are now default.
- A brand-new performance guide with various options to improve your FPS.
- Grass Cache was removed. Pre-made facegen will now be provided for download.
- Added Modular Armory which I made specifically for TPF.
- Added Simple Smithing Overhaul with some tweaks.
- More dense grass and better swamp grass.
- Much better glacier and ice assets (multilayered parallax).
- Switching from AllGUD to Simple Dual Sheath (AllGUD is now part of TPF-X).
- Roboto Font Replacer was moved to TPF-X. Sovngarde Font is now TPF default.

**About the Performance Guide:**

As you may have noticed from the above feature list, TPF 4.6 is even more demanding on your hardware than previous versions. Our INI settings are now based on the BethINI High preset and the DynDOLOD configuration is on High with 3D tree LOD by default.

However, you can still enjoy TPF on mid- to low-end hardware!

The new performance guide covers a variety of performance improvements: Regenerating INI files, the return of Cathedral Landscapes for FPS-friendly grass, ENB alternatives, a performance configuration for DynDOLOD, and optionally scaling down the resolution.

Users of the manual guide can apply whichever of the tweaks they like.

For Wabbajack, there will be a second "Performance" profile available in Mod Organizer 2 with DynDOLOD on Medium with 2D tree LOD, optimised INI settings, and less FPS-hungry grass mods. The Game Folder Files folder will also include both Rudy ENB and Serio's ENB for you to choose from.

**About Cathedral Assets Optimizer:**

CAO updated multiple times in the past weeks but there were lingering issues with each new release and they once again reverted to the (stable) 5.0.15 which we used for a long time. The guide will do the same thing.

If you used CAO 5.1.3 or 5.2.0:

- Revert to Cathedral Assets Optimizer 5.0.15.
- Go through the entire guide to find mods with CAO instructions.
- Reinstall those mods, then process them with CAO 5.0.15.

**About the removal of grass cache:**

A sizeable portion of users (including myself) has reported mild stutters caused by grass cache. There are some workarounds but they mostly defeat the point of generating grass cache to begin with. Thus I decided to drop it. It's unfortunate because grass cache is the single best way to check for repeatable crashes but there are still too many issues with it (the stutters, cells sometimes randomly don't have grass, etc).

And it means one less patcher to run so there's that.

**About the switch from AllGUD to Simple Dual Sheath:**

Recently a much simpler dual sheath mod than AllGUD was released that does not require any patching or mesh edits whatsoever. [Simple Dual Sheath](https://www.nexusmods.com/skyrimspecialedition/mods/50049) is just a SKSE plugin, completely plug and play. Of course, [AllGUD](https://www.nexusmods.com/skyrimspecialedition/mods/28833) has far more features than just dual sheaths so I did not remove it entirely. You can now find instructions for the mod and all additional steps in TPF-X.

**About the facegen changes:**

We traced down a bug with Urag gro-Shub's facegen to the Creation Kit starting to stumbled over its own feet when generating all facegen at once (in this case, the bug could be fixed by skipping the six Snow Elves when generating facegen). Since facegen apparently absolutely *has* to be generated in small batches, I figured it would be easier to simply provide pre-made facegen for everyone after all. The facegen step in Finalisation was removed entirely.

**About the music mod changes:**

I finally decided to move all mods adding to music, including my merged plugin, to TPF-X (the official TPF addon). Support and instructions for them all still exist, just not in the default guide.

#### How to update

- **New save required.**
- Regenerate INI files ([instructions](/tpf/guide-resources/various-tutorials/#how-to-re-generate-ini-files-from-scratch)).
- Update [SSELODGen](https://stepmodifications.org/forum/topic/13451-xlodgen-terrain-lod-beta-82-for-fnv-fo3-fo4-fo4vr-tes5-sse-tes5vr-enderal-enderalse/), delete your old terrain LOD output, and regenerate it ([instructions](/tpf/finalisation/sselodgen/)).
- Rerun TexGen, DynDOLOD, and Occlusion ([instructions](/tpf/guide-resources/how-to-update/#dyndolod)).
- **Wabbajack:** Reinstall Game Folder Files (ENBSeries updated).

#### Introduction

- General minor updates (fixes, small additions, rephrased sections).
- Clarified that the new music tracks in the TPF playlist are now part of TPF-X and no longer in the base guide.
- Added a section to introduce the new TPF addons.
- Updated the Phoenix's Build section (~~gotta plug that sweet, sweet 3080~~).
- Added warning to check Discord for news before starting the guide.

#### Initial Setup

- **Skyrim and Steam:** Rewrote many instructions on this page and added a new screenshot.
- **Skyrim and Steam:** Added a link to LostDragonist's Steam Library Setup Tool.
- **Creation Kit:** Fixed link to Betheda.net being localised (it would open the German version, oops).
- **Mod Organizer 2:** Updated link and picture for MO2 2.4.2 (latest).
- **Mod Organizer 2:** Added a new Splash Screen section.
- **INI Files:** Updated almost all steps in the BethINI configuration (now based on the High preset).
- **Additional Tools:** Updated instructions for CAO (reverted to 5.0.15).
- **Additional Tools:** Removed instructions for Modwat.ch (no longer necessary with Load Order Library).

#### Mod Installation

- **Essential Mods:** Updated INI lines for SSE Display Tweaks (changed in recent update).
- **Essential Mods:** Removed instructions to disable VSYNC for SSE Display Tweaks (it should be on for everyone).
- **Essential Mods:** Added instructions to use SSE Display Tweaks to block load screens from certain plugins.
- **Essential Mods:** Added a note about capping the framerate to SSE Display Tweaks.
- **Essential Mods:** Updated download instructions for More Informative Console (file name changed).
- **Essential Mods:** Re-added Dear Diary - Better More Informative Console.
- **Essential Mods:** Removed Project Clarity AIO - Skyrim Textures Redone.
- **Essential Mods:** Added Base Coat.
- **Essential Mods:** Removed Hooded Skeleton Corpse Fix for WACCF (was fixed in WACCF 2.2).
- **Essential Mods:** Added WACCF Greatsword Weapon Speed Tweaks.
- **Essential Mods:** Updated the INI tweak section for No Grass In Objects.
- **Fixes:** Added powerofthree's Tweaks.
- **Fixes:** Added instructions to also download the Scrambled Eggchantments main file for Scrambled Bugs.
- **Fixes:** Added instructions to also download the Soul Gem Too Small file for Scrambled Bugs.
- **Fixes:** Updated additional instructions for Scrambled Bugs.
- **Fixes:** Added Assorted Mesh Fixes.
- **Fixes:** Added Skyrim Particle Patch for ENB - Assorted Mesh Fixes - Solitude Mesh Fixes Patch.
- **Fixes:** Added Dlizzio's Mesh Fixes.
- **Fixes:** Added Dlizzio's Mesh Fixes - Assorted Mesh Fixes Patch.
- **Fixes:** Updated No Animals Report Crimes download instructions (version number increased).
- **Fixes:** Removed Fixed Dragon Stalking Fix (part of Dragon War - A Dragon Combat Overhaul).
- **Fixes:** Updated download instructions for NPC AI Process Position Fix (file name changed).
- **Fixes:** Added hank's Gamepad and Controller Fixes.
- **Tweaks:** Updated FOMOD instructions for Dwemer Gates Don't Reset.
- **Tweaks:** Removed No Hunting Bows for Followers (single record, now included in the CRP).
- **Interface:** Removed No More Laser-Printed Book.
- **Interface:** Added Convenient Reading.
- **Interface:** Moved Roboto Font Replacer to TPF-X.
- **Interface:** Moved Sovngarde Font Replacer from TPF-X to the main guide. It's now the new default.
- **Graphics Baseline:** Added Dlizzio's Mesh Fixes - HD LODs Textures SE Mesh Fix.
- **Graphics Baseline:** Added instructions to delete the meshes\actors\ambient\ folder from Static Mesh Improvement Mod.
- **Graphics Baseline:** Added SMIM - Assorted Mesh Fixes Patch.
- **Graphics Baseline:** Added Unofficial Material Fix.
- **Graphics Baseline:** Added Unofficial Material Fix - Assorted Mesh Fixes Patch.
- **Graphics Baseline:** Added SMIM - Quality Addon - Unofficial Material Fix Patch.
- **Graphics Baseline:** Added Quality Cubemaps - HD Cube Maps.
- **Graphics Baseline:** Added instructions to also create a projectednormal.dds from Noble Skyrim's snow01_n.dds texture.
- **Graphics Baseline:** Added Dlizzio's Mesh Fixes - Noble Skyrim Material Fix.
- **Graphics Baseline:** Moved aMidianBorn Book of Silence to the CREATURES step.
- **Graphics Baseline:** Added Unofficial Material Fix - High Poly Project Patch.
- **Weather:** Moved Dynamic Volumetric Lighting and Sun Shadows here (from TPF-X).
- **Weather:** Moved Rudy ENB - Cathedral Weathers here (from TPF-X).
- **Lighting:** Updated download instructions for Luminosity (now using the new 4.2 version).
- **Visual FX:** Added TB's Improved Dust Particles.
- **Visual FX:** Removed Ljoss - Mage Light Fix.
- **Visual FX:** Removed Fire Halo Remover (covered by Dlizzio's Mesh Fixes).
- **Visual FX:** Moved Bright Snow Fix here (from TPF-X).
- **Landscape:** Removed Majestic Mountains - Mesh Tangent Space Fixes (incorporated in Skyrim - A Mountainous Experience).
- **Landscape:** Moved Skyrim - A Mountainous Experience (previously called Markarth - a Mountainous Experience) here.
- **Landscape:** Added a note to Moss Rocks to explain why we're using it instead of Majestic Mountains' moss module.
- **Landscape:** Added WalkWayCWall01 NIF - SLaWF SMIM BDS Patch.
- **Landscape:** Updated Skyrim Remastered - Glaciers and Ice download instructions.
- **Landscape:** Removed Skyrim 3D Icefloes.
- **Landscape:** Added Glacierslab.
- **Landscape:** Added SC - Glacierslab Addon.
- **Landscape:** Added Assorted Mesh Fixes - SMIM - Really Blended Roads Patch.
- **Trees & Plants:** Changed download instructions for Enhanced Vanilla Trees.
- **Trees & Plants:** Updated FOMOD instructions for Enhanced Vanilla Trees.
- **Trees & Plants:** Added Aspens Ablaze Add-On - DynDOLOD 3.
- **Trees & Plants:** Added instructions to delete another folder from HD Dead Trees and Driftwood.
- **Trees & Plants:** Added High Poly Canticle Tree.
- **Trees & Plants:** Updated FOMOD instructions for Veydosebrom Regions.
- **Trees & Plants:** Removed INI tweak instructions for Veydosebrom Regions (moved to BethINI).
- **Trees & Plants:** Added instructions to also download the High Poly Green Grass Update for Cathedral 3D Pine Grass.
- **Trees & Plants:** Added The Phoenix Flavour - Grass Patch.
- **Trees & Plants:** Removed Cathedral Plants (part of Base Coat).
- **Trees & Plants:** Added Improved Gourds.
- **Trees & Plants:** Added Rally's Blackreach Mushrooms.
- **Architecture:** Removed Markarth - A Reflective Experience (tweaks part of The Dwemer).
- **Architecture:** Removed Solitude Mesh Fixes (all fixes contained in Assorted Mesh Fixes and another patch).
- **Architecture:** Added Unofficial Material Fix - Stone Solitude Castle Floor.
- **Architecture:** Removed Castle Volkihar Reborn.
- **Architecture:** Added CC's Castle Volkihar Remastered.
- **Misc Structures:** Added Remiros' Dunmer Urns HD.
- **Misc Structures:** Updated additional instructions for Iconic Statues.
- **Misc Structures:** Added Remiros' Statues HD.
- **Interiors:** Added instructions to also install the STAC patch for SD's Horn Candles (an oversight, thanks Althro!).
- **Dungeons:** Removed Gecko's Dwarven Ruins Textures (prefer Noble Skyrim).
- **Dungeons:** Moved Metallurgy - Ingots and Ores HD to Clutter.
- **Dungeons:** Removed Ice Cave Parallax Improved.
- **Dungeons:** Added Skyrim Remastered - Caves.
- **Dungeons:** Added Skyrim Remastered - Azura and Blackreach Crystals
- **Dungeons:** Removed ElSopa Realistic Dark Elf Urns.
- **Dungeons:** Removed Ancient Dwemer Metal.
- **Dungeons:** Removed Dwemer Pipework Reworked.
- **Dungeons:** Removed Ancient Dwemer Metal - My Patches for SMIM Dawnguard Dragonborn.
- **Dungeons:** Removed Dwemer Ichor Barrel.
- **Dungeons:** Removed ENB Particle Lights - Dwemer Lanterns - Ancient Dwemer Metal Patch.
- **Dungeons:** Removed Rudy HQ - Bthardamz - Dwemer Ichor Barrel Patch.
- **Dungeons:** Added The Dwemer.
- **Dungeons:** Added Particle Lights for ENB - Light Orbs.
- **Dungeons:** Added Aetherium Falmer Cave Ceiling Glow.
- **Dungeons:** Added Skyrim Remastered - Azura and Blackreach Crystals.
- **Clutter:** Added instructions to remove some files from RUSTIC CLUTTER COLLECTION.
- **Clutter:** Removed Business Ledger HD Retexture.
- **Clutter:** Added The Business Ledger.
- **Valuable Items:** Removed ElSopa HD - Dragonborn Skull Variants.
- **Valuable Items:** Added Iconic's Saerek and Torsten Skull Key Retexture (closer to vanilla).
- **Apparel & Weapons:** Added Modular Armory.
- **Apparel & Weapons:** Removed Cathedral Armory (superseded by Modular Armory).
- **Apparel & Weapons:** Removed Project Clarity - Weapons - TPF Repack (superseded by Modular Armory).
- **Apparel & Weapons:** Removed Warmth - Light Armors Replacer temporarily (need to patch for Modular Armory).
- **Apparel & Weapons:** Added Modular Armory - Armor Mesh Fixes Patch.
- **Apparel & Weapons:** Updated FOMOD instructions for LeanWolf's Better-Shaped Weapons.
- **Apparel & Weapons:** Removed Ancient aMidianBorn Dwarven Armory.
- **Apparel & Weapons:** Removed Ancient Dwemer Metal - My Patches - No Smiling Female Helmet.
- **Apparel & Weapons:** Removed aMidianBorn Stormcloak Officer Armour (part of Modular Armory).
- **Apparel & Weapons:** Removed Actual Orichalcum Orcish Equipment.
- **Apparel & Weapons:** Added aMidianBorn Matching Armory - Glass Armor and Weapons.
- **Apparel & Weapons:** Removed Outlandish Stalhrim.
- **Apparel & Weapons:** Added Stalhrim Refrozen.
- **Apparel & Weapons:** Removed Outlandish Chitin Armour (part of Modular Armory).
- **Apparel & Weapons:** Removed Rudy HQ - Daedric Weapons and Armor (don't currently have a patch for Modular Armory).
- **Apparel & Weapons:** Removed Dragon Priest Weapons Improved (part of Modular Armory).
- **Apparel & Weapons:** Added Modular Armory - Masks of the Dovah Sonaak Patch.
- **Apparel & Weapons:** Added Unique Uniques Re-Ported.
- **Unique Artifacts:** Merged with Apparel & Weapons page since most mods were consolidated into Modular Armory.
- **Unique Artifacts:** Removed Unique Uniques.
- **Unique Artifacts:** Removed Unique Uniques - Fixes.
- **Unique Artifacts:** Removed HD Reflective Ebony Mail.
- **Unique Artifacts:** Removed Remiros' Dawnbreaker (part of Modular Armory).
- **Unique Artifacts:** Removed Remiros' Ebony Blade HD (part of Modular Armory).
- **Unique Artifacts:** Removed Remiros' Wabbajack HD (part of Modular Armory).
- **Unique Artifacts:** Removed Remiros' Ancient Falmer Armor HD (part of Modular Armory).
- **Unique Artifacts:** Removed Harkon's Sword - HD Retexture (part of Modular Armory).
- **Unique Artifacts:** Removed Unique Zephyr.
- **Unique Artifacts:** Removed Remiros' Bloodskal Blade (part of Modular Armory).
- **Unique Artifacts:** Removed Remiros' Hrothmund's Axe HD (part of Modular Armory).
- **Unique Artifacts:** Removed Aevrigheim - Miraak's Sword and Staff Replacer (part of Modular Armory).
- **Creatures:** Added Particle Lights for ENB - Undead Creatures.
- **Creatures:** Updated download instructions for Real Rabbits HD.
- **Creatures:** Removed Ancient Automatons (replaced by The Dwemer).
- **Creatures:** Removed Ancient Dwemer Metal - Missing Forgemaster Fix (replaced by The Dwemer).
- **Creatures:** Added additional instructions for HD Reworked Dragons 4K.
- **Creatures:** Re-added RUSTIC DRAGONS.
- **Creatures:** Re-added HD Serpentine Dragon and Mesh Fix.
- **Creatures:** Updated download instructions for Deiform Alduin (using 4K textures instead of 8K).
- **Creatures:** Added instructions to also download the Deiform Alduin Eyes textures.
- **Appearance:** Added Superior Lore-Friendly Hair.
- **Appearance:** Added instructions to delete a file from Authentic Eyes.
- **Gameplay Overhauls:** Updated download instructions for Adamant - A Perk Overhaul (file name changed).
- **Gameplay Overhauls:** Updated download instructions for Skyrim Uncapper - Adamant Arena (now using the Phoenix cut).
- **Gameplay Overhauls:** Updated Forceful Tongue - Shouts Overhaul FOMOD instructions.
- **Gameplay Overhauls:** Added Open World Loot.
- **Gameplay Overhauls:** Updated Reliquary of Myth FOMOD instructions (no longer selecting the Ebony Blade patch).
- **Gameplay Overhauls:** Added Modular Armory - Reliquary of Myth Patch.
- **Gameplay Overhauls:** Added Unique Item Tweaks.
- **Gameplay Overhauls:** Added Simple Smithing Overhaul.
- **Gameplay Overhauls:** Updated download instructions for Lightweight Smithing Tweaks.
- **Gameplay Overhauls:** Added Enchanting Adjustments Updated.
- **Improved Vanilla Quests:** Added Silence Is Golden.
- **Combat & Encounters:** Added Dragon War - A Dragon Combat Overhaul.
- **Combat & Encounters:** Removed Arena - An Encounter Zone Overhaul (replaced by Open World Loot).
- **Combat & Encounters:** Removed Splendor - Dragon Variants (replaced by Dragon War - Variants).
- **Combat & Encounters:** Added Briraka's Draugr Overhaul.
- **Combat & Encounters:** Added Briraka's Draugr Overhaul - Cannibal Draugr Patch.
- **Balancing:** This step is just too vague, moved everything to Gameplay Overhauls with some exceptions:
- **Balancing:** Moved Faster Mining Plus to Miscellaneous.
- **Balancing:** Moved Craftable Lockpicks to Miscellaneous.
- **Balancing:** Moved Craftable Torches to Miscellaneous.
- **Balancing:** Moved Reasonable Quest Rewards to Improved Vanilla Quests.
- **Balancing:** Moved Bounty Preview to Miscellaneous.
- **Balancing:** Removed Enchanting Adjustments and Price Bug Fix.
- **Balancing:** Removed Less Cure Disease Potions.
- **Balancing:** Removed Morrowloot Miscellania - Unleveled Uniques.
- **New Content:** Removed aMidianBorn Variants Lite.
- **New Content:** Removed Practical Female Armors - AMB AVL Patch.
- **New Content:** Added Open World Loot - AMB AVL Addons.
- **New Content:** Added Open World Loot - WACCF and ACE Patch.
- **New Content:** Added Ancient Nord Stalhrim.
- **New Content:** Added Open World Loot - Ancient Nord Stalhrim and Briraka's Draugr Overhaul Patch.
- **Miscellaneous:** No longer downloading Misc Tweaks - More Realistic Animal Loot.
- **Miscellaneous:** Now also downloading the Misc Tweaks - Night Eye Redux - ENB Fix (was part of TPF-X).
- **Miscellaneous:** Removed now redundant FOMOD instructions for Misc Tweaks - Shrines Don't Cure Diseases.
- **Miscellaneous:** Added Imperial Military Camps.
- **Assorted Plugins:** Added instructions for Enhanced Reanimation to manually create the INI file.
- **Assorted Plugins:** Added instructions for Essential Favorites to manually create the INI file.
- **Assorted Plugins:** Removed No Attack Messages (now a feature in powerofthree's Tweaks).
- **Sound FX:** Renamed this step to "Sound FX" from "Sounds & Music" as the music mods were moved to TPF-X.
- **Sound FX:** Added Thunder Sounds - WiZkiD Mix.
- **Sound FX:** Added Realistic Dog Sounds.
- **Sound FX:** Removed Musical Lore - Soundtrack Mod by Nir Shor (now part of TPF-X).
- **Sound FX:** Removed The Northerner Diaries - Immersive Edition (now part of TPF-X).
- **Sound FX:** Removed Still - Skyrim Inspired Music (now part of TPF-X).
- **Sound FX:** Removed Hun Lovaas - Skyrim Fan-Made Combat Music (now part of TPF-X).
- **Sound FX:** Removed Melodies of Civilization - Skyrim Fan-Made Music (now part of TPF-X).
- **Sound FX:** Removed Around the Fire - Skyrim Fan-Made Music (now part of TPF-X).
- **Sound FX:** Removed Dawnguard Music Overhaul - Skyrim Fan-Made Music (now part of TPF-X).
- **Sound FX:** Removed Yet Another Music Merge (now part of TPF-X).
- **Skeleton & Animations:** Moved All Geared Up Derivative (AllGUD) to TPF-X.
- **Skeleton & Animations:** Moved AllGUD Conditions Fix to TPF-X.
- **Skeleton & Animations:** Added Simple Dual Sheath.
- **Skeleton & Animations:** Added instructions to remove some files from Dragon Animations Replacer.
- **Utilities:** Removed Private Profile Redirector (apparently it still does mess up ENBs).
- **Utilities:** Updated download instructions for Spell Perks Item Distributor (file name changed).

#### Finalisation

- **Wrapping Up:** Added instructions to download and install the new premade facegen.
- **Wrapping Up:** Added Veydosebrom to the list of plugins to ESL-ify.
- **Wrapping Up:** Added Cathedral 3D Pine Grass to the list of plugins to ESL-ify.
- **Wrapping Up:** Removed the music mod plugins from the list of plugins to ESL-ify.
- **Facegen:** Removed this step. Premade facegen is now provided.
- **Nemesis:** Added a note on a potential fix if Nemesis stalls at 99% progress.
- **AllGUD:** Removed this step. We are now using Simple Dual Sheath. AllGUD was moved to TPF-X.
- **Grass Cache:** This page was removed for the forseeable future.
- **DynDOLOD:** Added INI Adjustments section (for expert mode and DVLaSS terrain underside mesh).
- **DynDOLOD:** Updated TexGen settings.
- **DynDOLOD:** Now using the STEP Optimal preset for DynDOLOD (updated instructions).
- **DynDOLOD:** Removed instructions to manually delete the loading screens (done automatically by SSE Display Tweaks).
- **ENBSeries:** Updated the page to refer to Rudy ENB instead of Serio's ENB.

#### Wabbajack

- Removed Game Resolution section (Wabbajack adjusts the resolution automatically to match your monitor).
- Updated the Game Folder Files instructions to account for the two different ENB presets that are now available.
- Removed VSYNC instructions (VSYNC is now enabled by default).
- Updated instructions in the Uncap Framerate section.

#### Mod Configuration

- Added a clarification on when it is best to take care of configuring the MCMs.
- Removed AllGUD MCM instructions.
- Added Simple Smithing Overhaul MCM instructions.

#### Appendix

- **Changelog:** Removed pre-4.0 changelogs (no longer relevant and this page is getting too long).

#### Conflict Resolution Patch

**Changes by Phoenix:**

- Fixed a few typos in Civil War Deserters
- Removed Less Cure Disease Potions as a master
- Adjustments for Reliquary of Myth and Unique Item Tweaks
- Removed chance for ROM's new ingredients to be harvestable from Spriggans killed with Nettlebane
- ROM's Dremora Archers are no longer wearing weird skimpy Daedric armor
- Resolved conflicts with WACCF Greatsword Weapon Speed Tweaks
- Updated various records for Enchanting Adjustments Updated
- The unique Poacher's Axe is no longer disenchantable
- Removed AMB Armor Variants Lite as a master
- Overwrote an unresolved error in Imperial Military Camps
- Removed some edits that were workarounds for Skyrim Remastered - Glaciers and Ice

**Umgak's general adjustments**

- Removed any old edits that are no longer necessary.
- Fixed many, many typos.
- Forwarded Luminosity 4.2 values in various cell records.
- Forceful Tongue FExxx80D "Ice Form" will now use Immersive Sounds firing noise.
- Forwarded USSEP changes into 00054226 "Bronze Water Cave" and 000778F1 "Robber's Cove".
- Made a specific Quicksilver Ingot (REFR: 000CD6F1) near Ennodius Papius accessible per USSEP (RW2 was reverting it).
- Fixed far more books than I'm bothering to list. It's a lot, okay? Book Covers Skyrim needs an update.
- Skyforge Steel Greatsword will now use WACCF values, minus its speed, per WACCF Greatsword Weapon Speed Tweaks.
- Various bandit bosses have had the Skull Crusher and Bone Breaker perks removed per USSEP (the perks don't work correctly on the player and the NPCs don't even have the prerequisite perk).
- Forwarded a couple of EDIDs (no gameplay changes).
- Fixed a couple of incompatibilities between Better Dynamic Ash and SMIM near Hrodulf's House.
- Fixed the Wolf Guardian Spirit Kyne's Sacred Trials being vulnerable to disintegrate and paralysis unlike regular ghosts, and not being affected by spells targeting Undead or Ghosts.
- Corrected a clunky subtitle in the College of Winterhold questline.
- Corrected a number of clunky subtitles in Tolfdir's dialog.
- Ensured that three Aspen trees which Better Dawnguard Entrance requires to be removed remain removed, instead of being re-enabled by Aspens Ablaze.
- Forwarded aspen tree position fixes from Landscape and Water Fixes, fixing a number of 'floating tree' errors.
- Forwarded a USSEP fix into the Tier 75 Alteration spellbooks table from Mysticism, fixing an inconsistency present in vanilla in which all T75 spells will appear at character level 35, *except* for Alteration's, which only appear at both level 35 CL and 75 Alteration.
- Corrected scrolls of Reanimate Corpse using the weaker Raise Zombie effect instead when using Mysticism. This bug is a vanilla bug which is corrected by USSEP.
- Added VendorItemScroll keyword to Scroll of Dead Thrall.
- Hid the Bound Battleaxe and Bound Bow FX enchantments from being shown in the magic UI as they were reverted by Adamant.
- Removed Alteration as the magic skill for Khajiit Unarmed Damage effect.
- Forwarded USSEP script edit into the Vampire reanimate effects from Scion, which should cause living actors hit by it to become hostile.
- Forwarded USSEP's text into the vampire side of the Dawnguard questline "Prophet".
- Removed Night Eye script from Forceful Tongue.
- Gave Gormlaith's summoned form the inventory a period-accurate shield per BriDraugrOverhaul, but kept her FT perks and stats.
- Reduced the number of enchanted robes received from Warlock chests from 2 to 1.
- Forwarded a slot tweak on the Nightingale Helmet from WACCF to Reliquary of Myth so that it will no longer hide the Circlet slot.
- Vendors will now be slightly disgusted at the propsect of buying human hearts.
- Guards will now comment on the Ring of Namira being in your possession less often.
- Guards will now comment less on the player smelling like a wet dog.
- Corrected stats of Skyforge Steel Sword while still allowing Guards to comment on it.
- Hunters will no longer speak in typos while talking about how their poaching isn't hurting anyone, and the Jarl can hardly eat every deer now can he.
- Hunters will no longer speak in typos while saying that they'll conquer the Reach, they'll also not say that to animals.
- The player now "owns" the Hearthfire bed (I mean, you built it yourself).
- Removed the "How about my new home?" option from marriage dialogue as there are no new home mods in TPF.
- Removed a glitched script from the "whining child" dialogue.
- The children at Honorhall will no longer report you to the guards for murdering Grelod the Kind, because she sucks.
- Repaired a large portion of the Adoption script.
- Jaree-Ra's quest is now declinable.
- Redoran Guards will now be a bit less forthcoming about the werewolves in the mountains, the Deathbrand treasure, or Ralis' expedition, instead saying these lines only once per day.
- You can no longer 'feed' on a burnt spriggan. They don't have hearts. That's a burnt root, your wolf stomach can't process it.
- Leveled prey animals are now less likely to spawn at Hearthfire homes. In vanilla, they were predators! but also still wouldnt spawn.
- Removed a random light source from this one random goat's enable parent between Dawnstar and Whiterun.
- Removed script from 000B72A0 "Slow" - Bug Fixes is handling the slow effect fixes now, so this old script and legacy item are unnecessary.
- Mysticism's xx0CFBC1 "Ice Hazard" will now use the lovely Immersive Sounds firing noise.
- Corrected Mysticism's xx445FCF "Inferno" noises.
- Forwarded "On Local Map" flag to campfires in accordance with Embers HD, corrected OBND records (not that those really matter).

**Umgak's adjustments for Adamant 5.0.0:**

- Fixed Quick Draw for Weapon Speed Effects Fix.
- Fixed Dual Flurry for Weapon Speed Effects Fix.
- Gave Fire Rune its own unique projectile so that it can be distinct from the one from AOS.
- Forwarded new Chain Lightning Explosion effect.
- Forwarded new Reanimate spell.
- Forwarded condition to Blizzard spell.
- Forwarded new Firebrand perk effects.
- Forwarded new Flames spell.
- Forwarded AOS sounds to new Static Field and North Wind effects.
- Forwarded new conditions and name to Perfect Fit.
- Forwarded new conditions to DLC1DawnguardItemPerk.

#### Wabbajack

In 4.6, I removed the Tools folder in Mod Organizer 2. The primary reason for this is that it should not be used anyway: At least any LOD generating tools are supposed to be installed and generate output *outside* of MO2 directories. Additionally, Wabbajack users are not meant to use these tools anyway. If for whatever reason you absolutely need to rerun DynDOLOD, etc, you can refer to the manual guide for installation instructions (but there will be no support).

- Regenerated INIs
- Reverted to Cathedral Assets Optimizer 5.1.3
- Updated Mod Organizer 2 to 2.4.2
- Updated ENBSeries to 0.454
- Updated SSE Display Tweaks 0.4.15-1
- Updated More Informative Console to 0.43
- Updated Dear Diary - Better More Informative Console to 1.2
- Updated Unofficial Skyrim Special Edition Patch to 4.2.5b
- Updated Weapons Armor Clothing and Clutter Fixes to 2.4
- Updated Scrambled Bugs to 11
- Updated Skyrim Landscape and Water Fixes to 6.2
- Updated No Animals Report Crimes to 1.0.3
- Updated Bug Fixes SSE to 3
- Updated NPC AI Process Position Fix to 4.05b
- Updated Equip Enchantment Fix to 1.2.4
- Updated Dwemer Gates Don't Reset to 1.3.1
- Updated WoW Dragon Mounds CTD Fix to 1.2
- Updated Shadows Of Sunlight to 0.3
- Updated Majestic Mountains - LOD Pack for DynDOLOD to 1.2
- Updated Skyrim - A Mountainous Experience to 1.5.6
- Updated Whiterun Mesh Fixes to 1.1.5
- Updated Sovngarde HD to 3.1
- Updated Real Rabbits HD to 1.3
- Updated Deiform Alduin to 1.1 r
- Updated Mild Complexions to 2.0
- Updated Adamant - A Perk Overhaul to 5.0.1
- Updated Adamant - Shrines and Amulets to 5.0.3
- Updated Aetherius - A Race Overhaul to 2.5.2
- Updated Mundus - A Standing Stone Overhaul to 1.6.0
- Updated Scion - A Vampire Overhaul to 1.2.0
- Updated Forceful Tongues - Shouts Overhaul to 2.3.1
- Updated Dragon Aspect Overhaul to 2.0
- Updated Adamant - Trade and Barter Patch to 1.1
- Updated Reliquary of Myth to 3.9.2
- Updated Cannibal Draugr on Solstheim to 2.2
- Updated Forsworn Gravesingers to 1.0.1
- Updated Tweaks for WACCF and ACE to 1.6
- Updated Immersive Dragons to 1.4
- Updated Misc Tweaks - Shrines Don't Cure Diseases to 1.7
- Updated Classic Paralysis to 2.1
- Updated Enhanced Reanimation to 1.3
- Updated Essential Favorites to 2.1
- Updated Spell Perk Item Distributor to 4.4
- Removed ETHEREAL CLOUDS (mod was removed in TPF 4.5 but I forgot to delete it in MO2)
- Installed [LOOT Preventifier](https://github.com/LostDragonist/MO2-Plugins) for Wabbajack only

## Release 4.5.4

> 25/04/2021

Since More Informative Console was recently updated, I temporarily removed the Dear Diary MIC reskin in the last update (the author, uranreactor, is already aware and working on an update for the new version of MIC). Unfortunately, I forgot that my repack of those files also included the new font for the console for which the fontconfig.txt in Roboto was edited. After removing the font file with the Dear Diary - Better MIC mod, the console font was broken for everyone, whoops.

- Manual users need to reinstall Roboto to reset the config file to default.
- For Wabbajack users, it's fixed automatically when you update.

Wabbajack users also need to **reinstall the game folder files**. The enblocal.ini updated.

**This update is save-safe.**

#### Initial Setup

- **Additional Tools:** Removed instructions to download an older version of CAO (now using the latest).

#### Mod Installation

- **Interface:** Removed additional instructions to change console font for Roboto temporarily.
- **Trees & Plants:** Updated download instructions for Skyrim Flora Overhaul (file version changed).
- **Trees & Plants:** Updated additional instructions for Skyrim Flora Overhaul.

#### Finalisation

- **Facegen:** Fixed wrong line for the CK Fixes INI tweak (33 instead of 32 since last update).
- **Facegen:** Added instructions to create the zEdit/scripts/ folder which doesn't exist by default.
- **ENBSeries:** Added Fix Black Hair section.

#### Wabbajack

- Updated Cathedral Assets Optimizer to 5.1.3
- Updated CAO - Basic Profiles Pack to 1.5
- Updated More Informative Console to 0.42
- Updated Skyrim Flora Overhaul to 2.72H
- Updated Manbeast - A Werewolf Overhaul to 1.2.0
- Updated Reliquary of Myth - Artifact Overhaul to 3.8.1
- Updated Cannibal Draugr on Solstheim to 2.1
- Fixed broken console font
- Re-ran (hopefully) all relevant mods through the updated CAO
- Regenerated facegen and repacked with new version of CAO

## Release 4.5.3

> 18/04/2021

Contrary to my previous statement, TPF 4.5.2 didn't make it to Wabbajack after all but this update will. Sorry about the delay.

This update is **save safe**.

#### Mod Installation

- Small updates and typo fixes.
- **Essential Mods:** Updated download instructions for More Informative Console (file update).
- **Essential Mods:** Removed Dear Diary - Better More Informative Console console temporarily (MIC updated).
- **Tweaks:** Removed Helgen Keep Bandit Chief Executioner (redundant with Civil War Deserters).
- **Landscape:** Added Majestic Mountains - Mesh Tangent Space Fixes.
- **Architecture:** Updated download instructions for Rally's Raven Rock.
- **Architecture:** Added FOMOD instructions for Rally's Raven Rock.
- **Sounds & Music:** Slightly changed the mod order of the music mods.
- **Sounds & Music:** Added instructions to remove the plugin for Musical Lore - Soundtrack Mod by Nir Shor.
- **Sounds & Music:** Added instructions to remove the plugin for The Northerner Diaries - Immersive Edition.
- **Sounds & Music:** Added instructions to remove the plugin for Still - Skyrim Inspired Music.
- **Sounds & Music:** Added instructions to remove the plugin for Hun Lovaas - Skyrim Fan-Made Music.
- **Sounds & Music:** Added instructions to remove the plugin for Melodies of Civilisation - Skyrim Fan-Made Music.
- **Sounds & Music:** Added instructions to remove the plugin for Around the Fire - Skyrim Fan-Made Music.
- **Sounds & Music:** Added Dawnguard Music Overhaul - Skyrim Fan-Made Music.
- **Sounds & Music:** Removed Phoenix - Merged Music Patch.
- **Sounds & Music:** Added Yet Another Music Merge.

#### Finalisation

- **Facegen:** Small fix for the Tint Mask Resolution change in the CK Fixes INI (line number changed).

#### Conflict Resolution Patch

- Removed Helgen Keep Bandit Chief Executioner as a master

#### Wabbajack

- Regenerated DynDOLOD
- Updated SSE Display Tweaks to 0.4.11
- Updated More Informative Console to 0.41
- Updated Scrambled Bugs to 6
- Updated Rally's Raven Rock to 1.1
- Updated Mundus - A Standing Stone Overhaul to 1.5.1
- Updated Manbeast - A Werewolf Overhaul to 1.1.0
- Updated Blade and Blunt - A Combat Overhaul to 1.3.1
- Updated Free Look to 3.0

## Release 4.5.2

> 13/04/2021

Fixed a bunch of issues that were reported over the past couple of dayss. This update is **save-safe** but it requires users of the manual guide to rerun DynDOLOD (you can keep your TexGen output).

- [How to update DynDOLOD](/tpf/guide-resources/how-to-update/#dyndolod) for both manual and Wabbajack users.

#### Initial Setup

- **Additional Tools:** Added instructions to specifically download an older version of Cathedral Assets Optimizer.

#### Mod Installation

- Fixed a few more small typos and oversights.
- **Fixes:** Updated download instructions for Bug Fixes SSE (file name changed).
- **Valuable Items:** Removed Septim HD (coin pile mesh can cause crashes).
- **Valuable Items:** Added Ancient Imperial Septims.
- **New Content:** Removed note about Early Elementalist for Misc College of Winterhold Tweaks (no longer applies).
- **Assorted Plugins:** Updated download instructions for Free Look (file name changed).

#### Finalisation

- **DynDOLOD:** Updated outdated screenshot with DynDOLOD settings.

#### Conflict Resolution Patch

- Removed leftover edit to an Ash Spawn weapon from a mod I don't remember.
- Removed leftover edit to blacksmith water trough in Riften.
- Slapped bandaid on broken glaciers on Solstheim.

## Release 4.5.1

> 07/04/2021

Fixes for 4.5 as expected. Thanks to everyone on Discord who gave feedback and reported issues!

This version will also be available on Wabbajack shortly.

**Cathedral 3D Mountain Flowers:**

As mountain flowers go [these](https://www.nexusmods.com/skyrimspecialedition/mods/41312) are probably the most elaborate out there. I was very impressed by the new models and textures, and added them to TPF a few versions ago. Since then I've played the game quite a bit with them installed and I can no longer deny that they simply stick out. I just realised that their ESM has a bunch of conflicts with Skyrim Landscape and Water Fixes that I somehow managed to miss so that was the final nail in the coffin. The mod was removed in this update (not patching conflicts for a mod that's about to be removed anyway). Instead I added Skyrim Flora Overhaul (only the plant retextures) which is still an improvement over vanilla.

**Double enchantments:**

Up until very recently, double enchantments in Skyrim were bugged. This affected the Solstheim "Chaos Damage" enchantment (fire, frost, and shock) as well as the "Fortify <school\> & Magicka Regen" enchantment from the base game. These enchantments could be learned by the player, but when the player applied them to equipment, only one of the effects actually scaled with their Enchanting skill level while the other remained at "Novice" strength.

Previously this was worked around by the mod [Enchanting Adjustments](https://www.nexusmods.com/skyrimspecialedition/mods/8473) which replaced the enchantments learnt by single ones (Shock Damage for Chaos Damage and Fortify <school\> for Fortify <school\> + Magicka Regen). A better implementation might have been to flag all items with these enchantments as not disenchantable but that is far more work and creates compatibility issues.

Either way, this fix is no longer necessary because **KernalsEgg**, author of the new and brilliant [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532) mod, actually fixed it. I edited Enchanting Adjustment accordingly (through the CRP) so you can once again learn and use the double enchantments in question.

#### Mod Installation

- Fixed various typos.
- **Fixes:** Updated additional instructions for Scrambled Bugs (final INI tweak moved to line 16 by latest update).
- **Fixes:** Updated download instructions for Skyrim Landscape and Water Fixes (file name changed).
- **Fixes:** Updated FOMOD Instructions for Skyrim Landscape and Water Fixes.
- **Tweaks:** Added No More Follower Hunting Bows (undocumented 4.5 addition).
- **Tweaks:** Removed Fixed Body Collision (causes physics issues, "tripping" over bodies, etc).
- **Tweaks:** Fixed missing download instructions for True Teacher Durnehviir.
- **Interface:** Fixed explanation for A Quality World Map (now unpacking archive for SSELODGen).
- **Graphics Baseline:** Added instructions to create a projecteddiffuse.dds for Noble Skyrim (undocumented 4.5 addition).
- **Landscape:** Fixed download instructions for Skyrim Remastered - Glaciers and Ice (second download is in optional files).
- **Landscape:** Updated download instructions for Realistic Water Two (version number change).
- **Trees & Plants:** Added instructions to remove two textures from Cathedral Plants.
- **Trees & Plants:** Removed Cathedral 3D Mountain Flowers.
- **Trees & Plants:** Added Skyrim Flora Overhaul.
- **Trees & Plants:** Removed download instructions for the Fern main file from Flora Mod Collection.
- **Trees & Plants:** Added Skyrim High Poly Fern Meshes.
- **Trees & Plants:** Added Caveworm Plant Retexture.
- **Gameplay:** Added Dragon Aspect Overhaul (undocumented 4.5 addition).
- **Gameplay:** Removed Genuinely Intelligent Soul Gems (undocumented 4.5 removal).
- **New Content:** Added Armor of Yngol - WACCF Patch.

#### Finalisation

- **Wrapping Up:** Replaced example plugin for ESL-ifying (UniqueBorderGates-All-PointTheWay.esp was removed in 4.5).
- **Wrapping Up:** Removed Fixed body collision.esp from the list of plugins to ESL-ify (removed from the guide.)
- **Wrapping Up:** Removed UniqueBorderGates-All-BetterDGEntrance.esp from the list of plugins to ESL-ify (removed from the guide).
- **Nemesis:** Moved this step *before* Facegen. Nemesis mods crash the Creation Kit before they are patched.
- **Nemesis:** Moved creation of the PATCHER OUTPUT separator from Facegen to this page.
- **Nemesis:** Removed mention of Movement Behavior Overhaul and replaced a related screenshot.
- **Facegen:** Removed mention of High Poly Head which didn't get added after all.

#### Conflict Resolution Patch

- Fixed remaining miscellaneous conflicts.
- Actually fixed conflicts with Reasonable Quest Rewards (they got lost in 4.5 somehow)
- Tweaked Armor of Yngol implementation (chest now only contains armor pieces and should only appear during the quest)
- Re-enabled double enchantments because Scrambled Bugs now contains a fix for them

#### Wabbajack Installer

- Regenerated all outputs
- Updated Mod Organizer 2 to 2.4.1
- Updated SSE Creation Kit Fixes to 3.2
- Updated SSE Display Tweaks to 0.4.9-1
- Updated the Skyrim Particle Patch
- Updated Skyrim Landscape and Water Fixes to 6.0
- Updated Storm Lightning to 1.4.9
- Updated Smoking Torches and Candles to 1.76
- Updated Realistic Water Two to 3.1.0
- Updated High Poly Blackreach Mushrooms to 1.1
- Updated Cathedral Armory - TPF Repack to 1.1.3
- Updated Aetherius - A Race Overhaul to 2.4.1
- Updated Mundus - A Standing Stone Overhaul to 1.5.0
- Updated Reliquary of Myth - Artifact Overhaul to 3.8.0
- Updated Radiant Requirements to 1.1.0
- Updated Blade and Blunt - A Combat Overhaul to 1.3.0
- Updated Lightweight Smithing Tweaks to 2.3
- Updated Misc Tweaks - Better Horses to 1.3
- Updated Private Profile Redirector to 0.5.2
- Updated ENBSeries (no version change)
- Updated SSELODGen to Beta 76
- **4.5.1.1:** Replaced Harder Quest Tweaks old files
- **4.5.1.2:** Removed Particle Patch from downloads (it's inlined)
- **4.5.1.2:** Fixed missing NPCsWithFaces archive
- **4.5.1.2:** Regenerated terrain LOD which fixed an issue

## Release 4.5

> 06/04/2021

It is done! TPF 4.5 is the biggest update since 4.0 and I spent altogether too long chewing on it. As a result, the risk of me having missed something (typos, unfinished sentences, any sort of weirdness) is even higher than usual. Therefore I would ask you to consider TPF 4.5 a **beta release** that will probably get some much needed polishing in 4.5.1 and potentially further small updates.

- Thanks to No Grass In Objects and grass cache, we now have extended grass range which allows for better distant blending.
- TPF is now using the new DynDOLOD 3.0 which is still in Alpha but perfectly functional.
- Some mods (Extended UI, QuickLoot) were moved to the new addon, TPF-X.
- Added new enemy types, a better console UI, an overhaul for Shouts, tweaks for bounties and quest rewards, and more.
- **This update is NOT save-safe.** You must start a new game.

**Removed mods:**

- **Prince and the Pauper:** While the FOMOD includes a Gamwich retexture option, most of the included clothing is still painfully low res. There *is* an upscale on the Nexus but frankly it cannot really be described as a visual improvement. I prefer having a smaller collection of children's clothing with consistently high quality textures.
- **JK's Cities Lite:** Has some issues with clipping and flickering that I cannot fix (no permissions) and the author of the lite version has been inactive for a long, long time.
- **Arthmoor's town additions:** Aka Arthmoor's awkwardly-squeezed-in houses. They don't look great and nobody is going to actually notice that some NPCs don't have homes.
- **Cathedral Landscapes:** A great concept that never received the updates and improvements it desperately needed. We switched to other mods that offer better grass and a similar degree of distant blending with custom terrain LOD.

#### Initial Setup

- **INI Files:** Godrays should always be set to "High" now.
- **INI Files:** Removed Grass Fade tweak (covered by No Grass In Objects).
- **INI Files:** Added BethINI - Custom section to disable land fade for better terrain LOD transitions.

#### Mod Installation

- **Instructions:** Removed an old reference to optional mods (that are no longer available).
- **Instructions:** Added note on what crossed out options in FOMOD instructions mean.
- Split up "Balancing" once again into "Balancing & Crafting" and "New Content".
- Removed the "College of Winterhold" step. Mods were distributed among other sections.
- Removed "Worldspace Additions".
- Removed "Cities & Villages".
- Removed JK's Cities - Lite.
- Removed Arthmoor's Dawnstar.
- Removed Arthmoor's Falkreath.
- Removed Arthmoor's Dragon Bridge.
- Removed Arthmoor's Ivarstead.
- Removed Arthmoor's Rorikstead.
- Removed Arthmoor's Kynesgrove.
- Removed Arthmoor's Karthwasten.
- Removed Arthmoor's Darkwater Crossing.
- Removed Arthmoor's Shor's Stone.
- Removed Arthmoor's Soljund's Sinkhole.
- Removed Arthmoor's Whistling Mine.
- Removed Unique Border Gates.
- **Essential Mods:** Added Dear Diary - Better More Informative Console.
- **Essential Mods:** Added console command to disable clutter physics damage to Autorun.
- **Essential Mods:** Updated Additional Instructions and the related screenshot for Autorun.
- **Essential Mods:** Added Project Clarity AIO - Skyrim Textures Redone.
- **Essential Mods:** Added Hooded Skeleton Corpse Fix for WACCF.
- **Essential Mods:** Added No Grass In Objects.
- **Fixes:** Added Scrambled Bugs.
- **Fixes:** Updated download instructions for Wiseman303's Flora Fixes - Revamped.
- **Fixes:** Removed instructions for Arthmoor's Patch Pack for Landscape Fixes For Grass Mods.
- **Fixes:** Added Word Wall Transparency Fix for ENB.
- **Fixes:** Removed Dragon Stalking Fix.
- **Fixes:** Added Fixed Dragon Stalking Fix.
- **Tweaks:** Added True Teacher Durnehviir.
- **Interface:** Removed Extended UI.
- **Interface:** Removed QuickLoot.
- **Interface:** Updated SkyHUD FOMOD instructions.
- **Interface:** Removed SkyHUD additional instructions (moved to separate profile).
- **Interface:** Added SkyHUD - TPF Preset.
- **Interface:** Added SkyHUD - Alternate White Dot Crosshair.
- **Interface:** Added moreHUD - TPF Preset.
- **Interface:** Removed moreHUD - Inventory Edition.
- **Interface:** Removed Immersive Bookreading and Lockpicking.
- **Interface:** Added instructions to change the console font for Roboto Font Replacer.
- **Graphics Baseline:** Added instructions to download the new 3.0 version of DynDOLOD Resources.
- **Graphics Baseline:** Updated the FOMOD instructions for DynDOLOD Resources.
- **Graphics Baseline:** Added Perfect Terrain LOD - Noise Texture.
- **Graphics Baseline:** Added instructions to merge the NobleSkyrimMod SMIM Patch with the main file.
- **Weather:** Removed ETHEREAL CLOUDS (using upscaled vanilla cloud textures from Project Clarity instead).
- **Lighting:** Added Shadows of Sunlight - In Small Exterior World Spaces.
- **LIghting:** Updated FOMOD instructions for Smoking Torches and Candles.
- **Visual FX:** Added Deadly Spell Impacts Transparency Fix for ENB.
- **Visual FX:** Removed Glow Be Gone SKSE Updated (more trouble than it's worth).
- **Visual FX:** Removed Glow Be Gone SKSE Updated GhostFX Workaround.
- **Landscape:** This step received a major overhaul. The mod order was updated.
- **Landscape:** Now using Majestic Mountains - Darkside (blends better with Northside).
- **Landscape:** Updated download and FOMOD instructions for Majestic Mountains.
- **Landscape:** Added instructions to delete the projecteddiffuse.dds from Majestic Mountains.
- **Landscape:** Updated FOMOD instructions for Majestic Mountains - Northside.
- **Landscape:** Removed additional instructions for Majestic Mountains - Northside (file gets overwritten anyway).
- **Landscape:** Added Moss Rocks.
- **Landscape:** Removed Landscapes - Cathedral Concept.
- **Landscape:** Removed Cathedral Landscapes - Recolored Vanilla Swamp Grass Addon.
- **Landscape:** Removed Cathedral Landscapes - Windhelm Bridge Fix.
- **Landscape:** Removed Cathedral Landscapes - Fixed Bridge Meshes.
- **Landscape:** Moved Cathedral - 3D Pine Grass to Trees & Plants.
- **Landscape:** Added MystiriousDawn's HD Skyrim Overhaul.
- **Landscape:** Added Better Dirt Cliffs and Alphas.
- **Landscape:** Added Nordic Coast.
- **Landscape:** Added Skyrim Remastered - Glaciers and Ice.
- **Landscape:** Added instructions to install the Darker Gradient Textures file for Realistic Water Two.
- **Landscape:** Removed Realistic Water Two Patch Hub.
- **Landscape:** Removed Bright Waterfall Fix for ENB.
- **Landscape:** Added Blended Roads.
- **Landscape:** Moved Point The Way here.
- **Landscape:** Moved Lanterns of Skyrim II here.
- **Landscape:** Updated FOMOD instructions for Lanterns of Skyrim II.
- **Landscape:** Moved Immersive Dawnguard Dayspring Pass here.
- **Landscape:** Removed Rorikstead Basalt Cliffs.
- **Landscape:** Removed Rorikstead Basalt Cliffs Patches.
- **Trees & Plants:** Added instructions to merge the Enhanced Vanilla Trees optional file with the main file.
- **Trees & Plants:** Added instructions to delete the billboards from Enhanced Vanilla Trees.
- **Trees & Plants:** Removed Enhanced Landscapes - Solstheim 3D Trees.
- **Trees & Plants:** Added Aspens Ablaze.
- **Trees & Plants:** Added Tree Bark in High Definition.
- **Trees & Plants:** Removed Immersive Fallen Trees.
- **Trees & Plants:** Removed Immersive Fallen Trees Patch.
- **Trees & Plants:** Added Veydosebrom Regions.
- **Trees & Plants:** Updated Cathedral - 3D Pine Grass additional instructions.
- **Trees & Plants:** Added High Poly Soul Husks.
- **Trees & Plants:** Added Soul Husk Retexture.
- **Trees & Plants:** Added Unique Solstheim Grass.
- **Architecture:** Added Whiterun Mesh Fixes.
- **Misc Structures:** Removed Stunning Statues of Skyrim.
- **Misc Structures:** Added Iconic Statues.
- **Misc Structures:** Removed Shrine of Azura HD.
- **Misc Structures:** Removed Winterhold Statue - Animated with ENB Lights.
- **Interiors:** Added SD's Horn Candles.
- **Dungeons:** Removed CC's Enhanced Ore Veins.
- **Dungeons:** Removed CC's Enhanced Ore Veins - Fixed Iron Ore Cubemap.
- **Dungeons:** Removed additional instructions from Metallurgy (now using the full package).
- **Dungeons:** Removed Rally's Jurgen Windcaller Tomb.
- **Dungeons:** Added Iconic's Jurgen Windcalled Tomb and Horn Retexture.
- **Dungeons:** Added Dwemer Pipework Reworked.
- **Dungeons:** Added instructions to download an additional file for Ancient Dwemer Metal - My Patches.
- **Dungeons:** Added WEBS.
- **Clutter:** Added Retexture for The Scroll.
- **Apparel & Weapons:** Removed instructions to install matched color fix for Frankly HD Stormcloaks (redundant).
- **Apparel & Weapons:** Added Ancient Dwemer Metal - My Patches - No Smiling Female Helmet.
- **Creatures:** Added Deiform Alduin.
- **Appearance:** Added Expressive Facegen Morphs.
- **Appearance:** Added Less Bright Teeth for Expressive Facegen Morphs.
- **Appearance:** Removed Immersive Mouth and Teeth.
- **Appearance:** Removed Just Fangs from BVFE.
- **Appearance:** Updated Simple Children - Patches FOMOD instructions.
- **Gameplay Overhauls:** Added Forceful Tongues - Shouts Overhaul.
- **Gameplay Overhauls:** Updated download and FOMOD instructions for Carriage and Ferry Travel Overhaul - Fixes and Winterhold.
- **Non-Player Characters:** Added instructions to unpack the BSA for Hearthfire Multiple Adoptions.
- **Non-Player Characters:** Removed Prince and the Pauper.
- **Non-Player Characters:** Removed Prince and the Pauper - Hearthfire Multiple Adoptions Patch.
- **Non-Player Characters:** Removed DIVERSE SKYRIM.
- **Improved Vanilla Quests:** Added Companions Werewolf Bloodritual Scene Tweak.
- **Improved Vanilla Quests:** Moved Improved College Entry - Questline Tweaks here.
- **Improved Vanilla Quests:** Moved Finding Velehk Sain here.
- **Improved Vanilla Quests:** Added Sable's Bits and Bobs - The Last Dragonborn Perk.
- **Improved Vanilla Quests:** Removed Andrealphus' Gameplay Tweaks (mod page was repurposed).
- **Improved Vanilla Quests:** Added Stones of Barenziah - Alternate Locations.
- **Improved Vanilla Quests:** Added Andrealphus' Tweaks - Harder Quests.
- **Combat & Encounters:** Added Less Sniperlike NPCs.
- **Combat & Encounters:** Added Sable's Bits and Bobs - Steam Driven Automatons.
- **Balancing:** Added Less Cure Disease Potions.
- **Balancing:** Added Bounties Are Worthwhile - Leveled Bounty Rewards.
- **Balancing:** Added Bounty Preview.
- **Balancing:** Added Reasonable Quest Rewards.
- **New Content:** Moved Armor and Clothing Extension here.
- **New Content:** Moved Tweaks for WACCF and ACE here.
- **New Content:** Moved aMidianBorn Armor Variants Lite here.
- **New Content:** Moved Practical Female Armors - AMB AVL Patch here.
- **New Content:** Re-added Armor of Yngol.
- **New Content:** Added Civil War Deserters.
- **New Content:** Added Forsworn Gravesingers.
- **New Content:** Added Forsworn Skinchangers.
- **New Content:** Moved Obscure's College of Winterhold here.
- **New Content:** Moved Choose Your Own Arch-Mage here.
- **New Content:** Moved Immersive College NPCs here.
- **New Content:** Moved Misc College of Winterhold Tweaks here.
- **New Content:** Moved Solstheim Lighthouse here.
- **New Content:** Moved Solstheim - Skaal Fishing Camp here.
- **Miscellaneous:** Moved Miscellaneous Tweaks Collection here (yes, I keep moving it, I'm sorry).
- **Miscellaneous:** Added instructions to download the new Misc Tweaks - More Expensive Inns.
- **Miscellaneous:** Added Horse Stamina HUD.
- **Miscellaneous:** Added Dragon Wall Wisdom - Readable Dragon Walls.
- **Miscellaneous:** Added Unique Dragon Aspect.
- **Miscellaneous:** Added Smelters for Riften and Solitude.
- **Miscellaneous:** Added Contraband Confiscated.
- **Assorted Plugins:** Removed Enhanced Death Cam (caused some unforseen issues).
- **Assorted Plugins:** Removed No Lockpick Activate (was only "required" for QuickLoot).
- **Skeleton & Animations:** Added Dynamic Animation Replacer.
- **Skeleton & Animations:** Added Jump Behavior Overhaul.
- **Skeleton & Animations:** Added Super Fast Get Up Animation.
- **Skeleton & Animations:** Added Faster Reanimation (undocumented 4.something addition).

#### Finalisation

- **Wrapping Up:** Added NoMoreFollowerHuntingBow.esp to the list of plugins to ESL-ify.
- **Facegen:** Updated list of plugins required for the NPCsWithFaces plugin as well as the CK screenshot.
- **SSELODGen:** Added this new page since we now generate terrain LOD with xLODGen.
- **SSELODGen:** Moved SSELODGen installation instructions here from the Occlusion page.
- **Grass Cache:** Added this page with instructions on how to generate grass cache.
- **DynDOLOD:** Updated all instructions for DynDOLOD 3.0.
- **Occlusion:** Updated the Occlusion page (it's very short now).
- **ENBSeries:** Added instructions to disable distant reflections in Serio's ENB.

#### Wabbajack

- Updated the instructions for launching Skyrim (renamed SKSE >> The Phoenix Flavour).

#### Mod Configuration

- **moreHUD:** Updated MCM instructions for the new preset.
- **Realistic Water Two:** Removed MCM instructions (no longer necessary).

#### Performance Guide

- This is a new page with instructions on how to soften the performance impact of base TPF.

#### Gameplay Guide

- Split up into multiple pages.
- Updated some sections (still requires a proper expansion).

#### TPF Addons

- There is now only a single, top-level **TPF Addons** page with all relevant information.
- Removed MO2 profile and Sync Mod Order plugin instructions (now part of the TPF-X instructions).
- Added information on the new TPF-X Addon in the Available Addons section.
- **Updating Addons:** Removed as I feel like it's too vague and general, better if addon creators provide specific instructions.
- **Available Addons:** Content from this page is now on the Addon Primer page.

#### Conflict Resolution Patch

- Removed Relighting Skyrim as a master (wasn't necessary)
- Removed Majestic Mountains - Moss Rocks as a master
- Removed JKs Skyrim Lite as a master
- Removed Arthmoor's Falkreath as a master
- Removed Arthmoor's Dragon Bridge as a master
- Removed Arthmoor's Ivarstead as a master
- Removed Arthmoor's Kynesgrove as a master
- Removed Arthmoor's Darkwater Crossing as a master
- Removed Unique Border Gates as a master
- Removed Genuinely Intelligent Soul Gems as a master
- Opening certain books will once again start the connected quest instantly instead of giving you a message box
- Disabled a Woodcutter's Axe placed in Riften by the USSEP clipping with the smelter added by Smelters in Riften and Solitude
- Resolved conflicts between Reasonable Quest Rewards and other mods
- Resolved conflicts between Less (sic) Cure Disease Potions and other mods
- Fixed campfire texture sets (thanks Dusky!)

## Release 4.4.3

> 10/03/2021

This update was originally intended to be a bit longer but there you go. Most importantly, TPF now supports MO2 2.4.0, the latest update.

**This update is save-safe.**

#### Update Instructions

For manual guide users only.

- Follow [these instructions](/tpf/guide-resources/how-to-update/#mod-organizer-2) to update your Mod Organizer 2 instance to 2.4.0 without losing your setup.
- Regenerate the **NPCsWithFaces.esp** with the three added plugins and rebuild facegen.
- Rename the **FINAL PATCH** separator to **FINAL PATCHES**. Makes more sense when you also have Addon patches.

#### Initial Setup

- **Mod Organizer 2:** Updated download and installation instructions for MO2 2.4.0.
- **Mod Organizer 2:** Added the BSA Unpacker section.
- **Mod Organizer 2:** Removed Manage Mod Downloads section (part of the installer now).
- **Skyrim Script Extender:** Fixed link to the SKSE INI to also lead directly to the file section.

#### Mod Installation

- **Instructions:** Improved general layout of the page for better readability.
- **Instructions:** Added small note about collapsible separators.
- **Essential Mods:** Added instructions to enable Regular Quicksaves in SSE Engine Fixes.
- **Essential Mods:** Added cl off to the commands for Autorun.
- **Weather:** Updated Wonders of Weather - Less Opaque Rain Splashes for ENB FOMOD instructions (95% >> 80%).
- **Trees & Plants:** Added Canticle Tree and Bark (undocumented 4.4.2 addition).
- **Dungeons:** Removed instructions to merge update with main file for Ancient Dwemer Metal - My Patches.
- **Dungeons:** Removed part of the additional instructions for Ancient Dwemer Metal - My Patches (no longer necessary).
- **Gameplay Overhauls:** Updated FOMOD instructions for Reliquary of Myth (now using the SPID Patches).

#### Finalisation

- **Wrapping Up:** Renamed the FINAL PATCH separator to FINAL PATCHES.
- **Facegen:** Slightly reworded some instructions.
- **Facegen:** Added a warning about required space on your hard drive for the facegen instructions.
- **Facegen:** Added three missing plugins with new NPCs to the NPCsWithFaces instructions.
- **Facegen:** Updated CK screenshot to reflect the above change.

#### Mod Configuration

- Updated the A Matter of Time instructions to account for the script tweak disabling the clock by default.
- Removed Storm Lightning instructions (Ultra Realistic preset is now selected by default).

#### Resources

- **How to Update:** Slightly improved the updating instructions for Mod Organizer 2.

#### Conflict Resolution Patch

- Disabled the "Bless Home" spell from Hearthfire Multiple Adoptions (thanks Delta!)

#### Wabbajack Installer

- Updated the links to the website / readme in the installer
- Updated Improved Sparks - Vanilla Grindstone to 3.0.1
- Updated Cathedral Armory - TPF Repack to 1.1.2
- Updated Cathedral Armory - Armor Mesh Fixes Patch to 1.02
- Updated Reliquary of Myth to 3.7.3
- Regenerated facegen

## Global Site Update

> 08/03/2021

I finally did some spring cleaning. For the longest time it annoyed me that in my original folder structure I had categorised pages by games, for example the TPF part of the website was called "Skyrim SE" in the top menu. But what if I want to start another SE project? And you don't want to know the chaos in my pictures folder either.

The reason I hesitated for so long to change the folder names is because it breaks every, single, link. And while fixing the internal links and file paths was merely a minor annoyance, fixing all external links is more difficult - especially considering that other people may link to TPF as well and those links are now broken. Of course I also need to recompile both TPF and WTP for Wabbajack to update the links that open automatically upon installing a Wabbajack list.

Well, I finally updated now and I'm very happy with the changes. It likely will take some time for all external links to get fix plus I suspect I may have missing some internal links and file paths.

#### Changes

- Removed the Bioware section (see below).
- Renamed "Skyrim SE" to "The Phoenix Flavour" (link changed from skyrim-se to tpf).
- Renamed "Fallout 4" to "Welcome to Paradise" (link changed from fallout to wtp).
- Updated all internal links and file paths - hopefully.
- Cleaned up my pictures folder to remove any pictures that are no longer in the guide.
- Updated the home page, it has two buttons now and a combination of the TPF and WTP pics.

#### Bioware

The current state of things is that I have published a guide for ME1 with a draft for an ME2 version waiting for revision. But here's the thing: Modding Bioware games is quite different from modding Bethesda games. I've only really dipped my toes in it and wouldn't call myself an expert by any stretch of the imagination. Something I often criticise about various smaller Skyrim modding "guides" is that their authors barely know what they're doing. It occured to me that my Mass Effect "guides" are in essence the same thing ~~with better formatting~~.

To keep a longer story short, I have developed a strong sense of imposter syndrome over those excursions into Bioware land that is causing me a fair amount of stress. Something I've learned over the past couple years is that if you have too many things putting pressure on you at once, cut out everything that's non-essential. Well, this time the scissors are for the Bioware section of the TPF website.

## Release 4.4.2

> 07/03/2021

This update contains some more 4.4 fixes but also a bigger update for the **Cathedral Armory - TPF Repack**. Specifically, I added Armor Mesh Fixes and added meshes from the existing Cath Armory patch to my repack.

I also added **Practical Female Armor** meshes patched for Cath Armory by **Asator**. Several armors will no longer have boobplates: Nordic Carved, Elven, Steel Plate, and Wolf. These are in my opinion the worst offenders and the ones that actually annoy me. I may add PFA meshes for Ebony armor in the future.

#### Updating instructions

- Double-click **SSE Engine Fixes** and set `SleepWaitTime=` to `false` again. This is so there is enough time for the new NPC AI Process Position Fix to do its job.
- Regenerate **AllGUD**.

#### Mod Installation

- **SSE Engine Fixes:** Removed INI tweak for SSE Engine Fixes.
- **Fixes:** Added NPC AI Process Position Fix.
- **Graphics Baseline:** Removed pointless instructions to delete walkwaycwall01.nif from SMIM.
- **Weather:** Added (experimental) FOMOD instructions for Storm Lightning.
- **Visual FX:** Added Improved Sparks.
- **Architecture:** Added instructions to remove a texture from Skyland - Solitude.
- **Architecture:** Added Better Volkihar Secret Entrance (undocumented 4.4 addition).
- **Architecture:** Added Upgraded Moondial (undocumented 4.4 addition).
- **Dungeons:** Added Ancient Dwemer Metal - My Patches for SMIM Dawnguard Dragonborn (undocumented 4.4 addition).
- **Clutter:** This page was split in two. The bottom half of mods was moved to the new VALUABLE ITEMS page.
- **Clutter:** Added Rally's Farming Tools.
- **Clutter:** Added Rally's Hooks and Saws.
- **Clutter:** Added Rally's Fishing Poles.
- **Clutter:** Fixed a typo in the additional instructions for Realistic HD Blacksmith Remastered.
- **Valuable Items:** Moved Septim HD here.
- **Valuable Items:** Moved all mods that were below Business Ledger HD Retexture in CLUTTER here.
- **Valuable Items:** Added Draw Knife Retexture.
- **Apparel & Weapons:** Added Armor Mesh Fixes.
- **Apparel & Weapons:** Added instructions to download the Armor Mesh Fixes patch from the Cathedral Armory mod page.
- **Apparel & Weapons:** Removed instructions to download the hotfix from LeanWolf's Better-Shaped Weapons (will be overwritten anyway).
- **Apparel & Weapons:** Added Actual Orichalcum Orcish Equipment (undocumented 4.4 addition).
- **Apperal & Weapons:** Added JS Circlets - USSEP Patch.
- **Non-Player Characters:** Added Hunters Dialogue Edit.
- **Combat & Encounters:** Realistic Melee Range was moved above Blade & Blunt in the load order.
- **Balancing:** Re-added Practical Female Armors.
- **Assorted Plugins:** Added Classic Paralysis.
- **Assorted Plugins:** Added Enhanced Reanimation.
- **Assorted Plugins:** Added Enhanced Death Cam.
- **Assorted Plugins:** Added Essential Favorites.

#### Finalisation

- **Wrapping Up:** Removed Realistic AI Detection 2 SE Lite.esp from the list of plugins to ESL-ify.

#### Conflict Resolution Patch

- Now comes packaged with a script from AMOT that will automatically hide the clock widget until you choose to enable it
- AMOT script by SkyAmigo, edited by Sr. Kaio. Thanks to both!

#### Wabbajack Installer

- Updated Equip Enchanting Fix to 1.2.3
- Updated Storm Lightning to 1.4.8
- Updated Cathedral Armory - TPF Repack to 1.1.1
- NPCs With Faces is no longer included (people got confused)

## Release 4.4.1

> 04/02/2021

Fixed a bunch of embarrassing typos, both in the guide and in the 4.4 changelog.

#### Mod Installation

- **Fixes:** Added No Grass In Caves (undocumented 4.4 addition).
- **Graphics Baseline:** Fixed part of High Poly Project FOMOD instructions being illegible.
- **Clutter:** Added Deer Skull and Antlers (undocumenteed 4.4 addition).
- **Apparel & Weapons:** Actually removed Sunhallowed and Bloodcursed Weapons - HD Retexture from the page.

#### Finalisation

- **ENBSeries:** Incorporated a suggested improvement to the Global INI Settings instructions.

## Release 4.4

> 04/03/2021

**Removal of High Poly Vanilla Hair:** This mod was TEMPORARILY removed as the current version has clipping issues on vanilla heads. The author only tested with High Poly Head but unfortunately did not set that as a requirement. They are apparently working on a fix and the mod will be re-added when that fix is available.

**Removal of Forgotten Retex Project:** While this is a great compilation of various mods, I prefer to hand-pick at the end of the day. As more conflicting mods were added, the list of files to delete from this mod grew further and I decided to simply remove it. Similar to HMB II (Cathedral NPCs) many of the mod previously included in the big package were now re-added separately.

**Removal of Skyrim 3D Misc - Tanning Rack:** Ok, so hear me out. Mathy does great work. Incredible meshes. They are so good, in fact, that every time I come across a tanning rack, I can't help thinking "that's a 2021 mesh in my 2011 game". Yes, I removed a mod because it's too well made.

**Removal of Practical Female Armor Changes:** This one will upset people, and trust me, the return of the boobplate doesn't make me happy either. But with the PFA meshes and Cath Armory meshes, and lacking the skills to implement the changes from either mod into the other, I had to make a decision. Will probably be re-added at some point when I've figured out how to patch the meshes.

#### Updating Instructions

- Completely redo the [Facegen](/tpf/finalisation/facegen) step, including updating the script, regenerating the plugin, rebuilding facegen, and running the output through CAO.
- Also regenerate AllGUD, TexGen, DynDOLOD, and Occlusion. Remember to use the [How To Update - DynDOLOD](/tpf/guide-resources/how-to-update/#dyndolod) if you're on an ongoing playthrough.

#### Mod Installation

- **Essential Mods:** Updated INI Tweak instructions for SSE Display Tweaks.
- **Graphics Baseline:** Added instructions to remove two meshes from Ruins Clutter Improved.
- **Graphics Baseline:** Added HD Falmer and Chaurus.
- **Graphics Baseline:** Updated FOMOD instructions for High Poly Project.
- **Landscape:** Removed Pfuscher's Rapid Rocks (mesh is stupidly high poly and also doesn't blend well).
- **Landscape:** Added Majestic Mountains - Rapid Rocks Mesh.
- **Landscape:** Updated FOMOD Instructions for Majestic Mountains - Northside.
- **Trees & Plants:** Fixed file paths in additional instructions for HD Dead Trees and Driftwoods.
- **Trees & Plants:** Added HD Dead Trees and Driftwoods 2K Mesh Fix.
- **Architecture:** Removed The Streets of Whiterun HD.
- **Architecture:** Added Skyland Whiterun.
- **Architecture:** Added Skyland Whiterun - SMIM Wood Color Patch.
- **Architecture:** Moved RUSTIC MONUMENTS AND TOMBSTONES to Misc Structures.
- **Architecture:** Moved Skyrim 3D High Hrothgar Steps to Misc Structures.
- **Architecture:** Moved Pilgrim's Delight - High Hrothgar Shrine Retextures to Misc Structures.
- **Architecture:** Removed HD Reworked Falmer Architecture (covered by HD Falmer and Chaurus).
- **Architecture:** Added Iconic's Moon Crest Retexture.
- **Misc Structures:** Removed instructions to download an optional file for SD's Farmhouse Fences (was redundant).
- **Misc Structures:** Added Rudy HQ - Hay.
- **Misc Structures:** Added Iconic's Morthal Quest Coffin Retexture.
- **Dungeons:** Added Rally's Jurgen Windcaller Tomb.
- **Clutter:** Removed Forgotten Retex Project.
- **Clutter:** Added Septim HD.
- **Clutter:** Added Qwafee Keys.
- **Clutter:** Removed Aetherial Crown by Saerileth - Plugin Replacer.
- **Clutter:** Updated Skyrim 3D Misc download instructions (no longer downloading Tanning Rack file).
- **Clutter:** Added Realistic HD Pickaxe Remastered.
- **Clutter:** Added Realistic HD Woodcutter's Axe Remastered.
- **Clutter:** Added Realistic HD Blacksmith Remastered.
- **Clutter:** Added Dressed Hearthfire Doll.
- **Clutter:** Added HD Ruined Book Retexture.
- **Clutter:** Added Burned Book Retexture.
- **Clutter:** Added instructions to compress JS Dragon Claws textures to save VRAM.
- **Clutter:** Added White Phial Replacer.
- **Clutter:** Added Iconic's Weathered Dragonstone Retexture.
- **Clutter:** Added Barenziah's Glory.
- **Clutter:** Moved Barenziah's Glowing further down in the mod order.
- **Clutter:** Added Iconic's Falmer Eye Gem Retexture.
- **Clutter:** Added Bust of the Gray Fox.
- **Clutter:** Added Iconic's Remastered Paragon Gems Retexture.
- **Clutter:** Added Particle Lights for ENB - Paragon Gems.
- **Food & Ingredients:** Added Ingredients (mod by Pfuscher).
- **Food & Ingredients:** Added Particle Lights for ENB - Ingredients.
- **Apparel & Weapons:** Removed Practical Female Armors until I figure out how to patch the meshes.
- **Apparel & Weapons:** Removed Male Horns for Female Iron Helm.
- **Apparel & Weapons:** Removed Frankly HD Silver Sword.
- **Apparel & Weapons:** Updated FOMOD instructions for LeanWolf's Better-Shaped Weapons.
- **Apparel & Weapons:** Added Cathedral Armory - TPF Repack.
- **Apparel & Weapons:** Added Project Clarity - Weapons - TPF Repack.
- **Apparel & Weapons:** Removed Iron Things - Bow.
- **Apparel & Weapons:** Removed Elven Weapons for Silence.
- **Apparel & Weapons:** Removed CC's HD Dwemer Weapons and Armor.
- **Apparel & Weapons:** Added Ancient aMidianBorn Dwarven Armory.
- **Apparel & Weapons:** Removed Falmer Weapons for aMidianBorn Book of Silence (covered by HD Falmer and Chaurus).
- **Apparel & Weapons:** Removed Ebony Weapons 2017 Retexture.
- **Apparel & Weapons:** Added HD Reflective Ebony Armor and Weapons.
- **Apparel & Weapons:** Removed HD Reworked Shellbug (covered by HD Falmer and Chaurus).
- **Apparel & Weapons:** Removed Sunhallowed and Bloodcursed Arrows - HD Retexture.
- **Apparel & Weapons:** Added instructions to merge the optional fiels from Outlandish Stalhrim with the main file.
- **Unique Artifacts:** Added HD Reflective Ebony Mail.
- **Unique Artifacts:** Removed Bloodskal Blade Redone.
- **Unique Artifacts:** Added Remiros' Bloodskal Blade HD.
- **Unique Artifacts:** Removed Auriel's Bow - HD Retexture.
- **Unique Artifacts:** Removed Auriel's Shield - HD Retexture.
- **Unique Artifacts:** Removed Ghosu - Auriel's Quiver Replacer.
- **Unique Artifacts:** Removed Ghosu's Auriel's Quiver Retexture.
- **Unique Artifacts:** Added 2K Black Bow of Fate Retexture.
- **Unique Artifacts:** Changed mod order for Frankly HD Miraak.
- **Unique Artifacts:** Added Aevrigheim - Miraak's Sword and Staff Replacer.
- **Creatures:** Removed Unique Barbas xEdit instructions (now covered in the CRP).
- **Appearance:** Updated link for Cathedral Player and NPC Overhaul - Female Skin Textures.
- **Appearance:** Removed Mild Hair Colors.
- **Appearance:** Added Natural Hair Colors.
- **Appearance:** Removed High Poly Vanilla Hair.
- **Appearance:** Updated link for Xenius Character Enhancement - Dirt Masks.
- **Improved Vanilla Quests:** Added instructions to resave Finding_Derkeethus.esp in the Creation Kit.
- **Combat & Encounters:** Changed download instructions for Realistic AI Detection. Sneaking is harder now.
- **Balancing:** Removed Armor and Clothing Extension (WACCF) - MCM Menu Fix (original mod was updated).

#### Finalisation

- **Facegen:** Fixed a typo.
- **Facegen:** Added instructions to download the zEdit script from the Nexus.
- **Facegen:** Updated list of plugins to load in zEdit.
- **Facegen:** Adjusted instructions zEdit instructions (since the script can just be downloaded now).
- **Facegen:** Updated the screenshot for loading the plugin in the CK (changed load order confused people).

#### Wabbajack

- Added instructions on how to uncap the framerate for people with G-Sync or FreeSync monitors.

#### Resources

- **How To Update:** Added instructions to also delete and regenerate the Occlusion output in the DynDOLOD section.

#### Conflict Resolution Patch

- Reverted size change to Unique Barbas as it can cause him to get stuck.
- Removed Aetherial Crown - Plugin Replacer as a master
- Fixed conflicts between No Grass In Caves, Relighting Skyrim, and Realistic Water Two

#### Wabbajack Installer

- ENB Man is no longer packaged with the Wabbajack installer
- Updated SSE Display Tweaks to 0.4.8-1
- Updated the CAO - Basic Profiles Pack to 1.4
- Updated Mysticism - A Magic Overhaul to 1.1.6
- Updated Adamant - A Perk Overhaul to 4.2.8
- Updated Misc Tweaks - Better Horses to 1.2
- Updated Armor and Clothing Extension to 1.2
- Updated aMidianborn Armor Variants Lite to 1.3
- Updated Tweaks for WACCF and ACE to 1.5
- Updated DynDOLOD to 2.94
- Reinstalled Skyrim 3D Misc - Winterhold Gate to hopefully fix it getting unchecked
- Regenerated facegen with the new version of the NPCsWithFaces script

## Release 4.3.2

> 25/02/2021

The update is **save-safe**. Upon loading a save, you will be warned about a "missing plugin" because the CRP was renamed. Since the plugin is still present (only under a different name) and had no direct masters, this is harmless and you can simply click OK.

#### Initial Setup

- **Mod Organizer 2:** Added instructions to download the old 2.3.2 version of Mod Organizer 2.

*Support for MO2 2.4.0 will come eventually but we will wait until most Antivirus tools have flagged the new version as harmless in their databases. They are known to quarantine parts or the entirety of MO2, usually because of the UVFS.*

#### Mod Installation

- **Visual FX:** Removed Voltage.
- **Visual FX:** Removed Voltage - KZG Chroma Pack.
- **Visual FX:** Added Thunderbolt - HD Lightning.
- **Assorted Plugins:** Added Vampires Cast No Shadows.

#### TPF Addons

- **Available Addons:** Added a big (and I mean big) reminder to read the Addon Primer first.

#### Conflict Resolution Patch

- The plugin was renamed to **The Phoenix Flavour - Conflict Resolution Patch.esp** for consistency with other Addon patches.
- Marked dummy item for a bug fix in Enchanting Adjustments as Non-Playable (thanks to Slidikins!)

#### Wabbajack Installer

- Actually removed QuickLight
- Updated Serana's Hood Fix to 3.0.1
- Updated Revamped Assets Skyrim - Weapon Racks Patch to 1.1
- Updated Horses for Followers to 1.3
- Updated Alchemy Adjustments - TPF Tweaks to 1.2
- Updated DynDOLOD to 2.93
- Updated xLODGen to v73

*LOD and Occlusion were not regenerated.*

## Release 4.3.1

> 24/02/2021

No changes to the manual guide or Wabbajack (although an actual content update is coming soon).

I added a new section called [**TPF Addons**](/tpf/tpf-addons/) to officially feature the various Addons created by third parties. These range from integration patches (Legacy of the Dragonborn and Creation Club content) to small collections to be installed on top of an existing TPF setup. Sr Kaio's and D1Z4STR's Addons are for the small touches while Slidikins' Strenuous Skyrim is made to increase the overall difficulty. Different Addons cater to different tastes!

**If you are interested in Addons:** Please, please read the [Addon Primer](/tpf/tpf-addons/addon-primer) I wrote before installing anything. The page will take you through the rest of the section and supply you with everything you need to know.

I am also working on an Addon of my own with some changes that I cannot put into the main guide. Stay tuned for updates!

## Release 4.3

> 21/02/2021

This update is **save-safe** but manual guide users must regenerate some of their outputs.

- Facegen (delete output, re-active NPCsWithFace.esp, export facegen)
- TexGen + DynDOLOD ([instructions](/tpf/guide-resources/how-to-update/#dyndolod))
- Occlusion

**Wabbajack users:** You also need to follow [these instructions](/tpf/guide-resources/how-to-update/#dyndolod) to update DynDOLOD on an ongoing save.

#### Mod Installation

- **Essential Mods:** Moved Static Mesh Improvement Mod to Graphics Baseline.
- **Fixes:** Removed instructions to install the WM's Flora Fixes SMIM Patch (moved to Graphics Baseline.)
- **Fixes:** Linked Rude Imperial Soldiers Escort Fix to a pre-ported and -ESL-ified alternative.
- **Fixes:** Removed now-obsolete porting instructions from Rude Imperial Soldiers Escort Fix.
- **Fixes:** Added Equip Enchantment Fix.
- **Tweaks:** Added Fixed Body Collision.
- **Graphics Baseline:** Added Better DynDOLOD Red Mountain Plume.
- **Graphics Baseline:** Moved Static Mesh Improvement Mod here.
- **Graphics Baseline:** Added Static Mesh Improvement Mod - Quality Addon.
- **Graphics Baseline:** Added SMIM Whiterun Bench.
- **Graphics Baseline:** Moved Riekling Barrels SMIM here.
- **Graphics Baseline:** Moved WM's Flora Fixes SMIM Patch here.
- **Lighting:** Added the High Poly Smelter - Embers HD Patch.
- **Visual FX:** Added instructions to remove a decal texture from Voltage.
- **Visual FX:** Added Voltage - ZTG Chroma Pack.
- **Visual FX:** Added Ljoss ENB - Magelight Fix.
- **Visual FX:** Added Glow Be Gone SKSE Updated.
- **Visual FX:** Added Glow Be Gone SKSE GhostFX Workaround.
- **Landscape:** Added Cathedral Landscapes - Fixed Bridge Meshes.
- **Landscape:** Removed Blended Roads.
- **Trees & Plants:** Added HD Dead Trees and Driftwoods.
- **Trees & Plants:** Removed Enhanced Landscapes - Oaks Standalone (another one for the not v+ enough axe).
- **Trees & Plants:** Added 3D Junipers - Trees and Berries.
- **Architecture:** Added Solitude Mesh Fixes.
- **Architecture:** Added Skyland - Solitude.
- **Architecture:** Removed HQ Solitude.
- **Architecture:** Added Markarth - A Reflective Experience.
- **Architecture:** Added Markarth - A Mountainous Experience.
- **Misc Structures:** Added Boats and Ships.
- **Misc Structures:** Moved Riekling Barrels SMIM to Graphics Baseline.
- **Misc Structures:** Updated Stunning Statues of Skyrim FOMOD instructions (no longer selecting Winterhold and Azura statues).
- **Misc Structures:** Added Shrine of Azura HD.
- **Misc Structures:** Added Winterhold Statue - Animated with ENB Lights.
- **Misc Structures:** Added Rally's Solstheim Shrines.
- **Interiors:** Added Centered Blue Palace Thrown.
- **Dungeons:** Removed instructions to delete two textures from Underground.
- **Dungeons:** Fixed typo in Helgen Mud Fix instructions for Underground.
- **Dungeons:** Added instructions to remove dragonbridge01.nif from Rudy HQ (Blended Roads compatibility).
- **Dungeons:** Removed 4K Nordic Murals.
- **Dungeons:** Added CC's Remsatered Murals.
- **Clutter:** Updated download instructions for Meridia's Luxon Beacon Replacer.
- **Clutter:** Added Particle Lights for ENB - Bugs In A Jar.
- **Food & Ingredients:** Added Unique Stros M'Kai Rum (crashing issue kindly resolved itself).
- **Food & Ingredients:** Added Skeever Tail HD.
- **Unique Artifacts:** Removed Better Shrouded Armor - Ancient Replacer Only (not v+ enough).
- **Appearance:** Added Xenius Character Enhancement - Dirt Masks.
- **Non-Player Characters:** Updated instructions for Tavern AI Fix (Autorun Console Commands > Autorun).
- **Non-Player Characters:** Updated instructions for Guard Dialogue Overhaul (Autorun Console Commands > Autorun).
- **Improved Vanilla Quests:** Fixed file name in download instructions for the Timing Is Everything Preset.
- **Miscellaneous:** Removed QuickLight.

#### Finalisation

- **Wrapping Up:** Removed ImperialSoldiersEscortFix.esp from list of plugins to ESL-ify.
- **Wrapping Up:** Added Fixed body collision.esp to the list of plugins to ESL-ify.
- **Facegen:** Fixed a typo.
- **Facegen:** Moved instructions for the PATCHER OUTPUT separator here.
- **Facegen:** Added workaround in the case of constant crashes while attempting to export facegen in the Creation Kit.
- **Nemesis:** Moved instructions for the PATCHER OUTPUT separator to the Facegen step.

#### Resources

- **How To Update:** Added support for Wabbajack users to the DynDOLOD section.
- **How To Update:** Fixed links and typos in the DynDOLOD section.

#### Conflict Resolution Patch

- Packaged the aMidianBorn hide armor textures to overwrite the vanilla copy in Warmth (thanks butthead!)
- Disabled the loading screen added by Lanterns of Skyrim II
- Removed Better Shrouded Armor - Ancient Replacer as a master
- Fixed a conflict between Alchemy Adjustments and Unique Stros M'Kai Rum
- Increased level requirements for More Werewolves open world encounters from 10 to 16
- Removed Enhanced Landscapes - Oaks Standalone as a master

#### Wabbajack Installer

- Updated Simple Offence Suppression to 2.0
- Updated Guard Dialogue Overhaul to 2.16
- Regenerated facegen
- Regenerated LOD and Occlusion

## Release 4.2.1

> 18/02/2021

#### Mod Installation

- **Appearance:** Fixed a copy-paste error.
- **Appearance:** Added Forsworn and Blackblood and Boethiah Tattoo (undocumented 4.2 addition).
- **Appearance:** Added Northborn Scars (undocumented 4.2 addition).
- **Appearance:** Added Better Beast Race Scars (undocumented 4.2 addition).

## Release 4.2

> 17/02/2021

This update is bringing DIY facegen instructions and an overhaul for the Appearance section. Please check this [Patreon post](https://www.patreon.com/posts/47666672) for detailed information!

**This update is save-safe.** However, if you were using certain headparts (eyes primarily) added by the now removed Cathedral Player and NPC Overhaul, you may want to go back into the character creation (type `showracemenu` in the console and hit Enter) and update your character. Do NOT change your race!

#### Initial Setup

- **Additional Tools:** Added note that the trailing backslash at the end of the xEdit cache file path is required.
- **Additional Tools:** Added instructions for an argument to define a backup file path.
- **Additional Tools:** Added screenshot to make sure folks get the arguments right.
- **Additional Tools:** Added the -B argument to the QuickAutoClean version as well and updated the screenshot.
- **Additional Tools:** Re-added zEdit with installation instructions.
- **Additional Tools:** Updated Cathedral Assets Optimizer Profiles screenshot (profile pack was updated).
- **ESM Cleaning:** Removed instructions to disable backups in xEdit (they are now simply moved to a separate folder).

#### Mod Installation

- **Fixes:** Re-added Skyrim Ultimate Eye Meshes Ruhmastered.
- **Interface:** Fixed link for Extended UI for Skyrim Uncapper.
- **Graphics Baseline:** Added Revamped Assets Skyrim - Weapon Racks Patch.
- **Appearance:** Removed Cathedral Player and NPC Overhaul.
- **Appearance:** Removed Expressive Facegen Morphs.
- **Appearance:** Moved DIVERSE SKYRIM to Non-Player Characters.
- **Appearance:** Removed the DIVERSE SKYRIM - Cathedral NPCs Facegen Patch.
- **Appearance:** Added Expressive Facial Animations - Female Edition.
- **Appearance:** Added Expressive Facial Animations - Male Edition.
- **Appearance:** Added Vanilla Body with UNP Textures.
- **Appearance:** Added Cathedral Player and NPC Overhaul - Female Skin Textures.
- **Appearance:** Added SkySight Skins.
- **Appearance:** Added Males of Skyrim - High Poly Hands.
- **Appearance:** Added Mild Complexions.
- **Appearance:** Added Masculine Khajiit Textures.
- **Appearance:** Added Feminine Khajiit Textures.
- **Appearance:** Updated FOMOD instructions for Forgotten Argonian Roots (using UNP females option).
- **Appearance:** Added Mild Hair Colors.
- **Appearance:** Added High Poly Vanilla Hair.
- **Appearance:** Added Vanilla Hair - Salt and Wind.
- **Appearance:** Added Argonians Enhanced - HD Argonian Hair.
- **Appearance:** Removed note referring to Cathedral NPCs from Brows.
- **Appearance:** Removed note referring to Cathedral NPCs from Beards.
- **Appearance:** Added Beard Stubble.
- **Appearance:** Added Authentic Eyes.
- **Appearance:** Added Immersive Mouth and Teeth.
- **Appearance:** Added Immersive Mouth and Teeth for Orcs.
- **Appearance:** Added Beastly Smiles.
- **Appearance:** Added Just Fangs from BVFE.
- **Appearance:** Added Painterly - A High Res Warpaint Retexture.
- **Gameplay Overhauls:** Added instructions to remove facegen files from Carriage and Ferry Travel Overhaul.
- **Gameplay Overhauls:** Removed Carriage and Travel Overhaul - Cathedral NPCs Facegen Patch.
- **Non-Player Characters:** Moved DIVERSE SKYRIM here.
- **Non-Player Characters:** Removed Immersive Patrols - Cathedral NPC Facegen Patch.
- **Improved Vanilla Quests:** Fixed mod name for the TIE - TPF preset.
- **College of Winterhold:** Removed note about Cathedral NPCs from the OCW FOMOD instructions.
- **College of Winterhold:** Removed Obscure's College of Winterhold - Cathedral NPCs Facegen Patch.
- **College of Winterhold:** Added instructions to delete facegen files from Immersive College NPCs.
- **College of Winterhold:** Removed Immmersive College NPCs - Cathedral NPCs Facegen Patch.

#### Finalisation

- **Facegen:** Added new page with comprehensive instructions to generate facegen for TPF.

#### Conflict Resolution Patch

- Removed Cathedral NPCs as a master.
- Fixed Hanging Elves Ear mesh to prevent all Elves Ears in a cell from displaying the harvested model after harvesting one.
- Edited buygoldenclawscript.pex to remove leveled price. It will always cost 5000 Septims.
- Edited QF_FreeformRiften05_00053309.pex to properly revert the amounts of pamphlets required to be handed out to vanilla.

#### Wabbajack Installer

- Updated Landscape Fixes for Grass Mods to 4.8

## Release 4.1.2

> 14/02/2021

**Wabbajack installer update.** No changes to the manual guide. The update is *save-safe* and can be applied to an ongoing playthrough.

#### Wabbajack Installer

- Updated Skyrim Uncapper - Adamant Arena to 2.10
- Updated Blade and Blunt to 1.2.1
- Update aMidianBorn Armor Variants Lite to 1.2
- Updated Horses for Followers to 1.1
- Updated ENBSeries (no version number change)
- Updated DynDOLOD to 2.92

*Note that while I updated DynDOLOD itself, I haven't re-generated LOD so there will be no problem with updating ongoing playthroughs.*

## Release 4.1.1

> 13/02/2021

#### Mod Installation

- **Food & Ingredients:** Actually removed Unique Stros M'Kai Rum from the mod installation section.

## Release 4.1

> 10/02/2021

As it turns out, the Timing Is Everything preset feature is broken. I hadn't previously noticed it as I didn't check *all* the pages and on the "Extras" page everything seemed to work well. Umgak fixed that in scripts packaged with the CRP. The preset itself was updated for even better synergy with other mods in TPF, ensuring quests will not be available before you are capable of beating them. Details can be found on the new [Quests](/tpf/gameplay-guide/quests) page in the Gameplay Guide.

While working on the Quests segment of the Gameplay Guide, I noticed that it was rather inconsistent to use Andrealphus' Dawnguard DLC integration option for the Stones of Barenziah (No Stones Unturned) but not the Dragonborn DLC one. So I fixed that.

#### Mod Installation

- **Landscape:** Changed Blended Roads instructions to simply use the Medieval Bridges optional file.
- **Food & Ingredients:** Removed Unique Stros M'Kai Rum (encountered a CTD in connection with it that needs further investigating).
- **Apparel & Weapons:** Added instructions to install the new hotfix for LeanWolf's Better-Shaped Weapons.
- **Improved Vanilla Quests:** Added Buyable Golden Claw.
- **Improved Vanilla Quests:** Added instructions to download Andrealphus' Gameplay Tweaks - Stones of Barenziah - Solstheim.
- **College of Winterhold:** Added instructions to select the Viewable Faction ranks patch in the Obscure's COW FOMOD.
- **Miscellaneous:** Added Viewable Faction Ranks.

#### Mod Configuration

- Rephrased instructions for Timing Is Everything so applying the preset no longer feels optional.

#### Gameplay Guide

- **Quests:** Added a new page to cover changes to quests, level requirements, etc.

#### Conflict Resolution Patch

- **4.0.1:** Updated for Adamant 4.2.7
- **4.0.1:** Fixed the preset functionality in tie_mcmscript.pex
- **4.1:** Reverted amount of pamphlets to be distributed in the Spread the Love quest to vanilla (30 > 20)
- **4.1:** Increased buy price for the Golden Claw from 500 to 5000 Septims

#### Wabbajack Installer

- Updated Adamant - A Perk Overhaul to 4.2.7
- Updated Aetherius - A Race Overhaul to 2.4.0
- Updated Mundus - A Standing Stone Overhaul to 1.4.0
- Updated Timing Is Everything - TPF Preset to 1.1
- Updated Conflict Resolution Patch

## Release 4.0 Final

> 09/02/2021

After a rather long Beta phase and rather more substantial updates than I had planned to do, we have finally arrived at a point where I consider 4.0 polished enough for a full release.

#### Initial Setup

- **INI Files:** Added note to ignore Skyrim not recognising newer AMD cards.
- **INI Files:** Increased values in View Distance tab (attempt to fix fade-in of lanterns).

#### Mod Installation

- **Essential Mods:** Replaced the buggy Autorun Console Commands with Umgak's remade Autorun.
- **Landscape:** Added Blended Roads (version packaged with Cath Landscapes is outdated).
- **Landscape:** Added instructions to remove a file from Northside to fix moss tiling.
- **Landscape:** Removed Ashbound (redundant with the latest versions of Better Dynamic Ash).
- **Interiors:** Added Ennead Banners - RUGNAROK Patch.
- **Dungeons:** Re-added ENB Particle Lights - Dwemer Lanterns - Ancient Dwemer Metal Patch.
- **Dungeons:** Re-added Rudy HQ - Bthardamz - Dwemer Ichor Barrel Patch.
- **Food & Ingredients:** Added Unique Stros M'Kai Rum.
- **Non-Player Character:** Removed Simple Offence Suppression MCM - Block Friendly Fire.
- **Improved Vanilla Quests:** Added Radiant Requirements MCM.
- **Improved Vanilla Quests:** Added Radiant Requirements MCM - TPF Preset.
- **College of Winterhold:** Added note to Misc College of Winterhold to activate previous mods before the FOMOD.
- **Balancing:** Added missing download instructions for Faster Mining Plus.
- **Balancing:** Updated instructions for amidianBorn Armor Variants Lite.
- **Miscellaneous:** Added Horses for Followers.
- **Sounds & Music:** Fixed link for Phoenix - Merged Music Patch.

#### Finalisation

- **First Launch:** Slightly rewrote the last bit to not make it seem as if you were done with the guide at this point.

#### Wabbajack

- Added instructions to re-enable VSYNC for those who need it.

#### Mod Configuration

- Added note about the carriage ride and a potential glitch.

#### Gameplay Guide

- Added section about Radiant Requirements.

#### Appendix

- **Troubleshooting:** Rewrote section on grass shadows or lack thereof.
- **Troubleshooting:** Added fix for black waterfalls.

#### Conflict Resolution Patch 

- Removed Ashbound as a master.
- Cleaned unnecessary edits from cell and worldspace records.
- Resolved conflicts for Radiant Requirements MCM.
- Removed fix for conflicts between Finding Velehk Sain and aMidianBorn Armor Variants Lite (included in AVL's FOMOD).
- Added Dargor's Rock to cover up a hole near the Tomb of Ysgramor.
- Added a replacement mesh for the Skyforge HD LOD to fix it clipping outside of the city walls.

#### Wabbajack Installer

- Updated ENBSeries (no file version change)
- Updated Skyrim Landscape and Water Fixes to 5.9
- Updated moreHUD to 4.0.0.5Beta
- Updated DynDOLOD to 2.91
- Updated Cathedral - 3D Mountain Flowers to 1.8
- Updated Cathedral Player and NPC Overhaul to 4.3
- Updated Mysticism - A Magic Overhaul to 1.1.5
- Updated Adamant - A Perk Overhaul to 4.2.5
- Updated Adamant - Shrines and Amulets to 4.2.5
- Updated Blade & Blunt - A Combat Overhaul to 1.2.0
- Updated Arena - An Encounter Zone Overhaul to 1.1.0
- Updated Misc Tweaks - Shrines Don't Cure Diseases to 1.6
- Updated AllGUD Conditions Fix to 1.1
- Updated xLODGen to Beta 71
- Regenerated AllGUD for aMidianBorn Armor Variants Lite 1.0.1
- Regenerated TexGen, DynDOLOD, and Occlusion

## Release 4.0 Beta 7

> 29/01/2021

With the removal of Fuz Ro D'oh and new instructions for Keyboard Shortcuts Fix, the Clean-up page has essentially become redundant and was removed.

**Beta Testers:** To update to Beta 7, delete Fuz Ro D'oh in Mod Organizer 2 (Utilities separator). Then download the new Alchemy Adjustments - TPF tweaks mod, install it, update the CRP, download the new loadorder.txt and apply it. Done!

#### Mod Installation

- **Fixes:** Added instructions for Keyboard Shortcuts Fix to create its LOG file manually.
- **Trees & Plants:** Fixed missing picture for EL Solstheim 3D Trees.
- **Balancing:** Properly added Alchemy Adjustments - TPF Tweaks.
- **Utilities:** Removed Fuz Ro D'oh (no longer necessary now that AS LAL was removed).

#### Finalisation

- **Wrapping Up:** Expanded the Check for MO2 Warnings section.
- **Final Steps:** Slightly restructured the page and added the A New Playthrough section.
- **Clean-up:** Removed this page which has become redundant.

#### Appendix

- **Troubleshooting:** Marked one listed issue as resolved due to the removal of Fuz Ro D'oh.

## Release 4.0 Beta 6

> 29/01/2021

With this update, **Alternate Start - Live Another Life** (aka AS LAL), got the boot. Gonna be honest here, I've been meaning to remove that mod for a long, long time. Unfortunately, there never was a simple alternative to it that just puts you in a quiet place to go through MCM settings and character creation before the vanilla start. And, spoiler alert, there still isn't.

However, I discovered that the vanilla start - once a buggy mess in modded games - works perfectly fine in TPF. This is due to the fact that most mods no longer instantly fire all their scripts as soon as you start the game and we have very mods that run many scripts anyway. The overall stability of SSE and the decoupling of framerate and physics are helping here as well.

Without AS LAL, everyone is forced to go through the vanilla intro which makes balancing far easier for us. There is simply no way we can balance every single one of AS LAL's starting points so that it's a fair start for a new playthrough. I always recommended the vanilla start anyway. Additionally, AS LAL touches so many parts of Skyrim that it's essentially patching hell. Now we are rid of that, too.

The downside is that there is no quiet mod configuration spot before you are thrown into the game anymore. You will probably have to take a breather after escaping Helgen or later in Riverwood for the MCM stuff. I miss the convenience of the AS LAL cell but it's a small part of the mod and doesn't justify keeping the rest.

**Website structure:** As you may have noticed, I moved around some pages and added a new (WIP) Wabbajack page. The purpose of this is to have a clear distinction of guide sections for manual and for WJ users.

#### Introduction

- Temporarily removed link to mod spreadsheet (very outdated, will get to it).
- Added link to the new [playlist](https://www.youtube.com/playlist?list=PLj_QypS-aCNNyUBLpYsFAeCJk1Zq0xnmV) with music tracks added by mods in TPF.
- Expanded the Wabbajack section and added a FLOWCHART to make it obvious which sections WJ users need to follow.

#### Initial Setup

- **Mod Organizer 2:** Rewrote the Separator section to have DIY instructions (users make their own separators).
- **ESM Cleaning:** Actually fixed Dawnguard manual cleaning instructions (could have sworn I already did this).
- **ESM Cleaning:** Added note to uncheck SSEEdit Backups so that they don't clutter up your Overwrite.

*For Beta Testers: Re-cleaning Dawnguard.esm is not necessary. The problem was that I had custom Filter profiles that I thought were default. Users didn't have them though, so I had to rewrite the instructions without using a filter.*

#### Mod Installation

- **Instructions:** Added paragraph on creating new separators for each new page in the mod installation section.
- **Essential Mods:** Removed Alternate Start - Live Another Life (praise the Nine).
- **Fixes:** Updated FOMOD instructions for Landscape Fixes for Grass Mods (no longer selecting the AS LAL patch).
- **Tweaks:** Removed Multiple Floors Sandboxing (added to ACC).
- **Graphics Baseline:** Fixed file names in additional instructions for aMidianBorn Book of Silence.
- **Graphics Baseline:** Added instructions to delete the scripts folder from aMidianBorn Book of Silence.
- **Landscape:** Updated FOMOD instructions for Rorikstead Basalt Cliffs Patches (no longer installing the AS LAL patch).
- **Dungeons:** Added instructions to Underground to fix the shiny mud in Helgen.
- **Apparel & Weapons:** Fixed download instructions for Sunhallowed and Bloodcursed Arrows (Optional Files > Main Files).
- **Miscellaneous:** Removed Bounty Previews (late note from Beta 1, will be re-added very soon).

#### Finalisation

- **Wrapping Up:** Added instructions to create a new separator before installing the CRP.
- **Wrapping Up:** Removed sandboxcylinderheight.esp from list of plugins to ESL-ify (added to ACC).
- **Nemesis:** Added instructions to add a PATCHER OUTPUT separator.
- **DynDOLOD:** Added instructions to click "Advanced" in the window that comes up when *not* generating 3D tree LOD.
- **Occlusion:** Improved instructions for generating Occlusion (minor rephrasing).
- **First Launch:** Updated for the removal of Alternate Start.
- **Clean-Up:** Moved instructions to check MO2 for errors here.

#### New Game

- This section was completely removed.
- Most of the FINAL STEPS page was redundant except for the MO2 error check which was moved to Clean-up instead.
- The MOD CONFIGURATION page is now a top-level page.
- The GAMEPLAY GUIDE page is now a top-level page.

#### Wabbajack

- Added this new top-level page with instructions for the Wabbajack version of TPF.

#### Mod Configuration

- **Mod Configuration:** This is now a top-level page.
- **Mod Configuration:** Temporarily removed the (fairly pointless) instructions for GIST. Will add proper ones in the future.

#### Gameplay Guide

- **Gameplay Guide:** This is now a top-level page.
- **Gameplay Guide:** Added a far too detailed section about the music mods added in TPF.

## Release 4.0 Beta 5

> 26/01/2021

As you may have noticed, the **ENBSeries** section has vanished from the sidebar. What happened? It was reintegrated. Everything from those pages was moved back into the main body of the guide with ENBMan, binaries, and preset installation being a step in the Finalisation. This was done in order to further streamline the guide and eliminate optional paths and variations.

Also removed was **Nether's Follower Framework** after some internal discussions. Overtime, NFF has grown from a lightweight follower overhaul to an excessively bloated mod doing all kinds of things. While it remains high quality, the vast majority of features are misplaced in a v+ setup. Additionally, combat is easier for us to balance knowing that players are limited to a single follower like in vanilla. Some features of NFF were replaced by other mods.

**New save required** once again because of the removal of NFF. Sorry. =(

#### Introduction

- Updated more outdated parts of the introduction page.

#### Initial Setup

- **INI Files:** Reintegrated ENB-related tweaks (disabling AO, increasing particle count).

#### Mod Installation

- **Tweaks:** Added Followers Don't Draw Weapons.
- **Tweaks:** Added Multiple Floors Sandboxing.
- **Interface:** Fixed file name in download instructions for Fix Note Icon for SkyUI.
- **Graphics Baseline:** Updated AMB instructions (Content Addon version not needed with AVL).
- **Gameplay Overhauls:** Fixed file name in download instructions for Skyrim Uncapper - Adamant Arena.
- **Non-Player Characters:** Added Simple Offence Suppression.
- **Non-Player Characters:** Added Simple Offence Suppression MCM - Block Friendly Fire.
- **Non-Player Characters:** Removed Nether's Follower Framework.
- **Non-Player Characters:** Removed NFF - Disable Craftables.
- **College of Winterhold:** Added note to Obscure's College FOMOD instructions to specifically disable the HMB patch.
- **Combat & Encounters:** Added Better Stealth AI for Followers.
- **Combat & Encounters:** Added Follower Trap Safety.
- **Combat & Encounters:** Added instructions to download the Follower Trap Safety Patch for Improved Traps.
- **Combat & Encounters:** Removed Improved Traps - Nether's Follower Framework Bear Trap Fix.
- **Miscellaneous:** Removed additional instructions from Saddlebags that would remove its Horse Call power.
- **Utilities:** Added Spell Perk Item Distributor.
- **Utilities:** Removed UIExtensions (was only installed for NFF).

#### Finalisation

- **Wrapping Up:** Added Followers Don't Draw Weapons.esp to the list of plugins to ESL-ify.
- **Wrapping Up:** Added sandboxcylinderheight.esp (Multiple Floors Sandboxing) to the list of plugins to ESL-ify.
- **DynDOLOD:** Added skippable instructions on how to remove DynDOLOD's meme loading screens.
- **ENBSeries:** Added this new page which includes many instructions from the now removed ENBSeries section.
- **ENBSeries:** Serio's ENB is now once again the default ENB preset for TPF due to its performance-friendly nature.
- **ENBSeries:** Added instructions on how to customise ENB screenshots in the global enblocal.ini file.

#### New Game

- **Mod Configuration:** Removed instructions for Nether's Follower Framework.
- **Mod Configuration:** Removed instructions for Growl - Werebeasts of Skyrim.
- **ENB Tweaks:** Removed this page as we are now using an already tweaked version of Serio's ENB.
- **Gameplay Guide:** Removed mention of Nether's Follower Framework.

#### Conflict Resolution Patch

- Removed playable flag from Hvergelmir's beards added to Cathedral NPCs (they have transparency issues).
- Removed playable flag from extra hair styles added by Aetherial Crown.

## Release 4.0 Beta 4

> 24/01/2021

Simon's werewolf overhaul is finally out now and replaced Growl which completes our suite of SimonRim mods for gameplay. Because of this and the update Scion received, a new save is required for Beta 4.

I also did some reshuffling. Again. It's better if I do it now before 4.0 is officially out.

#### Initial Setup

- **Skyrim and Steam:** Updated Game Language screenshot for the new Steam UI.
- **Skyrim and Steam:** Updated Disable Auto Updates screenshot for the new Steam UI.

#### Mod Installation

- **Gameplay Overhauls:** Removed Growl - Werebeasts of Skyrim.
- **Gameplay Overhauls:** Added Manbeast - A Werewolf Overhaul.
- **Gameplay Overhauls:** Added Simple Werewolf Favourite Howls Menu.
- **Improved Vanilla Quests:** Added The Companions - Don't Be A Milk Drinker.
- **Balancing:** Renamed "Crafting & New Gear" AGAIN. Yeah. Back to the old name.
- **Tweak Collections:** Added Misc Tweaks - More Expensive Player Homes.
- **Skeleton & Animations:** Fixed file name in download instructions for Immersive Dragons.
- **Skeleton & Animations:** Fixed file name in download instructions for Werewolf Claws Affect Spider Webs.
- **Tweak Collections:** Removed this section because it was dumb.
- **Tweak Collections:** Removed Morrowloot Miscellania - Dremora Bound Weapons.
- **Tweak Collections:** Moved Morrowloot Miscellania - Unleveled Uniques to Balancing.
- **Tweak Collections:** Moved Miscellaneous Tweaks Collection to Gameplay.
- **Tweak Collections:** Moved Andealphus' Gameplay Tweaks to Improved Vanilla Quests (as they all affect quests).
- **Tweak Collection:** Moved Assorted Tiny Tweaks to Tweaks.
- **Sounds & Music:** Added Around the Fire - Skyrim Fan-Made Music.

#### New Game

- **Mod Configuration:** Removed left-over MCM instructions for Diverse Dragons Collection.
- **Gameplay Guide:** Finally started working on this page.

#### Conflict Resolution Patch

- Removed the Draught of Fate Unwound from other leveled lists, now only available in Riften.
- Lowered amount of available Draughts of Fate Unwound in Elgrim's Inventory to 1.
- Tripled value of the Draught of Fate Unwound.
- Removed records and edits related to Growl - Werebeasts of Skyrim.
- Removed two meshes (related to removed mods, EEO and Growl).
- Fixed a conflict between Manbeast and Mortal Enemies.

## Release 4.0 Beta 3

> 24/01/2021

#### Introduction

- Fixed an oversight in the "Included Mods" list.

#### Mod Installation

- **Tweaks:** Removed xEdit tweak for Simply Smaller Wolves (moved to the CRP).
- **Interface:** Added Extended UI for Skyrim Uncapper.
- **Trees & Plants:** Fixed file name in download instructions for Enhanced Landscapes - Solstheim 3D Trees.
- **Creatures:** Added HD Werewolves.
- **Appearance:** Added instructions to Cathedral NPCs to delete one conflicting file.
- **Gameplay Overhauls:** Added note to Reliquary of Myth to explain why certain patches shouldn't be installed.
- **Non-Player Characters:** Added NFF - Disable Craftables.
- **Improved Vanilla Quests:** Added Timing Is Everything - Custom Preset (finally!).
- **Improved Vanilla Quests:** Fixed file name in download instructions for A Lovely Letter - Alternate Routes.
- **Combat & Encounters:** No longer merging optional and main file from No Road Predators Redone.
- **Combat & Encounters:** Removed Diverse Dragons Collection (most of the dragons are out of place in V+).
- **Combat & Encounters:** Removed Diverse Werewolves Collection.
- **Combat & Encounters:** Updated More Werewolves FOMOD instructions.
- **Miscellaneous:** Removed obsolete reference to a mod being optional from Shadowmarks.
- **Assorted Plugins:** Fixed file name in download instructions for Classic Sprinting Redone.
- **Sounds & Music:** Fixed formatting for Phoenix - Merged Music Patch.
- **Skeleton & Animations:** Fixed incomplete file path for downloads folder.

#### Finalisation

- **Cleanup:** Removed note referring to the possibility of having skipped a mod (which no longer exists).
- **Cleanup:** Removed leftover instructions for Simply Knock (which was removed).
- **Cleanup:** Removed one paragraph referring to the long removed Customisation section (the cake is a lie).

#### New Game

- **Mod Configuration:** Added instructions for Timing Is Everything (loading the custom preset).
- **Mod Configuration:** Removed note about potential CTDs from Wonders of Weather rain splashes option (they were fixed).

#### Conflict Resolution Patch

- Fixed the bucket by the Skyforge (a better collision mesh for the wrwalltierdivide01.nif).
- Moved some plants around the Bannered Mare to reduce clipping.
- Fixed conflict between the USSEP and Simply Smaller Wolves.
- Removed records and edits related to Diverse Dragons Collection.
- Removed records and edits related to Diverse Werewolves Collection.
- Disabled one of four werewolves placed by More Werewolves in the Morthal swamp.

## Release 4.0 Beta 2

> 21/01/2021

#### Initial Setup

- **Mod Organizer 2:** Removed instructions to install deorder's MO2 plugins (better suited to a beginner's guide).
- **ESM Cleaning:** Improved instructions for cleaning Dawnguard ESM manually.
- **ESM Cleaning:** Fixed broken link at the bottom to the next page.

#### Mod Installation

- Swapped the **Landscape** (11 > 10) and **Trees & Plants** (10 > 11) steps.
- **Weather:** Fixed link for Wonders of Weather - Less Opaque Rain Splashes for ENB.
- **Trees & Plants:** Fixed download instructions for Enhanced Landscapes - Solstheim 3D Trees.
- **Worldspace Additions:** Removed instructions to install an optional file for Solstheim Lighthouse (would be overwritten anyway).

#### Appendix

- **Troubleshooting:** Added instructions to enable BorderlessUpscale in SSE Display Fixes.
- **Known Issues:** Moved everything from this page to Troubleshooting and removed it.
- **Credits:** Updated for recent changes.

## Release 4.0 Beta 1

> 20/01/2021

Update 4.0 for The Phoenix Flavour is firmly taking the setup back to its "vanilla plus" roots. TPF is committing to low-impact mods that blend in well while doubling down on our performance-friendly visual enhancements. Many mods were removed in this update, some of the beloved favourites, but there are solid reasons behind each removal.

New mods include the custom made **Armor Variants Lite** which is an alternative to kryptopyr's CCOR-dependent aMidianBorn Content Addon, created by Umgak from scratch. I also re-added the much requested artifact overhaul **Reliquary of Myth** and completely rebuilt the appearance section which is now centered around **Cathedral NPCs**. And finally Fore's New Idles was replaced with the more recent and open source **Nemesis**.

**Removal of CBBE:** I only ever included CBBE because many people demanded it. It's not required by anything and half the time I have no idea whether a CBBE patch is required or not. I haven't noticed a difference between CBBE / vanilla body in regular gameplay, ever, and I'm sick of worrying that something might not work correctly. I have no idea how to use BodySlide and frankly, I'm not interested in figuring it out. At this point, CBBE is for me personally just additional headache for zero gain. Well, I guess my character's buttcheeks are low-poly now but I can just about live with that.

**Removal of CCOR and RDO:** Both Complete Crafting Overhaul Remastered and Relationship Dialogue Overhaul were removed in this update because of feature creep. In the case of CCOR, the feature creep is subtle but enough to disturb my V+ vibes. Almost all the features that I personally like were implemented by other means with a faction equipment crafting module being on my to do list. RDO was never properly ported to SSE to begin with, nobody is creating patches for it, and it touches a million different things. The effort of integrating it is almost comparable to CRF. I personally doubt I will even notice if it's missing so I removed it as well.

**Removal of ENB Lights:** While it adds some cool effects, I removed ENB Lights for the time being as it is somewhat annoying to handle. It edits plenty of meshes (which means added compatibility work) and isn't properly updated for some of the newer fire mods. I'll likely come back to this mod and reimplement parts of it in a later 4.x update.

**Removal of the Content Addon:** Since [Elysium](https://github.com/TitansBane/Elysium) is now a thing, I no longer feel any sort of pressure to add new content to TPF. First and foremost, the list is intended to improve the gameplay, balancing, and graphics of the base game (and that's difficult enough!). Some extra content mods are still in the guide (those adding equipment variants) as I cannot imagine playing without them.

#### Introduction

- Rewrote most of the page, updated the feature list, and added testimonials.

#### Initial Setup

- Updated and rephrased many section, added screenshots and replaced some with better ones.
- **Skyrim and Steam**: Renamed this page (used to be called Skyrim SE which is not very specific).
- **Skyrim and Steam**: Added instructions to delete leftover files after uninstalling the game.
- **Skyrim and Steam**: Added more detailed instructions and a screenshot for verifying that Skyrim SE is set to English.
- **Additional Tools**: Added instructions to add an exception to Windows Defender for CAO.

#### Mod Installation

- Updated many download instructions (incremented version numbers mostly).
- Removed all (optional) and (conditional) flags.
- Added instructions to merge additional files with the main file for many mods.
- **Installation Instructions**: Removed all references to optional mods which are no longer a thing.
- **Essential Mods**: Added instructions to UHDAP on how to download with a slow internet connection.
- **Essential Mods:** Added Disable USSEP Book.
- **Essential Mods:** Moved Weapons Armor Clothing and Clutter Fixes here.
- **Fixes:** Removed Skyrim Ultimate Eyemeshes Ruhmastered (included in Cathedral Player and NPC Overhaul).
- **Fixes:** Removed Eye Normal Map Fix (redundant with Cathedral NPCs).
- **Fixes:** Removed Eyes AO Clipping Fix (redundant with Cathedral NPCs / Expressive Facegen Morphs).
- **Fixes:** Removed ENB Brow Fix (redundant with Cathedral Player and NPC Overhaul).
- **Fixes:** Removed Double Sided Vertex Human Mouth Fix (redundant with Cathedral Player and NPC Overhaul).
- **Fixes:** Removed WoodElf - MaleHair - Fix (redundant with Expressive Facegen Morphs).
- **Fixes:** Added Blackreach Tentacle Mesh Fix.
- **Tweaks:** Moved Windhelm Segregation - Stay at New Gnisis Cornerclub here.
- **Tweaks:** Moved Alik'r Warriors Aren't Welcome here.
- **Interface**: Finally re-added Quick Loot Re.
- **Interface**: Removed Undiscovered Means Unknown (wasn't very popular among users).
- **Graphics Baseline:** Removed Caliente's Beautiful Bodies Enhancer (too much unjustified headache).
- **Weather:** Added WoW Dragon Mounds CTD Fix.
- **Weather:** Added Wonders of Weather - Less Opaque Rain Splashes for ENB.
- **Lighting:** Replaced Relighting Skyrim - No Player Homes with the new updated version.
- **Visual FX:** Replaced Subtle Wind FX with Less Distracting Blowing Snow Effects for ENB Particle Patch.
- **Landscape:** Slightly changed the order of mods (update Mod Order in MO2 accordingly).
- **Landscape:** Updated download instructions for Majestic Mountains (now downloading the DynDOLOD LOD Pack).
- **Landscape:** Updated FOMOD instructions for Majestic Mountains.
- **Landscape:** Added Cathedral Landscapes - Recolored Vanilla Swamp Grass Addon.
- **Landscape:** Cathedral Landscape - Windhelm Snow Bridge Fix.
- **Landscape:** Added Cathedral - 3D Pine Grass.
- **Landscape:** Removed The Elder Scrolls - Veydosebrom.
- **Landscape:** Removed Cathedral Landscapes - Veydosebrom Swamp Grass Addon.
- **Landscape:** Removed manual edit from RW2 (no longer necessary after updating mod order).
- **Landscape:** Added Bright Waterfall Fix for ENB.
- **Landscape:** Updated FOMOD instructions for Better Dynamic Snow.
- **Landscape:** Temporarily removed Enhanced Landscapes.
- **Landscape:** Temporarily removed Enhanced Landscapes - Dead Marsh Fixes (mod page hidden).
- **Landscape:** Updated FOMOD instructions for Rorikstead Basalt Cliffs Patches.
- **Landscape:** Removed Better Dynamic Majestic Mountains.
- **Landscape:** Removed Manor Roads (looks ugly).
- **Trees & Plants:** Updated Enhanced Vanilla Trees download instructions.
- **Trees & Plants:** Updated Enhanced Vanilla Trees - Alternative Branches FOMOD instructions.
- **Trees & Plants:** Removed Bent Pines II (it's been in the list forever and I love it but it's not very v+).
- **Trees & Plants:** Moved Immersive Fallen Trees here.
- **Trees & Plants:** Moved Immersive Fallen Trees Patch here.
- **Trees & Plants:** Removed Sacred Trees (regrown Gildergreen can look very ugly).
- **Trees & Plants:** Moved Rudy HQ - More Lights for ENB - Deathbells and Nirnroots here.
- **Trees & Plants:** Added Cathedral - 3D Mountain Flowers.
- **Trees & Plants:** Added Sufficiently Optimised Snowberries 3D.
- **Trees & Plants:** Added High Poly Blackreach Mushrooms.
- **Trees & Plants:** Added Rudy HQ - More Lights for ENB - Glowing Mushrooms.
- **Trees & Plants:** Added High Poly Gleamblossoms.
- **Worldspace Additions:** Added this new page.
- **Worldspace Additions:** Moved Point The Way here.
- **Worldspace Additions:** Moved Lanterns of Skyrim II here.
- **Worldspace Additions:** Updated download instructions for Lanterns of Skyrim II.
- **Worldspace Additions:** Updated FOMOD instructions for Lanterns of Skyrim II.
- **Worldspace Additions:** Moved Immersive Dawnguard Dayspring Patch here.
- **Worldspace Additions:** Moved Unique Border Gates here.
- **Worldspace Additions:** Moved Solstheim Lighthouse here.
- **Worldspace Additions:** Moved Solstheim - Skaal Fishing Camp here.
- **Cities & Towns:** Renamed this step (used to be called "Buildings & Interiors").
- **Architecture:** Removed Pfuscher's Manhole Texture.
- **Architecture:** Replaced STR - High Hrothgar with Halls of the Greybeards.
- **Architecture:** Added HD Reworked Falmer Architecture.
- **Misc Structures:** Added SD Farmhouse Fences Patch for True Nordic Farmhouses.
- **Misc Structures:** Updated FOMOD instructions for SLO - Stone Walls (no longer selecting the new ivy mesh).
- **Misc Structures:** Added Stockades of Skyrim.
- **Misc Structures:** Added WiZkiD Carriages.
- **Misc Structures:** Added Riekling Barrels SMIM.
- **Misc Structures:** Updated FOMOD instructions for Stunning Statues of Skyrim (no longer selecting Mehrunes).
- **Interiors:** Removed Rally's Pillows.
- **Interiors:** Added Vanilla Table Replacers.
- **Interiors:** Added Nordic Beds.
- **Interiors:** Added 4K Retexture for Nordic Beds.
- **Interiors:** Added Thrones of Skyrim.
- **Dungeons:** Removed instructions to delete textures/effects folder from Rudy HQ - Nordic Ruins.
- **Dungeons:** Added Dwemer Ichor Barrel 2K.
- **Dungeons:** Moved ENB Particle Lights - Dwemer Lanterns here.
- **Dungeons:** Moved Rudy HQ - More Lights for ENB - Bthardamz here.
- **Dungeons:** No longer selecting the Hearthfire Patch in the CC's Enhanced Ore Veins FOMOD.
- **Dungeons:** Removed additional instructions from CC's Enhanced Ore Veins (no longer necessary).
- **Dungeons:** Added Dwemer Ichor Barrel 2K.
- **Clutter:** Added Barenziah's Glowing.
- **Clutter:** Removed Rudy HQ - Miscellaneous (was almost completely overwritten anyway).
- **Clutter:** Replaced MAPS with RUSTIC MAPS (which is the new SSE port).
- **Clutter:** Removed Frankly HD Dragonbone (covered by HD Reworked Dragons).
- **Clutter:** Removed JS Purses and Septims (they look gorgeous and unfortunately do not blend in at all).
- **Clutter:** Updated RUSTIC SOULGEMS download instructions (patching now done in CRP).
- **Clutter:** Removed the RUSTIC SOULGEMS FOMOD instructions.
- **Clutter:** Moved Rudy HQ - More Lights for ENB - Soul Gems here.
- **Food & Ingredients:** Added Remiros' Dragonborn Alcohol HD.
- **Food & Ingredients:** Removed additional instructions from True Homecooked Meal (moved to CRP).
- **Food & Ingredients:** Moved Rudy HQ - More Lights for ENB - Torchbugs and Moths here.
- **Food & Ingredients:** Moved Rudy HQ - More Lights for ENB - Chaurus Eggs and Sacs here.
- **Apparel & Weapons:** Updated FOMOD instructions for Practical Female Armors (now once again selecting the AMB CA Patch).
- **Apparel & Weapons:** Added instructions to download the Falkreath Matched Color Fix for Frankly HD Stormcloak and City Guards.
- **Apparel & Weapons:** Added instructions to download the Frankly HD Imperial Armor and Weapons LeanWolf Patch.
- **Apparel & Weapons:** Removed additional instructions to delete meshes from Frankly HD Imperial Armor and Weapons.
- **Apparel & Weapons:** Removed instructions to install the CBBE patch for Frankly HD Dawnguard Armor and Weapons.
- **Apparel & Weapons:** Updated download instructions for Iron Things (the standalone bow file already includes the fixed mesh).
- **Apparel & Weapons:** Removed additional instructions for Iron Things (no longer necessary).
- **Apparel & Weapons:** Updated download instructions for Outlandish Stalhrim (now downloading the blue cubemap).
- **Apparel & Weapons:** Added Rudy HQ - More Lights for ENB - Daedric Weapons.
- **Apparel & Weapons:** Added HD Reworked Shellbug.
- **Apparel & Weapons:** Removed JS Barenziah (prefer Gamwich and Saerileth's retexture packaged with Forgotten Retex Project).
- **Unique Artifacts:** Replaced Unique Uniques - Plugin Replacer with Unique Uniques - Fixes.
- **Unique Artifacts:** Removed instructions to install the CBBE patch for Frankly HD Nightingale Armor and Weapons.
- **Unique Artifacts:** Removed instructions to install the CBBE patch for Frankly HD Miraak.
- **Unique Artifacts:** Added instructions to install the Hotfix for Frankly HD Miraak.
- **Unique Artifacts:** Added Remiros' Ebony Blade HD.
- **Unique Artifacts:** Added instructions to run Ghosu - Auriel's Quiver Replacer through SSE NIF Optimizer.
- **Unique Artifacts:** Added instructions to run Ghosu's Auriel's Quiver Retexture through SSE NIF Optimizer.
- **Unique Artifacts:** Added Remiros' Hrothmund's Axe HD.
- **Creatures:** Updated FOMOD instructions for Bellyache's Animal and Creature Pack (no longer selecting Bears).
- **Creatures:** Replaced HD Rabbit by Pfuscher with Real Rabbits HD.
- **Creatures:** Now selecting 2K textures in the True Wolves of Skyrim FOMOD (instead of 1K).
- **Creatures:** Added HD Reworked Bears.
- **Creatures:** Replaced CC's HD Dwemer Automatons - Remastered with Ancient Automatons.
- **Creatures:** Added Ancient Dwemer Metal - Missing Forgemaster Fix.
- **Creatures:** Replaced RUSTIC DRAGONS with HD Reworked Dragons which covers more dragon and so that the style is consistent.
- **Creatures:** Removed The Decayed Dragon - Durnehviir Retex (Durnehviir is covered by HD Reworked Dragons).
- **Creatures:** Removed HD Serpentine Dragon and Mesh Fix (serpentine dragon is covered by HD Reworked Dragons).
- **Appearance:** This page was completely redone.
- **Appearance:** Added Cathedral Player and NPC Overhaul (this replaces / includes all mods that were removed).
- **Appearance:** Added Expressive Facegen Morphs.
- **Appearance:** Moved DIVERSE SKYRIM here.
- **Appearance:** Added instructions to delete the BSA for DIVERSE SKYRIM.
- **Appearance:** Added DIVERSE SKYRIM - Cathedral NPCs Facegen Patch.
- **Appearance:** Updated FOMOD instructions for Forgotten Argonian Roots (selecting vanilla body instead of CBBE).
- **Appearance:** Removed additional instructions for Eyes AO Clipping Fix (no longer necessary).
- **Appearance:** Removed Just Fangs from BVFE (redundant with Expressive Facegen Morphs).
- **Appearance:** Added Beast Race Fang Removal.
- **Appearance:** Moved TK Children here.
- **Appearance:** Moved Simple Children here.
- **Appearance:** Removed Bijin Skin for CBBE.
- **Appearance:** Removed Skysight Skins.
- **Appearance:** Removed High Poly Male Meshes - Vanilla plus Seamless Head.
- **Appearance:** Removed Coverkhajiit.
- **Appearance:** Removed Painterly - A High Res Vanilla Warpaint Retexture.
- **Appearance:** Removed Northborn Scars.
- **Appearance:** Removed Natural Eyes.
- **Appearance:** Removed Khajiit Wild Eyes.
- **Appearance:** Removed Bed Head - A Vanilla Hair Replacement
- **Appearance:** Removed Argonian Improvements - Horns.
- **Appearance:** Removed Immersive Mouth and Teeth.
- **Appearance:** Removed Immersive Mouth and Teeth for Orcs.
- **NPC Overhauls:** This page was merged with Appearance.
- **NPC Overhauls:** Removed Vanilla NPCs Ruhmastered.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul - Stripped BSA.
- **NPC Overhauls:** Removed Windsong Immersive Character Overhaul - USSEP and CRF Patches.
- **NPC Overhauls:** Removed Ethereal Elven Overhaul.
- **NPC Overhauls:** Removed Ethereal Elven Overhaul - SSE Patch.
- **NPC Overhauls:** Removed DIVERSE SKYRIM - Ethereal Elven Overhaul Patch.
- **Gameplay Overhauls:** Moved More Expensive Transmute for Mysticism here.
- **Gameplay Overhauls:** Added instructions to download the Shrines and Amulets addon for Adamant.
- **Gameplay Overhauls:** Added Skyrim Uncapper.
- **Gameplay Overhauls:** Added Skyrim Uncapper - Adamant Arena.
- **Gameplay Overhauls:** Removed Complete Crafting Overhaul Remastered.
- **Gameplay Overhauls:** Removed Complete Crafting Overhaul Remastered - JS Circlet Replacer Patch.
- **Gameplay Overhauls:** Replaced Sacrosanct with Scion - A Vampire Overhaul.
- **Gameplay Overhauls:** Removed Trua - Minimalistic Faiths of Skyrim.
- **Gameplay Overhauls:** Moved Trade and Barter here.
- **Gameplay Overhauls:** Added Trade and Barter - Mysticism and Adamant Patches.
- **Gameplay Overhauls:** Re-added Reliquary of Myth - Artifact Overhaul.
- **Gameplay Overhauls:** Moved Genuinely Intelligent Soul Gems here.
- **Gameplay Overhauls:** Updated download instructions for Carriage and Ferry Travel Overhaul (Dawnstar patch no longer needed).
- **Gameplay Overhauls:** Removed CFTO - Winterhold Carriage.
- **Gameplay Overhauls:** Added Carriage and Ferry Travel Overhaul - Fixes and Winterhold.
- **Gameplay Overhauls:** Added Carriage and Ferry Travel Overhaul - Cathedral NPCs Facegen Patch.
- **Gameplay Overhauls:** Removed Night Eye Overhaul.
- **Gameplay Overhauls:** Removed Night Eye Overhaul - Plugin Replacer.
- **Non-Player Characters:** Moved Run For Your Lives here.
- **Non-Player Characters:** Moved Tavern AI Fix here (it doesn't really constitute as a fix).
- **Non-Player Characters:** Removed AI Overhaul - Windsong Immersive Character Overhaul Patch.
- **Non-Player Characters:** Removed AI Overhaul - Ethereal Elven Overhaul Patch.
- **Non-Player Characters:** Removed Relationship Dialogue Overhaul.
- **Non-Player Characters:** Updated download instructions for Hunters Not Bandits (no longer downloading the RDO version).
- **Non-Player Characters:** Updated Nether's Follower Framework FOMOD instructions.
- **Non-Player Characters:** Added Immersive Patrols - Cathedral NPCs Facegen Patch.
- **Improved Vanilla Quests:** Removed Even Better Quest Objectives.
- **Improved Vanilla Quests:** Removed Gildergreen Regrown (looks awful).
- **Improved Vanilla Quests:** Removed The Paarthurnax Dilemma.
- **Improved Vanilla Quests:** Added The Paarthuranx Resolution.
- **Improved Vanilla Quests:** Removed Castle Volkihar Rebuilt.
- **College of Winterhold:** Added this new step because of all the mods related to the college.
- **College of Winterhold:** Moved Obscure's College of Winterhold here.
- **College of Winterhold:** Updated Obscure's College of Winterhold FOMOD instructions.
- **College of Winterhold:** Added Obscure's College of Winterhold - Cathedral NPCs Facegen Patch.
- **College of Winterhold:** Moved Immersive College NPCs here.
- **College of Winterhold:** Added Immersive College NPCs - Cathedral NPCs Facegen Patch.
- **College of Winterhold:** Moved Improved College Entry - Questline Tweaks here.
- **College of Winterhold:** Moved Misc College of Winterhold Tweaks here.
- **College of Winterhold:** Updated Misc College of Winterhold Tweaks FOMOD instructions.
- **College of Winterhold:** Moved Choose Your Own Archmage here.
- **College of Winterhold:** Moved Finding Velehk Sain here.
- **Combat & Encounters:** Re-added Mortal Enemies.
- **Combat & Encounters:** Re-added Realistic Melee Range.
- **Combat & Encounters:** Removed Beast Skeletons.
- **Combat & Encounters:** Removed Beast Skeletons - Plugin Replacer.
- **Combat & Encounters:** Added proper FOMOD instructions for DMC for a vanilla-like player werewolf replacer.
- **Balancing:** This step was removed. Its mods were split up among other categories or removed from the guide.
- **Balancing:** Removed Economy Overhaul and Speechcraft Improvements.
- **Balancing:** Removed Zim's Immersive Artifacts (mostly covered by ROM now).
- **Balancing:** Removed Unique Items Tweaks (might be re-added later).
- **Crafting & New Gear:** This is basically the old Balancing step - but quite different.
- **Crafting & New Gear:** Added Lightweight Smithing Tweaks.
- **Crafting & New Gear:** Added Faster Mining Plus.
- **Crafting & New Gear:** Added Craftable Torches.
- **Crafting & New Gear:** Added Craftable Lockpicks.
- **Crafting & New Gear:** Moved Armor and Clothing Extension here.
- **Crafting & New Gear:** Moved Armor and Clothing Extension (WACCF) - MCM Menu Fix here.
- **Crafting & New Gear:** Added Tweaks for WACCF and ACE.
- **Crafting & New Gear:** Removed aMidianBorn Content Addon.
- **Crafting & New Gear:** Added aMidianBorn Armor Variants Lite.
- **New Gear:** Removed this step and all mods remaining here.
- **New Gear:** Removed Weapon Armor Clothing and Clutter Fixes - CBBE Patch.
- **New Gear:** Removed Common Clothes and Armors (may be re-added in the future).
- **New Gear:** Removed Common Clothes and Armors - CBBE Patch.
- **New Gear:** Removed Armor of Yngol.
- **New Gear:** Removed Kthonia's Unique Weapon Pack.
- **Tweak Collections:** Added this new step.
- **Tweak Collections:** Moved Morrowloot Miscellania here.
- **Tweak Collections:** Updated download instructions for Morrowloot Miscellania.
- **Tweak Collections:** Moved Miscellaneous Tweaks Collection here.
- **Tweak Collections:** Updated FOMOD instructions for Misc Tweaks - Shrines Don't Cure Diseases.
- **Tweak Collections:** Added Misc Tweaks - Night Eye Redux.
- **Tweak Collections:** Moved Andrealphus' Gameplay Tweaks here.
- **Miscellaneous:** Moved Irondusk's Saddlebags here.
- **Miscellaneous:** Removed Simply Knock.
- **Miscellaneous:** Removed Simply Knock SKSE64 DLL.
- **Miscellaneous:** Removed Dragon Remains.
- **Miscellaneous:** Removed Talkative Dragons (can get repetitive).
- **Miscellaneous:** Removed Talkative Dragons - Audio Replacer.
- **Miscellaneous:** Removed Keeper Carcette Survives.
- **Miscellaneous:** Added Simple Player Home Improvements.
- **Assorted Plugins** Added this new page to collect the various SKSE- and NSF-based plugins.
- **Assorted Plugins:** Moved Whose Quest Is It Anyway here.
- **Assorted Plugins:** Moved Yes I'm Sure here.
- **Assorted Plugins:** Added No Attack Messages.
- **Assprted Plugins:** Added Sales Overflow Solved.
- **Assorted Plugins:** Moved Better Stealing here.
- **Assorted Plugins:** Added instructions to lower the MaxPrice value for Better Stealing.
- **Assorted Plugins:** Moved Remember Lockpick Angle - Updated here.
- **Assorted Plugins:** Moved No Lockpick Activate - Updated here.
- **Assorted Plugins:** Moved Classic Sprinting Redone here.
- **Assorted Plugins:** Moved Better Jumping here.
- **Assorted Plugins:** Added I'm Walkin' Here.
- **Assorted Plugins:** Added Free Look.
- **Assorted Plugins:** Moved Uninterrupted Invisibility here.
- **Assorted Plugins:** Moved Uninterrupted Ethereal Form here.
- **New Music:** Merged with the Sound Effects page.
- **Sounds & Music:** Renamed from Sound Effects as this page now also includes the additional music mods.
- **Sounds & Music:** Updated FOMOD instructions for Immersive Sounds Compendium.
- **Sounds & Music:** Removed OMINOUS Dragon Soul Absorb Music.
- **Sounds & Music:** Removed the TPF Merged Music Patch (now part of the main CRP).
- **Skeletons & Animation:** Replaced FNIS with Nemesis Ultimate Behaviour Engine.
- **Skeletons & Animation:** Replaced XPMSSE Automated Patcher with a direct link to the fixed scripts.
- **Skeletons & Animation:** Added AllGUD Conditions Fix.
- **Utilities**: Removed the FISSES ESL-ified Patch.
- **Utilities**: Removed Copy and Paste in Console.

#### ENBSeries

- **Preset Installation:** Updated instructions for Rudy ENB 2.0.
- **Other Presets:** Slightly updated some sections of this page to be consistent with other 4.0 changes.
- **Related Mods:** This section was removed. Most included mods were moved to the main Mod Installation section.
- **Related Mods:** Removed ENB Lights.

#### Finalisation

- **Wrapping Up:** Updated and expanded list of plugins to be ESL-ified.
- **FNIS:** Removed this page as FNIS is no longer part of TPF.
- **Nemesis:** Added this page with instructions for Nemesis which replaced FNIS.
- **AllGUD:** Removed instructions to clean masters for the Alt Textures patch (no longer necessary).
- **AllGUD:** Added instructions to install the fixed Weapon Mesh Generator Script.
- **DynDOLOD:** Slightly updated and improved some of the instructions.
- **Occlusion:** Added this new page with instructions to regenerate occlusion data.

#### Finalisation

- **Mod Configuration:** Removed instruction for mods no longer present in the guide.
- **Mod Configuration:** Added instructions to bind the NFF Horse Whistle hotkey.
- **Mod Configuration:** Added MCM instructions for Storm Lightning.
- **Mod Configuration:** Added MCM instructions for Trade & Barter.
- **Mod Configuration:** Added a picture for the Wonders of Weathers MCM instructions.