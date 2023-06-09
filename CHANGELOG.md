Changelogs were not written here before compiling to Wabbajack. The modlist had undergone a very large number of changes over the years before this point. There are be a number of changes that are not logged. Retroactive changelogs will be written here over time. Most times, if I have changed a mod in any way, I created Notes for that mod in Mod Organizer, which you can by hovering over the notepad icon on the mod in the left pane of MO.

Basic conflict resolution when adding a mod is generally not included here, unless it was done to fix an existing issue. Every addition to the list is vetted thoroughly.

If the third number in a version (the 3 in 9.1.3) is changed or added, then that version is **NOT SAFE** to update to on an existing save at all. If the fourth number in a version (the 4 in 9.1.3.4) is changed or added, then that version should be safe to update to on an existing save, but you may encounter some non-breaking issues. This schema will be changed when the mod list reaches version 1.0.



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
- Fixed duplicate crosshair when using magic and weapon (fix part of https://github.com/zediious/tpfz-sprinkles/issues/63)
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
- Snowy Surfaces Sound Collision and Aesthetics 1.6.2 > 1.6.3
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
