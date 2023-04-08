Changelogs were not written before compiling to Wabbajack. The modlist had undergone a very large number of changes over the years before this point. There will be a number of changes that are not logged. Retroactive changelogs will be written.

Basic conflict resolution is generally not included here, unless it was done to fix an existing issue. Every addition to the list is vetted thouroughly before a version is released.

**If the third number in a version (the 3 in 9.1.3) is changed, then that version is NOT SAFE to update to on an existing save.**

## v0.9.3 - **4/8/2023**

**NOTE:** This version will have some initial issues in exisiting saves. Some of the modified locations that have changed persistent references in the world will not apply their changes on existing saves. Lawless will only apply some of its changes on cell reset. Play on this with an existing save at your own risk and do so WITH A BACKUP!

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

- Using an added Blank CC Plugins mod, all non-default Creation Club content you have will be overriden with a blank plugin. This list is only built around the default 4 creations. (fix https://github.com/zediious/tpfz-sprinkles/issues/12)
- Patched three floating lanterns in the Tamriel worldspace (fix https://github.com/zediious/tpfz-sprinkles/issues/13)
- Fixed incorrect Wildcat MCM configuration (fix https://github.com/zediious/tpfz-sprinkles/issues/9)
- Fix clipping of Alternate Perspective Hunter addon and Pilgrim Magnus Shrine (fix https://github.com/zediious/tpfz-sprinkles/issues/2)
- Fixed incorrect perk formID in Telekinesis Wood Chopping animations. They will now properly play when you have the second level of the "Philosopher" Alteration perk. (fix part of https://github.com/zediious/tpfz-sprinkles/issues/10)
- Removed custom movement animation-by armor type condition files, in favor of the actual Conditional Armor Type Animations mod. I honestly did not realize this mod existed, as I was using my own setup for some time. This one works a little bit better and also includes the Goetia movement animations. (fix part of https://github.com/zediious/tpfz-sprinkles/issues/10)

### Tweaks

- Disabled four aggresive Thalmor that spawn near Kilkreath Ruins on the road from Immersive Patrols. (implement https://github.com/zediious/tpfz-sprinkles/issues/14)
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

I've also ditched the very odd version schema I chose. Can't explain that one. As the list is prepared for an official "unoffical" wabbajack launch, the version will reach 1.0. From then on, versioning will be done on a save-safe basis, and the documentation will be updated to reflect this.

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

## v0.4006 - **4/1/2023**

### Removed

- Vanilla Body with UNP Textures
- Pride of Valhalla - UNP Textures
- High Poly Male Hands
- Ebony Mage Armor

### Added

- CBBE
- Pride of Valhalla - CBBE Textures
- HIMBO
- BodySlide
- OBody NG
- BodySlide Output
- CBBE and HIMBO BodySlide Refits for all armors that have them (70 mods total) in new mod category
  - I plan to create CBBE/HIMBO BodySlide patches for all used armor mods that do not have them

### Updated

- Lunar Guard Armor

## v0.4005 - **3/30/2023** 

### Added

- Apothecary - Food and Drink - Survival Mode Patch

### Fixes

- Fixed MCM Recorder preset being stuck on Thieves Guild Requirements. That mod will need to be manually configured.
- Patched Saints and Seducers CC content and Skyrim Sewers 4, moving Skyrim Sewers manhole.
- Patched Apothecary - Food and Drink - Survival Mode Patch with existing patches

### Tweaks

- Added Survival Mode effects to food items added by;
  - 4thUnknwon Ogre
  - Mihail Sea Cow
  - Riften Docks Overhaul
  - Capital City Windhelm
  - Immersive Encounters
  - Fortune's Tradehouse
  - Khajiit Will Follow

- Added drunk effects to specialty drinks added by;
  - Obscure's College of Winterhold
  - Beyond Skyrim Merchant
  - Fortune's Tradehouse
