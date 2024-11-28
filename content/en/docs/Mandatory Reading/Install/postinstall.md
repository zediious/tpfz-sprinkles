---
title: Post-Mod List Install
weight: 4
---
**Please read everything in this section! There are many important things here!**

## Ensure .NET 5.0 Runtime is installed

This version of .NET is required to launch the game via Mod Organizer. Make sure you have this version installed, even if you already have a newer version.

1. Visit [https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime), and use **"Download x64"** under the **"Run desktop apps"** section

2. Run the downloaded executable file, and use **"Install"**. Make sure this installs successfully.

## Launching Mod Organizer 2

1. Navigate to C:\tpfzs (or wherever you installed the mod list) and open ModOrganizer.exe.

2. If you don't have Microsoft VC_Redist installed, you may see an error. You can download the latest versions here: [https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170#latest-microsoft-visual-c-redistributable-version). Note that this is separate from the .NET 5.0 runtime downloaded above.

3. A dialogue will appear and ask if you want to associate Mod Organizer with nxm links. Click **Yes.**

## Check your Overwrite Directory

Occasionally, Wabbajack and/or Rootbuilder can place files that were installed by other mod lists and/or were already in your Skyrim installation folder inside the Overwrite directory for this mod list. This can cause a number of issues, including extremely long loading times or not loading at all. Perform the following steps to ensure this directory is not interfered with by other files.

1. If you did not perform the steps [here](../clean), you MUST do so. If you are knowledgeable, you may be able to remove files from this directory that should not be there and then simply verify your game install. If you do not understand this, PLEASE follow the directions in the link above.

2. In the left pane of Mod Organizer, scroll all the way to the bottom, where you will find an "Overwrite" mod. Double click this.

3. If you have not run the game yet, this mod/directory should be *completely* empty. If it is not, *double check* that you have performed Step 1. If you have, simply select all of the files inside of the Overwrite mod, right click them, and delete.

If you are *sure* you have performed Step 1, then those file should not be in the Overwrite again. If you find this is not the case, reach out on our Discord.

The only files/directories that should be in the Overwrite mod after launching the game and playing are as follows;

- NetScriptFramework (if you experience a crash, logs go here)
- Root
  - enbcache/cache files
  - betacomments.txt
  - d3dx9_42.log
  - imgui.ini
- ShaderCache/
- SKSE
  - Plugins
    - LamasTinyHUD Loadout .ini files
  - Various plugin log files

## Launching the Game

**PLEASE READ THIS SECTION! IT WILL PREVENT ISSUES!**

The hard part is nearly over. Carry on, the end is in sight!

1. In Mod Organizer 2, select SKSE from the drop-down menu next to the Run button and click Run. You should ALWAYS run the mod list with the SKSE executable, do NOT use the Skyrim SE executable. You can create a shortcut on your desktop if you wish using the Shortcut button under the Run button.

2. At this point Mod Organizer will become "Locked", while the Skyrim executable is running. **Under NO circumstances, should you ever click the "Unlock" button while you are playing the game!** This includes immediately when it appears. Mod Organizer needs to be in this state for the mod list to launch and work properly. If you do click Unlock, you will more than likely be faced with Infinite Loading Screens, or other issues.

3. Once Skyrim starts, create a new game. Loading a save from outside this mod list will corrupt that save, **do not do this!** If you are updating from an existing version of the mod list, read the changelog to ensure that the new version is save-safe.

4. Create your character, and finalize their race/name.

5. **As soon as you gain control of your character, do nothing.** The mods are loading and MCM configurations are being applied. You’ll see a list of mods initializing in the top left of the screen, and you will see popup messages, which you can click OK on. Please, **DO NOT** do anything until notification messages at the top left have ceased. This may take a bit of time, but be patient. This only needs to happen on the first load into a new game.

6. Once you see that no more items are appearing in the list in the top left, you can proceed to the next steps.

7. Make sure you are **not** looking at the Dragon NPC in the room, and press the F10 key. Select a Body Preset from the menu that appears. If you don't care about this as a Male character, select *Zeroed*. You *must* choose a preset as a Male, as the default proportions given are quite wonky. As a Female character, you can safely ignore this if you wish.

8. At this point, you should make a save, and reload that save before continuing.

## The MCM Settings

First and foremost, you should *NEVER* change an MCM setting except for Hotkeys without asking in Discord first. There are a very large number of MCM settings that change the experience drastically, or introduce bugs that are alleviated by disabling or enabling that setting. As such, it can quite literally break your game if you change a setting you should not change. *Please* ask about any non-hotkey MCM settings you wish to change.

On a new game, MCM Recorder will run a custom preset that has been created for this mod list. Most MCM configuration menus will be automatically configured for you, using the needed and recommended settings. Below you will find any mods that may require additional configuration.

### Valhalla Combat

ONLY if you decide to [change the block key](../../mod-list-tweaks/powerattackblock) from Duel Wield Parrying SKSE, you will also need to change the block key in the Compatibility section of this mod. Dual Wield Parrying uses a different system to send the blocking action to the game, and Valhalla needs to know which key is initiating this separate action to properly start a timed block. If you are not rebinding your block key, you do not need to worry about this.

## Take Note of any Current Bugs

Take a look at our full current issue tracker here; [https://github.com/zediious/tpfz-sprinkles/issues](https://github.com/zediious/tpfz-sprinkles/issues). 

Issues that are very frequent and/or effect the experience as a whole will be pinned at the top of the issue tracker. It will be valuable for you to check the others as well to confirm what you may need to look out for in the current version.

Make sure to report any bugs/issues or anything remotely odd on our issue tracker! If an issue already exists for what you're finding, most certainly add a comment expressing that you are seeing the issue as well. Reporting issues you find helps to make this mod list better for everyone :)

## Final Thoughts & Best Practices

- Endorse the mods that have been downloaded by this list! Without the mod authors, the list could not exist. You definitely don't have to click endorse 1500+ times in one day, but check your Nexus download history every once in a while and spend some time endorsing these mods. Wabbajack has made it incredibly easy to get the mods downloaded, but the authors deserve some commendation for their work, in my opinion. [Follow this link to get to your download history!](https://www.nexusmods.com/skyrimspecialedition/users/myaccount?tab=download+history)

- The **Notable Mods** sections in the Wiki sidebar contains a full-detailed breakdown of all the important mods in this list. This section is still a WIP, and many sections only contain stubs with the mod name. Make sure to check it out after you have read the Mandatory Reading section! You can also use "Full Mod List" in the "Other List Information" tab to view the full mod list at Load Order Library.

- When launching the game through Mod Organizer, **NEVER** click the "Unlock" button on the small window that Mod Organizer creates. This **WILL** cause issues!

- Be mindful of loading saves while in game, after you have already loaded into a save. This is **highly discouraged!** Skyrim has an engine issue with not clearing game state fully on save loads, which can cause crashes, save corruption in certain instances, or benign issues. [Check this comment for a more in-depth breakdown](https://www.reddit.com/r/skyrimmods/comments/17h3h2o/comment/k6lnsew/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button). We use a death alternative mod to get around this on death, but it is highly recommended that you do not do so manually without first fully closing the game.

- **NEVER** save right after a loading screen. Wait 15-30 seconds before saving to let scripts finish executing.

- Quicksaves made with F5 are automatically turned into Manual Saves. It is recommended to save **early** and **often**. Every 15 minutes and before interacting with quest NPCs, quest objects, and entering new zones should be sufficient. **Old saves can be deleted, but forgetting to save loses progress forever!**

- It is recommended that you do not load autosaves as a rule. In this mod list, they are **off** by default. If you want to read more about the subject, check out **mator's** [response to a discussion on the topic here](https://www.reddit.com/r/skyrimmods/comments/7bkazq/comment/dpj3cx7/)

- Wabbajack supports updating/upgrading over an existing installation, but it will automatically delete any files that aren’t used for the modlist installation. This means if you have changed the modlist in any way, Wabbajack will delete those changes and **may even delete your saves.** Keep backups of any changes you do make.

- If you plan to launch the Creation Kit within this mod list, you will need to disable the *"Skyrim 1.5.97 Executables"* mod to do so!

## [NEXT >> Mod List Tweaks - Power Attacking and Blocking](../../mod-list-tweaks/powerattackblock)
