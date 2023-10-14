---
title: Power Attacking and Blocking
weight: 1
---
In this mod list, we use Dual Wield Parrying SKSE to modify our block hotkey to Mouse Button-4, and For Honor Power Attack to modify our power attack hotkey to Mouse Right-Click. Below you will find instructions on changing your block key. If you want to change your block key back to the Mouse Right-Click, then you will need to remove For Honor Power Attack. Instructions are below for doing this as well.

## Changing the Block Key

1. In the left pane of Mod Organizer, use the search bar at the bottom to search for "Dual Wield". Double click the "Dual Wield Parrying SKSE" mod.

2. Click the "INI Files" tab at the top, and click the "DualWieldParryingSKSE.ini" file on the left tab.

3. You will need to set the "ParryKey" value to a number that corresponds to a key, mouse button, or controller button "Dec" value [at this link](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes). Do **NOT** set or use the "ParryKey2" value. Due to the below reason, you can only use one block key.

If you do change your block key, you will also need to change the block key in the Compatibility section of Valhalla Combat's MCM. Dual Wield Parrying uses a different system to send the blocking action to the game, and Valhalla needs to know which key is initiating this separate action to properly start a timed block.

## Changing the Power Attack Key

1. In the left pane of Mod Organizer, use the search bar at the bottom to search for "For Honor", and uncheck the "For Honor Power Attack" mod.

If you only wanted to change the power attack key back to the default, this is all you need to do. If you want to change it to something else besides the the Mouse Right-Click or hold Mouse Left-Click, you will need to use the [One Click Power Attack NG](https://www.nexusmods.com/skyrimspecialedition/mods/60878) mod. I cannot provide support if you decide to use this. Read the mod description and posts!

## [NEXT >> Enabling Dark Mode Interface](../darkinterface)
