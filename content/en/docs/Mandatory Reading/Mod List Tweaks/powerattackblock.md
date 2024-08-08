---
title: Power Attacking and Blocking
weight: 1
---
In this mod list, we use Dual Wield Parrying SKSE to modify our block hotkey to Mouse Button-4, and For Honor Power Attack to modify our power attack hotkey to Mouse Right-Click. Since not everyone may have a mouse with additional buttons, these may need to be changed. Below you will find instructions on changing your block key. If you want to change your block key back to the Mouse Right-Click, then you will need to remove For Honor Power Attack and use One Click Power Attack. This is currently unsupported.

## Changing the Block Key

1. In the left pane of Mod Organizer, use the search bar at the bottom to search for "Dual Wield". Double click the "Dual Wield Parrying SKSE" mod.

2. Click the "INI Files" tab at the top, and click the "DualWieldParryingSKSE.ini" file on the left tab.

3. You will need to set the "ParryKey" value to a number that corresponds to a key, mouse button, or controller button "Dec" value [at this link](https://ck.uesp.net/wiki/Input_Script#DXScanCodes). Do **NOT** set or use the "ParryKey2" value. Due to the below reason, you can only use one block key.

If you do change your block key, you will also need to change the block key in the Compatibility section of Valhalla Combat's MCM. Dual Wield Parrying uses a different system to send the blocking action to the game, and Valhalla needs to know which key is initiating this separate action to properly start a timed block.

## Changing the Power Attack Key

Please note that**I cannot provide support if you decide to change your Power Attack key.** Strange behavior can occur relating to power attacks not triggering as they should, where blocking happens instead. If you want to change your power attack key, you will need to follow the below steps;

1. Disable/uncheck the **For Honor Power Attack** mod in the left pane of Mod Organizer.

2. In game, open the Mod Configuration Menu, open the **BFCO** menu. Set the Power Attack Key (first option in the list) to your preferred key. This is set to SCRLK by default as it is an oft-used key.

To re-iterate, this *will* cause strangeness with blocking occuring when you try to power attack with this hotkey sometimes. I do not recommend you do so.

## [NEXT >> Switching Interface Theme](../interfacetheme)
