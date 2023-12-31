---
title: Changelog
weight: 1
---
Changelogs of this fashion were not written before compiling to Wabbajack. The modlist has undergone a very large number of changes over the years before this point. Most times, if I have changed a mod in any way, I created Notes for that mod in Mod Organizer, which you can view by hovering over the notepad icon on the mod in the left pane of MO.

Basic conflict resolution when adding a mod is generally not included here, every addition to the list is vetted thoroughly. Only if existing conflict resolution was flawed and fixed, will it be included here.

If the third number in a version (the 3 in 9.1.3) is changed or added, then that version is **NOT SAFE** to update to on an existing save at all. If the fourth number in a version (the 4 in 9.1.3.4) is changed or added, then that version should be safe to update to on an existing save, but you may encounter some non-breaking issues. This schema will be changed when the mod list reaches version 1.0.

## v0.9.5.6 - **12/31/2023**

This tiny update simply disables Ominous ENB in the Refined profile, as it was enabled alongside Serio's ENB by mistake. If you have already updated to 0.9.5.5, you can ignore this update and change the ENB that is enabled as you choose.

## v0.9.5.5 - **12/31/2023**

New Years Eve update! This version fixes a rather consistent crash involving certain spells, as well as a few other bugs! This version should be save-safe.

Quite a few spells have been added, modified or removed in multiple spell mods that have been updated. You may lose a few of your spells on existing saves!

### Updated

- Community Shaders - 0.6.6 > 0.7.4
- Screen Space Shadows - 1.1 > 1.1.2
- Complex Parallax Materials - 1.0 > 1.0.2
- Water Blending - 1.0 > 1.1
- Tree LOD Lighting - 1.1 > 1.2.0
- Grass Lighting - 1.3.2 > 1.4.0
- Grass Collision - 1.1 > 1.2
- Light Limit Fix - 1.0.2 > 1.2.0
- Light Limit Fix - 1.0.2 > 1.0.3
- Thunderbolt - HD Lightning - 1.0 > 2.0
- Goat HD by Pfuscher - 1.0 > 2.0
- Radiant Requirements - 1.1 > 1.2
- Madmen - A Forsworn Overhaul - 2.0 > 2.2
- Madmen - A Forsworn Overhaul Patch Collection - 2.0 > 2.0.2
- Vulcano - 1.0.9 > 1.2.5
- Arclight - 1.0.4 > 1.1.5
- Desecration - 1.0.5 > 1.1.7
- Lunaris - 1.2.2 > 1.3.5
- Stellaris - 1.1.2 > 2.0.6
- Necrom - 1.1.1 > 2.0.5
- Natura - 3.1.2 > 4.0.5
- Bloodmoon - 1.2.3 > 2.0.5
- Abyss - 3.0.2 > 3.1.5
- Arcane - 1.0.2 > 1.1.6
- True Directional Movement - 2.2.4 > 2.2.5
- Weapon Styles - Draw Sheathe Animations for IED - 1.1 > 2.1
- NPC Animation Remix - 1.6.2 > 1.8.0
- Immersive Folded Hands - 1.5 > 1.6.1
- Organic Player Animations - 1.1 > 1.2.1
- Improved Table Transition Animations - 1.2 > 1.3
- Modern Female Sitting Animations Overhaul - 1.6 > 1.8
- Spell Perk Item Distributor - 6.6.2 > 6.7.6
- ZedPatch - 0.9.5.2 > 0.9.5.5
- Synthesis Output - 0.9.5.2 > 0.9.5.5
- Nemesis Output - 0.9.5.2 > 0.9.5.5
- Bodyslide Output - 0.9.5 > 0.9.5.5
- Overwrite Misc - 0.9.5 > 0.9.5.5

### Fixes

- Fixed crashes near certain Hagravens or other magic-using NPCs due to outdated Darenii Spell mods in use with Madmen patch.
- Fixed missing preset for Radiant Requirements during startup
- Unbound SkyUI group keys by default
- Disabled LamasTinyHUD feature to equip current loadout on loading save, as it would unequip everything if you have nothing set.
- Fixed sneak animations never applying due to their DAR priority being too low. Enhanced sneak animations will now be used after getting the Trespasser perk.
- Corrected wobbly sneak archery animations.
- Corrected Steel Fashions Berserker armor causing women to float.
- Removed redundant pre-made Sorcerer patches that are patched by the Synthesis patcher.

## v0.9.5.4 - **12/10/2023**

### Updated

- Blank CC Plugins - 0.9.3 > 0.9.5.4

### Fixes

- This version overrides the new `_ResourcePack.esl` plugin with a blank plugin, fixing freezes that were consistently occurring in certain parts of the map.

## v0.9.5.3 - **12/10/2023**

This version makes the list installable again, after the recent Skyrim update(s). The changes made to do so will also allow the list to be more resistant to updates in the future.

There are no other changes made with this version!

## v0.9.5.2 - **11/9/2023**

This version was released early due to changes to Skyrim-Guild mods. Two have had their links changed, and one (Creatures Preview) was removed. This will unfortunately remove the Dragon, Bear, and Sabre-cat animations in the list. If it is re-added, the next version will contain it again.

This version is save safe, though you may observe some changes not apply on an existing save.

### Removed

- Oblivionesque Locks
- Creatures - DXPMCO

### Added

- SkyTEST 2022 Redux - Realistic Animal and Predators 2K
- Sirenroot - Frissa Sleep Package
- Armors of The Velothi Pt.2 Bonesaint Plume Fix

### Updated

- MonsterPatch - 0.9.5 > 0.9.5.2
- ZedPatch - 0.9.5 > 0.9.5.2
- ZedPatch2 - 0.9.5 > 0.9.5.2
- Synthesis Output - 0.9.5 > 0.9.5.2
- Occlusion Output - 0.9.5 > 0.9.5.2
- Nemesis Output - 0.9.5 > 0.9.5.2

### Fixes

- Changed download links for skyrim-guild mods to new modding-guild URL.
- Corrected load order for Sorcerer to place patches below it. Changes were carried over in conflict resolution, however the load order was not good practice.
- Corrected a few NPCs from Immersive College NPCs from being bald with hair patches.
- Stopped NPCS in The Ratway from attacking the tiny SkyTEST rats.
- Corrected inconsistent cell water types around Goldenglow Estate.

### Tweaks

- Reduced the amount of wolves in the Falkreath Leshen encounter.
- Expanded trigger box for Mjoll/Aerin conversation in Riften such that it will trigger if you enter from the other side of the city.
- Added a sleep package and bedroll for Frissa Black-Briar in Elgrim's Elixirs, so that you can steal from the store at night.

## v0.9.5.1 - **10/16/2023**

### Fixes

This version very simply includes Campfire, Campfire - Survival Mode Patch, and Custom Skills Framework Unified Menu - Dear Diary Dark, which were left out of the list compilation on accident, as these are disabled-by-default mods. Confirmed that these were the only ones missing. Absolutely a save-safe update!

## v0.9.5 - **10/14/2023**

This version is ABSOLUTELY NOT save-safe! You cannot use any existing saves with this version.

This version introduces a Performance Profile! This is in a simple state as of now, introducing reduced DynDOLOD Output and the use of Community Shaders instead of ENB! Along with this change, 3D Tree LOD has been enabled in the default profile, which will retain it's ENB usage along with a new optional preset! Further performance enhancements will be added to the Performance Profile as time goes on, some of which will be introduced to the entire list. You can switch between the Default "Refined" and the new "Refined - Performance" profiles with the drop down menu above the left pane of Mod Organizer. Keep in mind that any changes you make to mods in the list will not be reflected across profiles, this includes the optional "Enhanced Survival Mode" mods.

Along with the above change, "Safe-Specific Saves" have been disabled for each profile. Your saves will now be read from "My Games/Skyrim Special Edition" in your Documents directory. You should not be expecting to retain old saves with this version, but make CERTAIN you have backed up any saves you care about before updating nonetheless.

We've replaced iEquip with the modern and *extremely responsive* LamasTinyHUD. Never again will you die as you wait for iEquip to catch up. The mod offers a rather intuitive system for setting up your load outs, and doesn't miss a single beat when switching your weapons. The mod also offers a nearly identical system for quick potions, so you will not be missing easy access to healing while in combat. We have also added the new Wheeler Wheel Menu! This is set to Q by default, with the vanilla Favorites menu rebound to Y. These two mods together give you very quick and instant access to your entire arsenal!

An interesting addition to the list with this version is **Fast Travel Cost**. It will now require Gold/Septims for you to Fast Travel. The cost is calculated based on distance. This was added to incentivize exploring the world, but still allow you to Fast Travel if you wish, at the expense of your ever-growing coffers!

We've also removed our existing Companions questline tweak mods, and added the Companions module from At Your Own Pace! This introduces a myriad of changes to the Companions questline, allowing many more types of characters to play the questline, among many other great changes!

I would also be re-missed to not mention **Remote Interactions**. This mod opens up a seriously cool dynamic to interacting with NPCs in the world, allowing you to, well, interact remotely! The hotkey to initiate this is **B**. Jayserpa never disappoints!

This update is *quite* large, and the above description does not cover everything. Be sure to read the full changelog below!

### Removed

- Skyrim Platform
- Weapon Speed Effects Fix
- Winterhold Bridge Occlusion Fix
- iEquip (Replaced with LamasTinyHUD)
- Alternate Conversation Camera (Replaced with Improved Alternate Conversation Camera)
- CoMAP (Will be added back in future)
- Relighting Skyrim - No Player Homes (Updated)
- Realistic Bark Textures - Spruce 8K
- Aspen Bark HQ Variants - Birch 4K
- Spice of Life - Orc Longhouses
- Daedric Shrines - Individual Mods (Replaced with AIO)
- Modernize - HDT Clothing
- Improved Companions - Questline Tweaks
- The Companions - Don't Be A Milk Drinker
- More Radiant Quests for the Companions
- Skyrim Uncapper (Replaced with Skyrim Skill Uncapper)
- Super Simple Lock Bash (Replaced with Lockpicking for Barbarians)
- Forceful Tongue - Shouts Overhaul (Replaced with Stormcrown)
- Dragon Aspect Overhaul
- Intuitive Dragon Ride Control
- Smart Automatic Attribute Leveling (SAAL)
- Enchanting Adjustments Updated
- Follower Commentary Overhaul
- Ilieh - Cry of the Damned
- Redoran Exile Armor
- Redoran Exile Armor - HIMBO Refit
- Genuinely Intelligent Soul Trap - ESL Script
- Immersive Dawnguard Dayspring Pass (Fix https://github.com/zediious/tpfz-sprinkles/issues/75)
- The Warrior of Rivercrest
- Fugitive of the Natural Order
- Mihail Monsters and Animals - Crows (Replaced with Mihail Monsters and Animals - Crows and Ravens)
- Forsworn Skinchangers (Added in Madmen - A Forsworn Overhaul)
- Forsworn Gravesingers (Added in Madmen - A Forsworn Overhaul)
- Rain Extinguishes Fires (fix https://github.com/zediious/tpfz-sprinkles/issues/33)
- Aela Doesn't Approach If You Don't Help
- Sales Overflow Solved (Replaced with Barter Limit Fix)
- Use or Take
- Read or Take
- Uninterrupted Invisibility (Replaced with Enhanced Invisibility)
- Immersive Sounds - Yggdrasil Patch
- Dynamic Animation Replacer (Replaced with Open Animation Replacer)
- XP32 Maximum Skeleton Special Extended - Fixed Scripts
- XP32 Weapon Styles Uncloaked
- Dynamic Animation Casting (Replaced with NG)
- iFrame Generator (Replaced with NG)
- Flinching (Already included in Precision)
- Vanargand Animations - Female Idle Walk and Run (Replaced with V2)
- Vanargand Animations - Male Idle Walk and Run (Replaced with V2)
- Vanargand Animations - Sprint (Replaced with V2)
- EVG Animated Traversal - Maleficus' Patches
- EVG Animated Traversal - Windhelm Capital Expansion
- Rapier Moveset for MCO. (Replaced with ER Rapier)
- Don't Sheathe Bound Weapons
- Facegen

### Added

- SSE Creation Kit Fixes Update
- D3D Compiler (Disabled by default)
- Community Shaders (Disabled by default)
- Vanilla HDR (Disabled by default)
- Screen-Space Shadows (Disabled by default)
- Auto Parallax (Disabled by default)
- Complex Parallax Materials (Disabled by default)
- Water Blending (Disabled by default)
- Tree LOD Lighting (Disabled by default)
- Grass Lighting (Disabled by default)
- Grass Collision (Disabled by default)
- Light Limit Fix (Disabled by default)
- Go to Bed - Campfire Patch (Disabled by default)
- MQ105SprintTriggerScript Fix
- DLC2PillarBuilderActorScript Tweak
- DLC2dunSeekerInvisScript Fix
- DLC2MiraakScript Fix
- DLC2dunFrostmoonTriggerScript Optimization
- DLC2AudioRepeaterActivator01Script Tweak
- Shroud Hearth Barrow Script Fix
- The Taste of Death Improved Shutdown
- Beneath Bronze Waters Start Fix
- Naked Dead NPC Fix
- Dual Casting Fix
- World Encounter Hostility Fix
- Stuck on Screen Load Door Prompt Fix
- Zero Bounty Hostility Fix
- Green Water Cubemap Fix
- NPC Stuck in Bleedout Fix
- Camera Persistence Fixes
- Informed Mail Delivery
- Custom Skills Framework Unified Menu
- Inventory Interface Information Injector
- Inventory Interface Information Injector for Skyrim 1.5
- Constructible Object Custom Keyword System
- C.O.C.K.S for Skyrim 1.5
- Dear Diary Light Skin for C.O.C.K.S
- Dear Diary C.O.C.K.S. Mode
- LamasTinyHUD
- dMenu
- Wheeler - Quick Action Wheel of Skyrim
- Improved Alternate Conversation Camera
- Switch Camera During Dialogue
- No Furniture Camera
- Show NPC Disposition Relationship Rank
- DynDOLOD DLL NG
- Simple Snow Improvements - Skyrim
- Simple Snow Improvements - Solstheim Ruins
- Maximum Carnage - All Patched Up
- Natural Waterfalls
- Obsidian Mountain Fogs
- ALT - The Snow Elves Throne
- FYX - 3D Stockades - Walls and Gate
- Windhelm Entrance Fix
- Whiterun Objects SMIMed - Dragonsreach Stairs
- Skyrim Objects SMIMed - Farm Mills
- FYX - Nordic Doors and Traps Collisions
- FYX - Imperial Doors Collisions
- FIXED Highpoly Nordic Metal Grate
- Daedric Shrines - All in One
- Daedric Shrines - All in One - Xtudo Patches
- Daedric Shrines and Pilgrim Consistency and Tweaks
- Statue of Kynareth
- Statue of Kynareth - Xtudo Patches
- Statue of Mara
- Statue of Mara - Xtudo Patches
- JS Unique Utopia - Rings
- Bloodskal Blade - Tweaks and Enhancements
- Bloodskal Tweaks and Enhancements - Horizontal Strike for MCO and SkySA
- Vigilant - re-enable beam strikes for MCO and SkySA
- DVA - Dynamic Vampire Appearance
- Courier Delivers to NPCs
- Additional Dremora Faces + Xtudo Fixes
- Vanilla Follower Expansion - Illia
- Relationship Dialogue Overhaul Lite
- Interesting (Useless) Relationships and Quest Comments
- Companions Dialogue Bundle
- NPCs React to Invisibility
- Brawl Lines Expansion and Fixes
- Dremora Lines Expansion
- Dialogue Expansion - Khajiit Caravans
- Dialogue Expansion - Indaryn-Ingun-Asgeir-Alessandra
- Dialogue Expansion - Shor's Stone
- Stable Masters - New Clothing
- Carriage Drivers - New Clothing
- Ferrymen - New Clothing
- Saints and Seducers - Growable Plants
- Immersive Death Cycle
- SkyClimb
- Thaumaturgy - VAE and AVE Patches
- Simplicity of Seeding
- Scorching of Skeevers
- Lockpicking for Barbarians
- At Your Own Pace - Companions Module
- The Heart of Dibella - Quest Expansion
- Namira for Good Guys
- Search and Seizure - Quest Expansion
- Mistwatch Ending - More Options
- Harvest Your Blood for Septimus
- You Handle Yourself Well - A Tougher Giant Encounter
- Ill Met Bolar's Oathblade
- Return to Pelagius' Mind
- Spooky Philter of the Phantom
- Fjori and Holfeir in Sovngarde
- Slower Markarth Assassination
- Capital Windhelm Expansion Eastern gate blackscreen and other fixes
- Whiterun Expansion city patches
- Strongholds - Narzulbur
- Strongholds - Largashbur
- Strongholds - Dushnikh Yal
- Strongholds - Mor Khazgur
- Environs - Master Plugin
- Environs - Hroggar's House
- Environs - Hroggar's House - Patch Collection
- Environs - Abandonded Abodes
- Environs - Abandonded Abodes - Patch Collection
- Ryn's Faendal's House
- JK's Riften Outskirts
- JK's Riften Outskirts Patch Collection
- Skyrim Skill Uncapper
- Ascension
- Stormcrown - A Shout Overhaul
- Sorcerer - A Staff and Scroll Overhaul
- Vulcano
- Arclight
- Desecration
- Lunaris
- Stellaris
- Necrom
- Natura
- Bloodmoon
- Abyss
- Arcane
- Dealing with Backstories - Keep Items
- Skyrim on Skooma
- Remote Interactions
- Immersive Spell Learning - DESTified (Implement https://github.com/zediious/tpfz-sprinkles/issues/61)
- Legendary Skill Bonus
- Fast Travel Cost
- Sets of Skills - Custom Skill Framework Conversion
- Alternate Perspective - Voiced Addon
- Start in Bruma (an addon for Alternate Perspective)
- Interesting NPCs and WACCF Outfits Patch
- Lawless Bruma - A Bandit Overhaul for Beyond Skyrim Bruma
- Thanedom of Dumbarhold
- New Vominheim
- SIRENROOT - Deluge of Deceit
- Calling the Watchmaker - Lovecraftian Inspired Quest
- Old Blood
- More Thalmor Dossiers - Bruma Addon
- Khajiit Will Follow - Vigilant Addon
- Missives - Notes Retexture
- Sacred Relic Sword
- Winged Hussar Armor and Weapons
- Barsaebic Ayleid Armor
- Rormasu Armor
- Argonia Armors Integrated
- Nordic Steel Helmet
- Valermos + Dagger
- Blade of Chaos
- Dwemer Tonal Weaponry
- The Regal Rapier and Dainty Dirk
- Sting Spear
- Yol'Kreh - The Infernal Scythe
- Redguard Assassin Armor
- Daedric Armor
- Daedric Armor - Xtudo Fixes
- Traveling Mage HDT-SMP Armor
- Adventurer HDT-SMP Armor
- Maormer Seascale Set
- Maormer Seascale Set - Xtudo Fixes
- Yorukaze Katana
- Hisuteri Katana
- Lurker Thrusts Sword
- Maliketh's Black Blade
- The Loner's Sword
- Aegean Sentinel Halberd
- Helegel Straight Sword
- Scythe of the Crow Mother
- Horse-Slaying Saber
- Beirand's Specials
- FranklinZunge Collection - Common Clothes CBBE Refit
- More Hircinic Aspects of Hircine - Mihail's Shards of Immersion + Xtudo Fixes
- Mihail Monsters and Animals - Crows and Ravens + Xtudo Fixes
- Mihail Monsters and Animals - Deadlands Xivilais + Xtudo Fixes
- Mihail Monsters and Animals - Doomsday of Blades + Xtudo Fixes
- Mihail Monsters and Animals - Pitroamers + Xtudo Fixes
- Mihail Monsters and Animals - Vampire Falmer Overhaul + Xtudo Fixes
- Mihail Monsters and Animals - Watchers + Xtudo Fixes
- Mihail Monsters and Animals - Storm Golem
- Mihail Monsters and Animals - Falmeri Frost Mount + Xtudo Fixes
- Mihail Monsters and Animals - High Clannfears + Xtudo Fixes
- Mihail NPCs and Followers - Sinding's Werewolf Voice Overhaul
- Madmen - A Forsworn Overhaul
- Failed Pickpocket Gains XP Redux
- The Eloquent Reader
- MCO Universal Support
- Instantly Skip Dialogue NG
- Barter Limit Fix
- Enhanced Invisibility
- PhotoMode
- Configurable Notification Messages
- Acoustic Space Improvement Fixes
- Reverb Interior Sounds Expansion
- Open Animation Replacer (OAR)
- Open Animation Replacer - IED Conditions
- Paired Animation Improvements
- Behavior Data Injector
- Dynamic Animation Casting - NG
- iFrame Generator RE
- Vanargand Animations II - Female Idle Walk And Run
- Vanargand Animations II - Male Idle Walk And Run
- Vanargand Animations II - Sprint
- EVG Animated Traversal - Stamina Cost Addon
- Weapon Styles - Draw Sheathe Animations for IED
- Cancel Attack
- MCO Block Recovery
- Nordic Animation Complete Pack (Only for Battleaxe Animations)
- ADXP I MCO ER rapiers (SCAR)
- ADXP I MCO ER Katana (SCAR)
- Leviathan Animations II - Greatsword Sneak Locomotion And Attacks
- Organic Player Animations
- Conditional Expressions Extended
- Immersive Interactions for Quick Loot
- Press E to Heal Followers
- Project ja-Kha'jay - Khajiit Will Follow Addon
- Rogue's Gallery
- Sound Record Distributor
- Dynamic Activation Key
- Sonders Keyword Distribution Resources
- ZedPatch3
- City Navmesh Patches
- DynDOLOD Output - Low
- DynDOLOD Output - Medium
- Occlusion Output
- Sunhelm MCM Recorder (Implement https://github.com/zediious/tpfz-sprinkles/issues/70)
- Hearthfire Extended - Cook Script Fix
- Molag Bal's Inferno - Strange Man Fix
- Obscure's College of Winterhold - Script Fix
- Flat Landscape Noise

### Updated

- DynDOLOD 3 - Alpha120 > Alpha140
- FallrimTools - 6.0.612 > 6.0.636
- BodySlide and Outfit Studio - 5.6 > 5.6.3
- Vanilla Scripting Enhancements - 2.0 > 3.0
- powerofthree's Tweaks - 1.8 > 1.8.1
- Skyrim Landscape and Water Fixes - 7.7 > 8.2
- dunFolgunthurBossBattle Script Fix - 1.2 > 1.2.1
- DLC2TribalWerebearScript Fix - 1.0.1 > 1.0.2
- Soul Cairn Script Tweaks - 1.0.1 > 1.0.2
- Word Wall Transparency Fix for ENB - 0.2 > 0.3
- Particle Patch for ENB - 1.2.3 > 1.2.6
- MCM Helper - 1.3 > 1.4
- Assorted Mesh Fixes - 0.79 > 0.90
- Keyboard Shortcuts Fix - 1.0.0.2 > 1.0.0.4
- Compass Navigation Overhaul - 2.1 > 2.1.1
- TrueHUD - HUD Additions - 1.1.7 > 1.1.8
- Casting Bar - 2.1.1 > 2.1.4
- DynDOLOD Resources - Alpha32 - Alpha42
- Skyland - Dragonborn - 1.0 > 1.1
- Ruins Clutter Improved - 3.1 > 3.2c
- Ruins Clutter Improved - 1.1 > 1.2
- Static Mesh Improvement Mod - Quality Addon - 1.3 > 1.4
- High Poly Project - 4.9.5 > 5.3
- Cathedral Weather and Seasons - 2.23beta > 2.40
- Relighting Skyrim - 1.2 > 2.1.0
- Soft Shadows - 1.0 > 2.0
- Dynamic Impact - Slash Effects - 0.5alpha > 1.1
- Dirt and Blood - Dynamic Visual Effects - 2.24 > 2.30
- Inferno - Fire Effects Redux - 4.1 > 5.1
- Better Dynamic Snow - 3.5 > 3.6
- Enhanced Vanilla Trees - 2.1.1 > 2.2.2
- 3D Junipers - Trees and Berries - 0.1 > 0.2
- Relighting Skyrim - 2.1 > 2.2
- Majestic Mountains - 4.0 > 4.2
- Snowy Surfaces Sound Collision and Aesthetics 1.6.4 > 1.6.5
- Spooknik's Tundra Trees - 1.0 > 1.2
- Unique Markarth Doors - Base Object Swapper - 0.2.4 > 0.4
- Better Windhelm Ground Meshes - 1.3.4 > 1.3.5
- Thanedom Assets - 1.3 > 1.3.1
- Skyland - Whiterun - 2.1 > 2.2
- Skyland - Solitude - 1.6 > 1.8
- Skyland - Winterhold - 1.5 > 1.6
- The Halls of the Greybeards - 1.0 > 1.1
- Iconic Statues - 1.2 4K > 1.2.3 2K
- Dwemer Pipework Reworked - 4.0 > 5.0/5.1 Hotfix
- Zim's Immersive Artifacts - 1.6.2 > 1.7.4
- Unique Uniques SE Re-Ported - 2.3.1 > 2.3.3
- JS Unique Utopia SE - Daggers - 1.0 > 1.2
- Praedy's Staves AIO - 1.2 > 1.3
- Sleek Wolf Armor - Replacer - 1.3 > 1.3.1
- Particle Lights for ENB - Stalhrim Deposits and Ore - 1.1 > 1.3
- OBody NG - 3.0 > 4.2
- Forgotten Argonian Roots - Unknown Version > 2.0
- Mysticism - A Magic Overhaul - 2.2.3 > 2.3.3
- Adamant - A Perk Overhaul - 5.7.6 > 5.8.4
- Hand to Hand - An Adamant Addon - 1.4.6 > 1.5.6
- Take a Peek - New Stealth Mechanic - 1.15 > 1.22
- Aetherius - A Race Overhaul - 2.10.4 > 2.11.8
- Mundus - A Standing Stone Overhaul - 1.9.1 > 1.11.0
- Molag's Will - Vampire Perk Tree - 1.1 > 2.4.0
- Dynamic Things Alternative - 0.2 > 0.2.2
- Armor and Clothing Extension - 1.2 > 1.5.1
- Security Overhaul - Add-ons - 0.1.6 > 0.1.8
- Trade and Barter - 2.0 > 2.1
- Oblivionesque Locks - 2.0 > 2.1
- Apothecary - An Alchemy Overhaul - 1.3.4 > 1.3.5
- Thaumaturgy - An Enchanting Overhaul - 1.3.2 > 1.3.3
- AI Overhaul - 1.8.3 > 1.8.4
- Nether's Follower Framework - 2.8.3beta - 2.8.5
- Immersive Rejections - 1.1 > 1.11
- Guard Dialogue Overhaul - 2.17 > 2.18
- Civil War Lines Expansion - 1.06 > 1.08
- Bandit Lines Expansion - 1.07 > 1.08
- Misc Dialogue Edits - 1.8.5 > 1.9.2
- More Dialogue Options - 1.4 > 1.5
- Hunters Not Bandits - 4.0 > 4.1
- College of Winterhold - Quest Expansion - 1.12 > 1.14
- Nilheim - Misc Quest Expansion - 1.11 > 1.12
- House of Horrors - Quest Expansion - 1.10 > 1.12
- The Only Cure - Quest Expansion - 1.01 > 1.02
- Headhunter - Bounties Redone - 1.43 > 1.50
- More Thalmor Dossiers - 1.11 > 1.12b
- Destination Weddings - 1.4.1 > 1.5 (fix https://github.com/zediious/tpfz-sprinkles/issues/72)
- Riften Docks Overhaul - 2.5.3 > 2.5.5
- Skyrim Sewers - Radiant Quests Enabled - 1.0 > 1.1
- Halted Stream Mine - 1.3.2 > 1.4
- Ryn's Goldenglow Estate - 1.0 > 1.6
- Ryn's Karthspire - 1.5 > 1.6
- Environs - Riften Warehouse - 1.0 > 2.0
- Environs - The Greenwood Shack - 2.04 > 3.0
- Stendarr Rising - The Hall of the Vigilant Rebuild - 1.3 > 1.6
- Markarth Outskirts - 1.5 > 1.6
- Simple Player Home Improvements - 2.2 > 2.3
- JK's Dragonsreach - 1.1.1 > 1.1.2
- JK's The Winking Skeever - 1.4 > 1.5
- JK's Arnleif and Sons Trading Company - 1.0 > 1.0.1
- JK's Warmaiden's - 1.2 > 1.3
- JK's Windhelm Outskirts - 1.1 > 1.1.1
- JK's Windhelm Outskirts Patch Collection - 1.1 > 1.2
- JK's Interiors Patch Collection - 5.16 > 5.18.1
- Custom Skills - VIGILANT - 2.0 > 2.0.a
- Alternate Perspective - 3.0.3 > 3.0.6
- Skyrim's Got Talent - Improve As a Bard - 1.61 > 1.63
- Interesting NPCs - 4.5 > 4.54
- Interesting Follower Requirements for Interesting NPCs - 2.01 > 2.02
- Interesting NPCs Script Optimisation - 1.3.1 > 2.0
- Beyond Skyrim - Bruma - 1.6.1 > 1.6.3
- The Wheels of Lull - 5.1.9 > 5.1.12
- Depths of the Reach - 1.8 > 1.82
- Ships and boats of Tamriel - 1.1 > 1.2
- VIGILANT - 1.7.2 > 1.7.3
- VIGILANT - English - 1.7.2 > 1.7.3
- GLENMORIL - 0.95 > 0.95.50
- GLENMORIL - English - 0.95 > 0.95.50
- UNSLAAD - 2.6.3 > 3.0.2
- UNSLAAD - English Voiced - 2.6.3 > 3.0.2
- Beyond Reach - Tweaks and Enhancements - 2.6alpha > 2.6c
- Khajiit Will Follow - 4.6.5 > 4.7.1
- Quest - Baba Yaga and the Labyrinth - 0.3.1 > 0.3.2
- Fortune's Tradehouse - 1.1 > 2.0
- Skybound Underhang Camp - 4.0 > 5.0
- Sidequests of Skyrim - 0.8 > 0.8.2
- Mihail Monsters and Animals - Ettins - 1.1 > 2.0
- Silver Elven Armor - 1.0 > 2
- Animated Armory - Non-DAR-2.3.9 > DAR-2.3
- Simple Weapon Swing Parry - 1.0.2 > 1.0.4-
- Dual Wield Parrying SKSE - 1.5 > 1.7
- Arena - An Encounter Zone Overhaul - 1.1 > 1.2
- Dragon War - A Dragon Overhaul - 3.0.4 > 3.0.6
- Lawless - A Bandit Overhaul - 1.7 > 2.0
- Delphine's Map Reveals Dragon Mounds - 1.1 > 1.2
- Simply Order Summons - 0.11 > 0.12
- Tamrielic Names - 1.0 > 1.1
- Reachmen Tribes Names - 1.1 > 1.2
- Ashlander Nomads Names - 1.0 > 1.1
- Dovah Names - 1.0 > 1.1
- More Lights for ENB - Blood Splatter Fix - 0.3 > 0.4
- Faster HDT-SMP - 1.50.7 > 2.0.2
- Swiftly Order Squad - 1.7 > 
- Classic Paralysis - 3.1 > 3.3.1
- Enhanced Reanimation - 1.5 > 1.5.1
- Essential Favorites - 2.2 > 2.3
- Remember Lockpick Angle - Updated - 2.0 > 4.2
- Vampires Cast No Shadow 2 - 1.1.1 > 1.2.1
- Magic Sneak Attacks - 1.1 > 1.2
- ConsolePlusPlus - 1.2 > 1.3
- Audio Overhaul for Skyrim - 3.3.2 > 4.1.3
- Forceful Tongue - Audio Overhaul for Skyrim Patch - 1.0 > 1.0.2
- Immersive Sounds - Compendium - 2.2 > 3.0
- Audio Overhaul - Immersive Sounds Integration - 1.0.1 > 1.1.0
- Maximum Carnage Skeletons - 1.0 > 1.4
- Payload Interpreter 1.0.1 > 1.1.0
- Immersive World Encounters - 3.3 > 3.6.1
- TrueHUD - HUD Additions Boss Ini Tweaks - 1.3 > 1.4
- XP32 Maximum Skeleton Special Extended - 4.81 > 5.04
- Immersive Equipment Displays - 1.6.3 > 1.7.3
- True Directional Movement - 2.2.3 > 2.2.4
- Conditional Armor Type Animations - 1.1 > 1.3c
- Vanargand Animations - Male Idle Walk and Run - 1.3.1 > 1.3.1c
- Vanargand Animations - Sprint - 1.3 > 1.3c
- Leviathan Animations II - Male Idle Walk And Run - 2.3 > 2.3c
- Vanargand Animations - Sprint - 1.3 > 1.3c
- Leviathan Animations II - Female Idle Walk And Run - 2.3 > 2.3c
- Leviathan Animations II - Sprint - 2.4 > 2.4c
- Goetia Animations - Male Idle Walk And Run - 1.2 > 1.3c
- Goetia Animations - Female Idle Walk And Run - 1.2 > 1.3c
- Goetia Animations - Sprint - 1.0 > 1.0c
- EVG Animated Traversal - 1.0beta > 1.02
- ADXP I MCO elden rim moveset collection - 1.0 > 1.1
- ADXP I MCO ER Spear Basic Animation - 1.0 > 1.1
- Dodge - MCO|DXP - 0.9.6 > 2.1.19
- Vanargand Sneak Archery Animations - 1.3 > 1.4
- Use Those Blankets - 2.1 > 2.11
- Look Around - Searching Animations For NPCs - 1.0 > 1.1
- Modern Female Sitting Animations Overhaul - 1.4 > 1.6
- NPC Animation Remix - 1.4 > 1.6.2
- Immersive folded hands 1.4 > 1.5.0
- Conditional tavern cheering - 1.0.3 > 1.1
- Conditional Expressions Extended - 1.4.2 > 1.4.5
- Immersive Interactions - Animated Actions - 1.67 > 1.73
- Take a Seat - New Sitting Animations - 1.0 > 1.01
- Sharpen Other Swords II - AnimObject Swapper - 0.2.2 > 0.2.3
- Flute Animation Fix - 1.0 > 1.1
- Project ja-Kha'jay- Khajiit NPC Diversity Overhaul - 3.0 > 4.0.5+hotfix
- Project ja-Kha'jay- Interesting NPCs Khajiit Addon - 2.2 > 3.0.4
- powerofthree's Papyrus Extender - 5.5 > 5.6.1
- Base Object Swapper - 2.5.1 > 2.6.1
- Spell Perk Item Distributor - 6.6.1 > 6.6.2
- Keyword Item Distributor - 3.0.2 > 3.0.4
- NPCs Names Distributor - 1.1.1 > 2.4.0
- Custom Skills Framework - 1.0 > 2.0.2
- xLODGen Resource - SSE Terrain Tamriel - 1.0 > 2.0
- Leveled List Additions (Armors) - 0.9.4 > 0.9.5
- Leveled ListAdditions (Weapons) - 0.9.4 > 0.9.5
- MonsterPatch - 0.9.4 > 0.9.5
- ZedPatch 1 - 0.9.4.1 > 0.9.5
- ZedPatch 2 - 0.9.4.1 > 0.9.5
- Synthesis Output - 0.9.4 > 0.9.5
- Terrain LOD Output - 0.9.3.1 > 0.9.5
- TexGen Output - 0.9.3.1 > 0.9.5
- DynDOLOD Output > Renamed DynDOLOD Output - High
- Nemesis Output 0.9.4 > 0.9.5
- BodySlide Output - 0.9.3.1 > 0.9.5
- Overwrite Misc - 0.9.4 > 0.9.5

### Fixes

- Fixed CTD during Housecarl/Prisoner encounters from Immersive Encounters by updating the mod. (https://github.com/zediious/tpfz-sprinkles/issues/74)
- Corrected Better SkyUI Config not being incorporated into Paper UI config (fix https://github.com/zediious/tpfz-sprinkles/issues/71)
- Corrected position of SunHelm widgets when using them via MCM Recorder preset (fix https://github.com/zediious/tpfz-sprinkles/issues/70)
- Implemented fix for read books/notes not sorting correctly and causing issues reading the right item (Fix https://github.com/zediious/tpfz-sprinkles/issues/48)
- Disabled barrel that was blocking the stairs in Half Moon Mill Inn
- Corrected unbalanced damage values and crafting recipes for RFM. All RFM weapon damages and crafting requirements/materials are now in-line with the tier the weapon is placed in.
- Added required items and conditions to many RFM COBJ's that were missing them.
- Corrected unbalanced damage and armor values on a few equipment pieces.
- Corrected wrong recipe conditions, and added missing recipes for Draugr Weaponry Standalone
- Expanding on the above, you can loot Dwarven/Elven/Glass-damage weapons from Draugr. These weapons can't be tempered without the respective crafting perk, to balance finding these weapons in Draugr crypts.
- Balanced damage values and COBJ records for weapons added by Mihail's creature mods that were missed.
- Rebalanced Viridian set to be between Orcish and Ebony when wearing cuirass and custom greaves
- Corrected broken texture atlas on Adept mage robe/embroidered mage robe enchanted variants and unenchanted version.
- Corrected wrong comparison value for a variety of COBJ conditions
- Assigned the correct keywords to equipment that either had the wrong keywords or were missing them.
- Added VendorItem keywords to various equipment pieces that did not have them, preventing them from being sold to Blacksmiths.
- Disabled duplicate road signs at border gate to Cyrodiil
- Fixed Triple Triad in Skyrim being broken in some cases by making Container, Gift and MessageBox menus paused.
- Fixed temporary stat reset bug by making the Skill Menu paused.
- Fix the duplicate Greenwood Shack map marker (again) and make sure burnt corpses and other signs of dragon are disabled until "it" happens.
- Corrected various landscape color seams in the world by ensuring vertex color values are consistent between cells.
- Corrected landscape conflicts in Markarth Outskirts
- Corrected deleted references
- Re-added and patched radiantBlocker.esp for Lawbringer, to prevent radiant quests sending to claimed locations.
- Fix Cook "servant" from Hearthfire Extended never having food.
- Fixed Sugarclaw from being inside the wall after you leave Mistwatch, due to a scripted lean marker being left in the wall by moving it outside.
- Fixed navmesh around JK's Drunken Huntsman and the bakery added by Capital Whiterun Expansion
- Fix navmesh in Proudspire Manor, and relocated sewer trapdoor
- Fix navmesh in Jorrvaskr basement, and re-arranged the furniture around the sewer trapdoor.
- Fix Bloodskaal blade and certain VIGILANT weapon attack "arts" not triggering.
- Fixed Unenchanted Staves from having double meshes
- Fixed a few mod-added staves that were using unenchanted staff meshes
- Fix Jenassa from not being hireable
- Corrected custom "Adelvar Wind-Ruler" NPC at Robber's Gorge
- Disabled duplicate set of Mythic Dawn armor at Mehrune's Shrine, and moved the remaining set to a proper location.
- Disabled Venom Spitters in Bthardamz Arcanex that would often attack and make Orchendor submit before player reaches him.
- Make Ancient Daedric Gate map marker not visible on new game.
- Moved the Ice Titan near Ancient Daedric Gate, to prevent it from getting stuck. Also prevent it from attacking the nearby NPC via Faction.
- Fix Strange Man from following you randomly. This has the side-effect of making a certain part of a certain quest a little less creepy.
- Fix incorrect map markers on compass due to Compass Navigation/CoMAP incompatibility by removing latter mod until the former makes a fix.
- Fixed Chief Mauhulakh from not being a Hand to Hand trainer as they should be
- Corrected wrong ownership for a variety of crops and containers in the world
- Moved the Ferryman in Dawnstar to near the northern wall, and disabled clipping dock.
- Moved idle marker at Dawnstar smithy from inside the smithing table
- Moved book from Grand Paladin in Arcaneum from the floor to a table
- Moved book from Konahrik's Accoutrements in Arcaneum from the floor to a table
- Moved the podium/book for Artifacts of Boethia from the odd location in Arcaneum to exclusive book section on second floor
- Corrected Verolevi's Sneak idles from not applying when Trespasser perk is acquired
- Fixed Halberd/Pikes and Quarterstaves from using vanilla weapon idles rather than their own.
- Fix CTD when spamming SHIFT while looking at items due to incompatibility between BTPS and Use or Take/Read or Take by removing the latter two mods.
- Fixed missing meshes for two Animated Armory whips.
- Corrected missing rock underside LODS for Solitude Skyway
- Fixed purple LOD meshes on some Aspen's Ablaze trees in The Rift.
- Corrected infinite loading screen at Windhelm's east gate by adding fix to remove a broken vanilla knife from an NPC's inventory.
- Disabled two small floating objects at world center

### Tweaks

- Previously, both Battleaxes and Warhammers shared the same animation. This made it almost senseless to use Battleaxes.
  - Switched the animation used by Warhammers to the proper animation from "elden rim moveset collection". This is a slower animation
  - Switched the animation used by Battleaxes to the Nordic Animation Pack battleaxe anim. This is slightly faster.
- Removed all whips from leveled lists, and disabled crafting recipes due to Whips not behaving correctly with MCO.
- Verolevi's Weapon Sneak Idle/Attack animations now require the Trespasser perk, alongside the sheathed idles.
- Reduced the amount of Security XP gained overall, and reduced the influence it has on your character level.
- Raised the influence that your Hand-to-Hand skill has on your character level
- Dramatically increased the cost of commissioning equipment/enchantments with Honed Metal.
- Removed some out of place RFM weapons from certain lists.
- Dremora enemies will now use different Daedric armor sets instead of only the Vanilla set.
- Made undiscovered locations visible on compass by default.
- Switched TDM Lock-On Key to Mouse-Button-5 by default, instead of U.
- Removed a few very OP spells from Miraak, and reduced his stats and perks.
- Reduced the amount of Tundra Raiders in Whiterun Thane quest.
- Enlarged the four outer pillars in the Labyrinthian Dragon room, and reduced the Dragon's health slightly.
- Mirmulnir's level will now scale with the player, and has had his health reduced overall.
- Make Mythic Dawn armor type conversion recipes only appear if you have the requisite items in your inventory.
- Made certain SkyTEST prey animals no longer aggro.
- Disabled weapon rack error message from Immersive Display Overhaul.
- Default Smoothcam Preset is now centered when not using ranged/magic.
- Increased LOD render blocks by roughly 50k each, and brought Tree LOD to the same level as the maximum LOD distance.
- Disable Borderless Windowed Mode (still very seamless without)
- Decreased brightness to 50%. This only applies without ENB.

## v0.9.4.1 - **5/22/2023**

This version introduces SunHelm and Campfire as optional mods, for those that want enhanced Survival gameplay.

It also chiefly fixes a navmesh CTD near Shor's Stone. That's the main reason this release is coming without much more content additions or removals.

Also a good number of other fixes here! Thank you everyone in Discord for reporting bugs :)

If playing on an existing save, in order for MCM changes/fixes to apply, you need to go to the MCM Recorder MCM menu, and re-run the TPF - Zediious Sprinkles preset.

### Removed

- Hvergelmir Brows for High Poly Head
- zxlice's Backstab and Parry

### Added

- SunHelm Survival (disabled by default) (implement https://github.com/zediious/tpfz-sprinkles/issues/67)
- Campfire - Complete Camping System (disabled by default)
- Survival Mode Patches - Campfire (disabled by default)
- ZedPatch - Survival Mode (disabled by default)

### Updated

- Assorted Mesh Fixes - 0.78 > 0.79
- Fancy Sleeping Tree Replacer - 1.5 > 1.6
- Caught Red Handed - Quest Expansion  - 1.02 > 1.04
- Paarthurnax - Quest Expansion - 1.11 > 1.12
- Destination Weddings - 1.4 > 1.4.1
- Riften Docks Overhaul - 2.5.2 > 2.5.3
- Interesting NPCs Script Optimisation - 1.3 > 1.3.1
- Interesting NPCs Follower Requirements - 2.0 > 2.01
- Sidequests of Skyrim - 0.7.1 > 0.8
- Viridian Knight Armor - 3.4 > 5.0
- Dual Wield PArrying SKSE - 1.4 > 1.4
- Dragon War - 3.0.2 > 3.0.4
- Universal Cured Serana Eye Fix - 0.1 > 0.4
- Oxygen Meter - 1.1 > 1.3
- EVG Conditional Idles Extended - 1.2 > 1.3
- Gesture Animation Remix - 1.9.9 > 2.0
- Use Those Blankets - 2.0 > 2.1
- ZedPatch 1 - 0.9.4 > 0.9.4.1
- ZedPatch 2 - 0.9.4 > 0.9.4.1
- Overwrite Misc - 0.9.4 > 0.9.4.1
- Nemesis Output - 0.9.4 > 0.9.4.1

### Fixes

- Fixed Alduin staying landed during intro sometimes (fix https://github.com/zediious/tpfz-sprinkles/issues/66)
- Disabled Creature killmoves in Violens MCM to prevent invincibility (fix https://github.com/zediious/tpfz-sprinkles/issues/68)
- Fixed navmesh crash near Shor's Stone due to bad conflict resolution (fix https://github.com/zediious/tpfz-sprinkles/issues/69)
- Fixed Oxygen Meter not appearing by changing TrueHUD MCM, under "Player Widget", disabled "Display Enchantment Charge Meter". (fix part of https://github.com/zediious/tpfz-sprinkles/issues/63)
- Removed duplicate Lockpick recipe (fix part of https://github.com/zediious/tpfz-sprinkles/issues/63)
- Fixed duplicate cross hair when using magic and weapon (fix part of https://github.com/zediious/tpfz-sprinkles/issues/63)
- Fixed duplicate stat bars in Dark Mode UI

### Tweaks

- Reduced volume/gain of "Equus - Horses Sounds Redesigned" 

## v0.9.4 - **5/6/2023**

Uh oh, scary version number change! With this version, I have fixed a number of incorrect quest records and other things, and a good number of those things that will not apply on a new save. As such, I have labeled the version as not save-safe. For the most part, this will just cause broken things to stay broken. As such, I **highly recommend** you play with a new save on this version, but you may find luck with an existing save. Always make a backup of your saves before playing on new versions! Seriously! If you do play on an existing save, make sure that you dismiss all your followers before loading into it after updating!

With this version, we've introduced Dear Diary - Dark Mode as an optional interface replacer. You can disable the Dear Diary - Paper UI mod and it's related mods, and enable the Dark Mode version and it's related mods. Check the wiki/read the Notes for these mods for a guide!

Character Creation has also been fixed up in a few ways. The High Poly Head head parts will now be the default in character creation, and clipping beards have been disabled, so that you can only see the suitable High Poly Head versions. The High Poly Head hair meshes have also been added, they were left out by mistake. I've also added required dependencies for many of the RaceMenu presets in the list that were missed, fixing purple body meshes on these presets.

There are new mods, some from suggestions! The Idle Animations WheelMenu keybind has been set to " ] } ". More mods from suggestions will be added in the next version.

Also included are a very large number of fixes for combat/equipment balance, including changes to damage/crit, armor value, weight, value, keywords, crafting recipes and other miscellaneous things.

A lot of the fixes in this version were from those in the discord server, playing the list/checking my patches and giving feedback. You know who you are, thank you SO much!

### Removed

- Alternate Perspective - LRS Hunter Start (fix https://github.com/zediious/tpfz-sprinkles/issues/51)
- Alternate Perspective - Miner
- s6o6t LORE - Oblivion gates
- Emeri's High Poly Presets
- REALORE Preset Series - Bosmer
- Rika Nyr - Breton Preset
- Jasahri Nyr - High Poly Preset
- Fluffy FrostGiant
- Dragon War Patches (integrated into original mod)
- DCR - King Crusader Heavy War Regalia
- Simple Optional Shortcuts
- Send Off Somewhere
- Choose Your Own Arch-Mage
- Improved College Entry
- Most Plugins from Misc College of Winterhold Tweaks
- Scrambled Bugs - Soul Gem Too Small

### Added

- Dear Diary Dark Mode (implement https://github.com/zediious/tpfz-sprinkles/issues/41)
  - Paper Skin for Compass Navigation Overhaul (Dark Mode)
- Added to fix https://github.com/zediious/tpfz-sprinkles/issues/53
  - Fair Skin Complexion - Makeup Overhaul
  - Xara's Makeup and Warpaints
  - Female Makeup Suite
  - Freckle Mania
  - Weathered Nordic Bodypaints
  - Battle Hardened Warpaints
  - RaceMenu Overlay Compilation
  - Dragon Age Dalish Face Tatoos
  - Community Overlays 1 / 2 / 3
  - Skin Feature Overlays
- Hvergelmir Brows for High Poly Head
- Environs - The Greenwood Shack Alternate Perspective New Beginnings Patch
- Enhanced WheelMenu Control
- Idle Animations WheelMenu (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Simple Straw Hats (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Ave's Silver Sapphire Ring for Bruma (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Ave's Jade Sapphire Ring for Bruma (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Ave's Jade Ring for Bruma (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Last Vigil - Ebony Warrior Voice Rework (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Equus - Horse Sounds Redesigned (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Eviscerate - Weapon Sounds Reworked (implement https://github.com/zediious/tpfz-sprinkles/issues/54)
- Kalilies NPCs - Keep Your Skin
- Praedy's Staves Patches
- Hearthfires Extended and Creation Club Fishing Patch
- GIST - Genuinely Intelligent Soul Trap
- GIST - ESL Script
- For Honor in SKYRIM I Aramusha Dual Katana Moveset
- Synthesis Output

### Updated

- Casting Bar - 2.0 > 2.1.1
- Snowy Surfaces Sound Collision and Aesthetics 1.6.2 > 1.6.4
- Better Chests - 1.1.3 > 1.1.4
- Caught Red Handed - Quest Expansion - 1.01 > 1.02
- Hand to Hand - 1.4.4 > 1.4.6
- Immersive Display Overhaul - 1.2 > 1.3
- At Your Own Pace - College of Winterhold - 2.0 > 2.1
- Apothecary - 1.3.2 > 1.3.4
- Thaumaturgy - 1.2.1 > 1.3.2
- Dragon War - A Dragon Overhaul - 2.1.8 > 3.0.2
- Infinite Dragon Variants - 1.1.1 > 2.0.1
- Lawless + Simonrim Addon - 1.1.1 > 1.7
- Lawless Patches - 1.2 > 1.6
- Xtudo Dark Knight Set - 4.2 > 5
- Simply Order Summons - 0.8 > 0.11
- Swiftly Order Squad - 1.6.6 > 1.7
- For Honor Power Attack - 1.4 > 1.5
- Precision Creatures - 2.1 > 2.3
- Spell Perk Item Distributor - 6.5.2 > 6.6.1
- LeveledListAdditionArmor - 0.9.3.1 > 0.9.4
- LeveledListAdditionWeapon - 0.9.3.5 > 0.9.4
- MonsterPatch - 0.9.3 > 0.9.4
- ZedPatch 1 - 0.9.3.5 > 0.9.4
- ZedPatch 2 - 0.9.3.3 > 0.9.4
- Nemesis Output - 0.9.3.3 > 0.9.4
- BodySlide Output - 0.9.3.1 > 0.9.4
- DynDOLOD Output - 0.9.3.1 > 0.9.4
- Overwrite Misc - 0.9.3.4 > 0.9.4

### Fixes

- Fixed wolf/fox from T-posing and/or being invincible in certain situations (fix https://github.com/zediious/tpfz-sprinkles/issues/4)
- Fixed many RaceMenu presets from having purple body meshes (fix https://github.com/zediious/tpfz-sprinkles/issues/53)
- Fixed clipping of beards and hairs by using correct meshes (fix https://github.com/zediious/tpfz-sprinkles/issues/52)
- Fixed certain bounty quests from being in-completeable (fix https://github.com/zediious/tpfz-sprinkles/issues/56)
- Removed incorrect/useless command from Autorun configuration
- Fixed incorrect conflict resolution for House of Horrors Expansion mod, preventing broken dialogue with Vigilant Tyranus.
- Fixed being unable to talk to Eola in The Taste of Death
- Fixed being unable to talk to Tolfdir after First Lessons
- Fixed purple mesh on male Crimson Dark Knight set.
- Removed custom body texture from Kalilies NPCS/rebuilt facegen to prevent possible nipple exposure and neck seams
- Removed duplicate map marker at Greenwood Shack
- Fixed duplicate staff meshes in hand
- Corrected a great number of conflict resolution issues in ZedPatch, ZedPatch2, and MonsterPatch, fixing quests, dialogue and a few other things that were not working properly.

### Tweaks

- Switched from "Attack - MCO" to "Attack - DXP". This means that all combat animations will follow the exact speed that the animator intended. Attack speeds will no longer be affected by perks, weapon speed, or anything else. Work will be done to change perks that increase weapon speed into something that can be useful.
- Placed faster unarmed moveset with more combo potential behind the first tier of the "Momentum" perk from the Hand to Hand tree, and raised unarmed damage from -50% to -20%
- Raised damage of all katana/dai-katana/nodachi by 2
- Lowered damage of all rapiers/pikes/spears/halberds by 3
- High Poly Head face part will now be the default face part on character creation. The vanilla face part and select hairs/beards have been disabled. There are still a few hairs from other mods that clip on certain races. (fix https://github.com/zediious/tpfz-sprinkles/issues/52)
- Modified  One-hand Katana Animations to also work if you have a Spell or torch in your off hand, not just fists or shield.
- Lots of consistency tweaks for added weapons and armor, to make their damage/crit, weight, value, keywords, and crafting recipes balanced and proper.

## v0.9.3.5 - **4/24/2023**

This version simply removes a weapon mod from the list that has been placed under moderation review. This weapon was previously in the Glass Battleaxe leveled lists. This is save safe, the weapon will simply disappear from your saves if it existed.

### Removed

- Cosmo - Spear Fantasy

### Updated

- ZedPatch 1 - 0.9.3.4 > 0.9.3.5
- LeveledListAdditionsWeapons - 0.9.3.1 > 0.9.3.5

## v0.9.3.4 - **4/20/2023**

This version brings a re-balance of the combat and each difficulty. Using Simply Balanced, I've tweaked base damage values for the player and NPCs to be a *bit* more tanky on Adept. Further, difficulty modifiers have been changed. As you reduce your difficulty, enemies will become very easy to kill, and you will take a little less damage. As you raise your difficulty, enemies will exponentially become more "spongy" and you will take a little more damage. The focus with this is allowing the player to make enemies more spongy, if that is the desired gameplay. The Adept difficulty is what can be considered my "signature difficulty" with this list, and is what I would recommend playing with.

I've also fixed an embarrassingly large amount of borked weapon keywords and DAR conditions for said keywords. A variety of weapons that were not using the correct animations will now do so.

MCM settings for Wildcat have been modified, as well as the newly added Simply Balanced

### Removed

- WO3E - AA Patch

### Added 

- Simply Balanced
- Immersive Dawnguard Dayspring Pass Bruma Patch
- Nemesis Creature Behavior Compatibility Werewolf Addon

### Updated

- Casting Bar - 1.0.1 > 2.0.0
- Dynamic Impact - Slash Effects - 0.2alpha > 0.5alpha
- Spellsiphon - 5.26 > 5.27
- Dealing with Backstories - 2.2 > 2.3
- Immersive Rejections - 1.0 > 1.1
- Serana Relationship Revamped - 1.3 > 1.3.1
- The Wheels of Lull - 5.1.8 > 5.1.9
- Penitus Oculatus - 0.17 > 0.18.2
- Dual Wield Parrying SKSE - 1.3 > 1.4
- Faster HDT-SMP - 1.49.3 > 1.50.7
- Nemesis Creature Behavior Compatibility - 1.3 > 1.4
- Precision Creatures - 2.0 > 2.1
- Comprehensive First Person Animation Overhaul - 1.0.2 > 1.0.3
- Improved Table Transition Animations - 1.1 > 1.2
- Modern Female sitting Animations - 1.3 > 1.4
- NPC Animation Remix - 1.3 > 1.4
- Immersive Folded Hands - 1.3 > 1.4
- Conditional Expressions - 1.26 > 1.27
- Spell Perk Item Distributor - 6.5.1 > 6.5.2
- Keyword Item Distributor - 2.2 > 3.0.2
- ZedPatch 1 - 0.9.3.1 > 0.9.3.4
- ZedPatch 2 - 0.9.3.1 > 0.9.3.4
- Nemesis Output - 0.9.3.1 > 0.9.3.4
- Overwrite Misc - 0.9.3.1 > 0.9.3.4

### Fixes

- Added proper keywords to many missed weapons unique in the game, for them to use proper animations (Rapier, Katana, etc)
- Actually fixed Scythe animations playing with Scythe weapons
- Fixed Spear standing power attack not being used
- Fixed dai-katana animations not playing.
- Unique Katana animations play only with Katana in right hand and fists or shield in left
- Fixed dual wield katana animations only using the right hand
- Fixed floating manhole in front of Palace of the Kings
- Fixed the need to select your Alternate Perspective start scenario twice

### Tweaks

- Modified Simple Activate configuration to display the action you will do only on items in world. (Eat, Take, etc).
- Disabled Wildcat Realistic Damage Plugin
- Via Wildcat MCM
  - Tweaked the Adept difficulty to be roughly the same as the game is now, with slightly decreased damage dealt all around. Earlier difficulties have been tweaked to decrease damage to the player, and slightly increase damage dealt to enemies. Beyond Adept, Enemies will do more damage to the player, and the player will deal exponentially less damage to enemies, making them what could be considered "damage sponges" as you move closer to Legendary.
- Via Simply Balanced MCM
  - On all difficulties, the player takes 30% more base damage and NPCs take 20% more base damage.
  - Decreased the player damage output of destruction spells by 30%
  - Decreased the player damage output of bows/crossbows by 20%
  - Decreased the player damage of unarmed combat by 50%. You can use melee attacks very quickly.
  - Decreased the damage of daggers by 25%. These weapons can attack very quickly.
  - Decreased the damage multiplier for power attacks by 10%
  - Reduces experience gained across the board by 10%

## v0.9.3.3 - **4/16/2023**

This version fixes a resurgence of the False Save Corruption bug introduced in 0.9.3.1. All previously "corrupted" saves will be retroactively fixed.

### Added

- Adjustable Attribute Consumption SKSE (Horses still consume Stamina out of combat) (implement https://github.com/zediious/tpfz-sprinkles/issues/44)

### Fixes

- Fixed False Save Corruption bug resurfacing due to increased file handle since version 0.9.3.1
- Fixed missing roads on world map since version 0.9.3.1
- Changed BTPS MCM settings to fix item tooltips in 1st person (fix https://github.com/zediious/tpfz-sprinkles/issues/42)

## v0.9.3.2 - **4/15/2023**

This version has reduced the .wabbajack file size significantly! You will need to download the new version of Base Coat if updating, which is quite large.

### Updated

- Base Coat - 1.0 > 1.1

## v0.9.3.1 - **4/15/2023**

This version should be save-safe. None of the added or removed mods should have a *major* effect on the game. A few changes simply won't apply on existing saves at all, or will require a cell reset. Removed armors will disappear from your save. Make a backup of your saves before playing!

A few new armors and weapons have been added to leveled lists, view [Added Equipment.md](https://github.com/zediious/tpfz-sprinkles/blob/main/Added%20Equipment.md) to see exact additions!

### Removed

- D-Armory (fix https://github.com/zediious/tpfz-sprinkles/issues/32)
- Hunter Archer Armor (fix https://github.com/zediious/tpfz-sprinkles/issues/21)
- No Follower Attack Collision (fix https://github.com/zediious/tpfz-sprinkles/issues/38)
- Old MCO-Elden Counter Patch
- Simple Block Sparks

### Added

- Survival Mode Control Panel (implement https://github.com/zediious/tpfz-sprinkles/issues/31)
- Ominous ENB as an optional ENB preset (implement https://github.com/zediious/tpfz-sprinkles/issues/19)
- Mfg Fix (fix https://github.com/zediious/tpfz-sprinkles/issues/26)
- QuickLoot EE (implement https://github.com/zediious/tpfz-sprinkles/issues/37)
- Better SkyUI Config (implement https://github.com/zediious/tpfz-sprinkles/issues/37)
- Cyrodiilic Thief Set Female Version + CBBE Refity (fix https://github.com/zediious/tpfz-sprinkles/issues/39)
- Skyrim Souls RE, with the following menus remaining paused (fix https://github.com/zediious/tpfz-sprinkles/issues/27)
  - Console
  - Pause/Quest Journal
  - Level up/Skill Menu
  - Map Menu
  - MCM
- Extra Vanilla Male Hair
- NordwarUA Realistic Armor (Standalone)
- Infantry Armor + Xtudo Fixes
- Raven HDT-SMP Armor + No Feathers
- Armors of the Velothi Pt II + HIMBO Refit
- Seasoned Traveller Armor + CBBE/HIMBO Refit
- Iron Legion
- Nordic Fur Armor
- Cosmo - War Scythe

### Updated

- ZedPatch 1 - 0.9.3 > 0.9.3.1
- ZedPatch 2 - 0.9.3 > 0.9.3.1
- LeveledListAdditionsArmors - 0.4007 > 0.9.3.1
- LeveledListAdditionsWeapons - 0.4007 > 0.9.3.1
- Terrain LOD Output - 0.4002 > 0.9.3.1
- TexGen Output - 0.4002 > 0.9.3.1
- DynDOLOD Output - 0.9.2 > 0.9.3.1
- BodySlide Output - 0.4006 > 0.9.3.1
- Nemesis Output - 0.9.3 > 0.9.3.1
- Overwrite Misc - 0.9.3 > 0.9.3.1

### Fixes

- Fixed texture path for Poison Rag item from Blowgun mod (fix https://github.com/zediious/tpfz-sprinkles/issues/22)
- Patched missing cart/canopy and other carriage parts in Dawnstar (fix https://github.com/zediious/tpfz-sprinkles/issues/20)
- Moved Sugarclaw from inside Mistwatch Tower Wall (fix https://github.com/zediious/tpfz-sprinkles/issues/30)
- Disabled visible lighting plane objects in Nightgate Inn (fix https://github.com/zediious/tpfz-sprinkles/issues/35)
- Removed MCM Recorder recording for Shadow of Skyrim. This must be manually enabled and configured. (fix https://github.com/zediious/tpfz-sprinkles/issues/25)
- Fixed Elden Counter not working at all due to old patch in use.
- Fixed Valhalla Timed Block not working by correctly setting compatibility option in it's MCM.
- Fixed True HUD extra meter not working correctly, as both POISE and Valhalla were trying to use it. Now only Valhalla will try to use it, and will work correctly.
- Enabled Valhalla/POISE compatibility that was disabled by mistake (not related to above)
- Fixed incorrect Scythe animation conditions. All scythe weapons will now use the unique Scythe animations.
- Fixed LOD world hole near College of Winterhold

### Tweaks

- Changed default option for NPC Names Distributor set to not be Title, due to conflict with QuickLootEE
- Increased the default LOD render blocks a bit, and increased the Terrain LOD/DynDOLOD output settings slightly. Very small performance hit. These changes can be mostly reversed in the DynDOLOD MCM.
- Made the Valhalla Combat Timed Block window slightly larger.
- Increased Dodge stamina cost from 10 to 20

## v0.9.3 - **4/8/2023**

**NOTE:** This version will have some initial issues in existing saves. Some of the modified locations that have changed persistent references in the world will not apply their changes on existing saves. Lawless will only apply some of its changes on cell reset. Play on this with an existing save at your own risk and do so WITH A BACKUP!

### Added

- Simple Activate SKSE
- Hand to Hand - An Adamant Addon
- Lawless - A Bandit Overhaul
- DLC2TribalWerebearScript Fix
- Falmer Sounds - the Betrayal Legacy Edition
- Mihail Monsters and Animals - Vigilants + Xtudo Fixes
- Mihail Monsters and Animals - Ogrim
- Mihail Shards of Immersion - Flies around Corpses
- Markarth Outskirts
- Ryn's Mehrunes Dagon's Shrine
- Ryn's Azura's Shrine
- Ryn's Ustengrav
- Ryn's Mistwatch Folly
- Ryn's Snazzy Last Vigil + Ebony Warrior Overhaul
- Ryn's Anise's Cabin
- Ryn's Saarthal
- Ryn's Secunda's Kiss
- Ryn's Bleakwind Basin
- Ryn's Goldenglow Estate
- Ryn's Standing Stones
- Environs - Riften Warehouse

### Updated

- ZedPatch 1 - 0.9.2 > 0.9.3
- ZedPatch 2 - 0.9.2 > 0.9.3
- MonsterPatch - 0.4002 > 0.9.3
- DynDOLOD Output - 0.4007 > 0.9.3
- Nemesis Output - 0.9.2 > 0.9.3
- Overwrite Misc - 0.9.2 > 0.9.3

### Tweaks

- Modified Better Third Person Selection MCM to hide the activate key on activation prompts.

## v0.9.2 - **4/6/2023**

**NOTE:** This version is technically save-unsafe, due to some mod updates, but you may find your save is lightly affected. Play on this with an existing save at your own risk and do so WITH A BACKUP!

### Removed

- Sprint Swimming (has issues with movement mods in the list, will be revisited)
- Movement Behavior Overhaul (fix https://github.com/zediious/tpfz-sprinkles/issues/11)
- Rainbows

### Added

- Blank CC Plugins (fix https://github.com/zediious/tpfz-sprinkles/issues/12)
- Conditional Armor Type Animations
- Goetia Movement Animations
- Rainbows Remade

### Updated

- ZedPatch 1 - 0.4007 > 0.9.2
- ZedPatch 2 - 0.4007 > 0.9.2
- Nemesis Output - 0.4007 > 0.9.2
- Overwrite Misc - 0.4007 > 0.9.2
- Vanargand Movement Animations > CATA Version
- Leviathan Movement Animations > CATA Version
- Skyrim Landscape and Water Fixes - 7.6 > 7.7
- Sprint Sneak Movement Speed Fix - 1.0.2 > 1.1.1
- Fancy Sleeping Tree Replacer - 1.3 > 1.5
- Mysticism - A Magic Overhaul - 2.2.2 > 2.2.3
- Adamant - A Perk Overhaul - 5.7.4 > 5.7.6
- Riften Docks Overhaul - 2.3 > 2.5.2
- JK's Windhelm Outskirts - 1.0 > 1.1
- VIGILANT - 1.7.1 > 1.7.2
- VIGILANT - English - 1.7.1 > 1.7.2
- Penitus Oculatus - 0.16.4 > 0.17.0
- Rain Extinguishes Fires - 4.0 > 4.1.0
- Use or Take - 1.1 > 1.2.0
- Read orTake - 1.2 > 1.3.0
- For Honor Power Attack - 1.2 > 1.4
- Reanimated NPC Animations - 1.1 > 1.2
- SPID - 6.4 > 6.5.1

### Fixes

- Using an added Blank CC Plugins mod, all non-default Creation Club content you have will be overridden with a blank plugin. This list is only built around the default 4 creations. (fix https://github.com/zediious/tpfz-sprinkles/issues/12)
- Patched three floating lanterns in the Tamriel worldspace (fix https://github.com/zediious/tpfz-sprinkles/issues/13)
- Fixed incorrect Wildcat MCM configuration (fix https://github.com/zediious/tpfz-sprinkles/issues/9)
- Fix clipping of Alternate Perspective Hunter addon and Pilgrim Magnus Shrine (fix https://github.com/zediious/tpfz-sprinkles/issues/2)
- Fixed incorrect perk formID in Telekinesis Wood Chopping animations. They will now properly play when you have the second level of the "Philosopher" Alteration perk. (fix part of https://github.com/zediious/tpfz-sprinkles/issues/10)
- Removed custom movement animation-by armor type condition files, in favor of the actual Conditional Armor Type Animations mod. I honestly did not realize this mod existed, as I was using my own setup for some time. This one works a little bit better and also includes the Goetia movement animations. (fix part of https://github.com/zediious/tpfz-sprinkles/issues/10)

### Tweaks

- Disabled four aggressive Thalmor that spawn near Kilkreath Ruins on the road from Immersive Patrols. (implement https://github.com/zediious/tpfz-sprinkles/issues/14)
- Disabled base UNDERDOG sprinting animation
- Modified conditions for athletic UNDERDOG sprint animation to not play for actors with heavy armor equipped. This animation will play if your current stamina is above 150, at a 0.7 randomness value.
- Removed Actor Value checks from Goetia Animations conditions, so that they will play whenever armor is not worn, without the player or NPC requiring high Magicka and/or Magic skills.

## v0.9.1.1 - **4/2/2023**

### Fixes

- Actually fixed installation issues.

## v0.9.1 - **4/2/2023**

### Fixes

- Fixed installation issues regarding Skyrim version. You must now install the list with the latest version of Skyrim installed on Steam.

## v0.9 - **4/2/2023**

With the new version of Animated Armory, first-person animations for Animated Armory weapons are now available.

I've also ditched the very odd version schema I chose. Can't explain that one. As the list is prepared for an official "unofficial" wabbajack launch, the version will reach 1.0. From then on, versioning will be done on a save-safe basis, and the documentation will be updated to reflect this.

On that note, this update is **NOT SAVE SAFE!** Due to the updating of certain mods, existing saves will have issues. Refrain from updating for now if you do not want to restart your character.

### Added

- Skyrim Extended Cut - Saints and Seducers
- Undead Snow Elves- Mihail Monsters and Animals
- Undead Snow Elves - Xtudo optimized textures 2K
- JK's Windhelm Outskirts
- JK's Windhelm Outskirts Patch Collection
- Interesting NPCs (3DNPC) Script Optimisation
- Hungers - Optimized textures 2K by Xtudo

### Updated 

- Lawbringer
- Serenity
- Tactical Valtheim
- Skybound Underhang Camp
- Skybound Underhang Camp Lawbringer Patch (fix https://github.com/zediious/tpfz-sprinkles/issues/6)
- Animated Armory
- DynDOLOD Output
- ZedPatch 1
- ZedPatch 2
- Leveled List Additions (Armors)
- Leveled List Additions (Weapons)
- Nemesis Output

### Fixes

- (hopefully) Corrected wrong Creation Kit setup causing installation errors. This may be an ongoing process.

### Tweaks

- Added all Animated Armory whips to mace leveled lists (some tiers were missing)
