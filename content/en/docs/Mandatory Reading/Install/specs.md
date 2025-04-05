---
title: Profiles and System Specifications
weight: 1
---

## Profiles

With this modlist, you have the option to choose between the three different Mod Organizer Profiles. Each of these profiles provide a different level of performance.

By default. the list uses the "Refined" profile. The other two profiles are "Refined - Performance" and "Refined - Ultra". If you are able to use the "Refined - Ultra" profile, you will have the best visual experience the list can offer.

Below is a list of the differences between these three profiles

<div align=center>

| Profile | Shaders | Rules | Tree LOD | Using Grass LOD
|     :---:    |     :---:     |     :---:     |     :---:     |     :---:     |
| **Refined (The default profile)** | Community Shaders | High | 3D | NO
| **Refined - Ultra** | Community Shaders | High | 3D | YES |
| **Refined - Performance** | Community Shaders | Medium | 2D | NO |

<br>

</div>

Keep in mind that **Community Shaders** does still enact a sizeable performance impact. You can safely disable all of the mods in the **COMMUNITY SHADERS** separator to further increase performance in the "Refined - Performance" Profile

You can use either profile, and you can switch between them at any time. To do so, click the "Profile" dropdown menu at the top of the left pane in Mod Organizer 2, and select your desired profile. Note that any changes made in one profile will **not** reflect in the others.

Note that you have multiple ENBs you can use as an option if you choose. These exist near the very top of the the left pane of Mod Organizer, alongside Community Shaders and it's addons. Ensure that you **disable** Community Shaders if you decide to do so.

## Page File Configuration

This mod list is quite large, and consumes quite a bit of memory (RAM) while running. Due to the way Skyrim's engine works, there are times where the engine itself is unable to allocate more of your actual dedicated memory (RAM), leading to crashes. We can resolve this by manually defining a larger "Page File" for Windows/Skyrim to use. A Page File is space/a file on one of your disk drives (preferably an SSD) that can be used in place of memory when there is not enough dedicated memory available. Follow the below steps to set up and configure your page file.

*Note: These steps were taken almost directly from [this page](https://www.thewindowsclub.com/increase-page-file-size-virtual-memory-windows), with a few changes.*

1. In the Taskbar Search, type “Advanced System“. You will see View Advanced System Settings. Click on it. Or you can navigate to it via the Control Panel (Search “Advanced Settings” in the search box and then click View advanced system settings under the System option)
2. In System Properties, click the Advanced tab
3. In the Performance section click the Settings button
4. Performance Options will open. Click Advanced tab
5. Here, under Virtual memory, select Change
6. Uncheck "Automatically manage paging file size for all drives" at the top.
7. Highlight your Windows system drive. This should be an SSD!
8. Select Custom size
9. Change the Initial size value to `40960` and the Maximum size value to `40960`
10. Click Set
11. Finally, Click Apply/OK all the way.

The values above are what I use on my computer. I do not recommend you use any more than that.

## System Specifications

You should absolutely have Skyrim and this mod list installed onto an SSD, and they should be on the same SSD. Using a HDD **will** induce lower framerates, stutters, and possibly other issues related to stability. If you have no choice, the list will *function* to a degree, but your experience will be heavily degraded.

Skyrim is very heavy on processors, and also happens to not make use of all available processor cores. This means that processors that are designed with a lot of lower power cores may have trouble running the game/this list. Generally, anything above 3GHz should be fine but I can’t guarantee it. With my hardware, I have no CPU bottleneck whatsoever.

When this mod list was made, I had a GTX 980. In November 2023, I upgraded to a RTX 4070. The below section will start with my initial report on the performance with the 980. The "Ultra" preset did not exist while I had the 980. Afterwards, I will describe the performance with the 4070 across all profiles. Please use these as a guideline to see if you are able to run this mod list based on the information after the specification tables. I can make no guarantees, as certain hardware configurations may result in bottlenecks or other issues.

Keep in mind, that you do have the option of using [Frame Generation Mods](../../mod-list-tweaks/nvidiadlss) with this modlist, which will increase your framerate a noticeable amount. Check this linked page for more information!

<hr>

<div align=center>

| Category | My Old Specs |
|     :---:    |     :---:     |
| **CPU**   | Intel i7-9700K Boost Clock to 4.7GHz |  
| **GPU**    | NVIDIA GTX 980 4GB       |
| **Memory**    | 32GB 3200MHz     |
| **Storage**    | WD Blue SATA SSD     |

</div>

NOTE: The "Refined - Ultra" profile will NOT run well with a GPU equivelent to a GTX 980

When running this mod list with the default "Refined" profile, my FPS is 60 in 99% of interior spaces, and will dip into ~30-40 in heavy outdoor areas (such as The Rift). When VRAM caps are reached, which occurs often with my hardware, I can experience large stutters momentarily that can bring me down to ~20 FPS.

If you have worse specifications than the below or cannot deal with the performance described above, you can switch to the "Refined - Performance" profile within Mod Organizer 2, to use Community Shaders instead of ENB, and utilize a less intensive DynDOLOD preset.

If I play the list with the "Refined - Performance" profile, nearly all performance issues described in this page are gone. What remains is large stutters momentarily that can bring me down to ~30 FPS, due to VRAM limits being reached. These usually only occur after a long play session, and go away for about 30 minutes at a time.

I also recommend 6GB of VRAM, however as shown above it is possible to run this list with 4GB of VRAM. When doing so, you may be exposed to occasional VRAM related stuttering and FPS drops during extremely heavy moments, or rarely crashes. In my experience, I am able to play 3+ hour long sessions on this list with no crashes, only very rarely do these crashes occur. You will know it is a GPU related crash if your crash logs reference a `nvwgf2umx.dll` (with NVIDIA Graphics Cards).

Again, I HIGHLY recommend that you have 6GB of VRAM when running this list. It will make for a better time overall, but you absolutely can use less.

<hr>

<div align=center>

| Category | My Current Specs |
|     :---:    |     :---:     |
| **CPU**   | Intel i7-9700K Boost Clock to 4.7GHz |  
| **GPU**    | NVIDIA GTX 4070 12GB       |
| **Memory**    | 32GB 3200MHz     |
| **Storage**    | WD Blue SATA SSD     |

</div>

When running this mod list with the default "Refined" profile, my FPS is 60 in 99% of locations in the game world. There are very few instances that will drop the framerate for small moments, such as extremely intensive fights where many effects are going on or heavily scripted moments. General gameplay is extremely smooth, and stuttering or sudden FPS drops are near non existent.

Using the "Refined - Performance" profile is not necessary with a 4070, though you can of course use either profile.

The "Refined - Ultra" profile runs at 60 FPS in all interiors, and in most places in the game world. Looking out over locations such as the Whiterun Tundra can drop the FPS to 35-50 due to the large amount of grass LOD being loaded. Any other locations in the world do not have a noticeable FPS drop. FPS drops in general gameplay are very rare, and not something to note.

<hr>

As mentioned, there may be certain hardware configurations that could deviate from the above two anecdotes.


## [NEXT >> Installing Skyrim and the Creation Kit](../clean)
