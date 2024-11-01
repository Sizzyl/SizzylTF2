# SizzylTF2
This is everything I use in TF2 that isn't [my custom hud](https://github.com/Sizzyl/SizzylHUD) that I'm allowed to put here by mod creators
(some mod creators don't allow people to redistribute their stuff and those mods will be listed further down in the READMe).
Luckily as of writing this, I'm allowed to redistribute all the modss here, but it's worth noting that the larger mod files will only be downloadable via the releases tab and they won't be in the main repository.

## Install / Use
#### Windows
1. Download the most recent ZIP file for the version you want (with/without SizzylHUD) from [Releases](https://github.com/Sizzyl/SizzylTF2/releases).
2. Download [Java 17 or higher](https://adoptium.net/) and install it
2. Unzip the files from step 1 and drag the files inside of 'sizzyltf2' into your Team Fortress 2 root folder (the one you find when you hit 'browse files' in the properties tab on TF2.
3. Doubleclick on quickprecache_auto.bat to run it (will only work with java installed and is needed for quickprecache).
4. Right click TF2 on steam, go to launch options and paste ```+exec preloader```
5. Launch the game (it should now crash)
6. After launching the game and having it crash once, remove ```+exec preloader``` from your launch options, the mods are now installed.
#### Linux/MacOS (you can also try this if the windows install instructions don't work)
1. Download the most recent ZIP file for the version you want (with/without SizzylHUD) from [Releases](https://github.com/Sizzyl/SizzylTF2/releases).
2. Unzip the foldeer and delete the files associated with quickprecache: ```precachelist_mcp_full.txt, precachelist_mcp_nohats.txt, QuickPrecache.jar, quickprecache_auto.bat, quickprecache_mcp_full.bat, quickprecache_mcp_nohats.bat``` in main folder and  ```QuickPrecache.vpk``` in the custom folder.
3. Drag the files inside of 'sizzyltf2' into your Team Fortress 2 root folder (the one you find when you hit 'browse files' in the properties tab on TF2.
4. Download Pilso's [Modern Casual Preloader latest version](https://gamebanana.com/wips/79779).
5. Unzip Modern Casual Preloader and put all the files in your Team Fortress 2/tf/custom folder (right click tf2 on steam, hit browse local files, and click into the tf then th custom folder).
6. Right click TF2 on steam, go to launch options and paste ```+exec preloader```
7. Everything will now work! The downside of this mod is that the main menu will reload like 2-3 times ever time you launch the game and it'll take around 20-30 seconds for the game to fully load (you'll know it's loaded when the level coin is moving).

## WARNINGS
1. Things might not work without the exact launch options I use.
Here are my launch options (for a 1080p display, if you have a different resolution, change the w and h values to your monitor's resolution,
if you don't want to play borderless windowed remove ```-windowed -noborder -w 1920 -h 1080``` entirely):

```-novid -nojoy -nosteamcontroller -particles 1 -precachefontchars -windowed -noborder -w 1920 -h 1080```
Novid disables the starting video, nojoy disables controllers, nosteamcontroller disables the stream controller, particles1 + precachefontchars are optimizations everyone should use, everything after that is for borderless windowed mode.

2. Mods with files included in this repo might not have proper settings for your system OR be fully up to date. They are simply what I personally use. It is heavily reccomended to download each mod individually from their page listed below.

3. This is also not optimized for any system other than my own. It is likely better to pick and choose what mods/quality levels you'd like to use invidually, especially if you're on a lower end system.

## Mods/Files included in this repo
- my own personal autoexec.cfg file (which you're allowed to tamper with in any way you see fit unlike any other file included in this repo)
- [Mastercomm's Mastercomfig](https://comfig.app/app/)
- [Kylul's Soldier Animations](https://gamebanana.com/mods/206373)
- [Kylul's Pyro Animations](https://gamebanana.com/mods/206311)
- [Kylul's Demoman Animations](https://gamebanana.com/mods/373379)
- [Kylul's Spy Animations](https://gamebanana.com/mods/307980)
- [Kylul's Engineer Animations](https://gamebanana.com/mods/400704)
- [Xilekai's Control Point Illumination Fix](https://gamebanana.com/mods/538185)
- [SiFWolf's Better Kill Icons](https://gamebanana.com/mods/406361)
- [newguy111's Spy Reload Fix](https://gamebanana.com/mods/196596)
- [90FOV Fix for Medic](https://gamebanana.com/mods/285109)
- [Pistol Enhancement Pack](https://gamebanana.com/mods/523205)
- [Paysus's Scout Animations + Lugermorph Fix](https://gamebanana.com/mods/522553)
- [Paysus's Heavy Animations](https://gamebanana.com/mods/206261)
- [QuickPrecache (EXPERIMENTAL)](https://gamebanana.com/mods/524713)

## Mods/Files that are too large to include in the repo itself but are in the zip in the 'releases' folder
- [Main Menu Character Overhaul](https://gamebanana.com/mods/294786)
- [Linux Patch for Main Menu Character Overhaul](https://gamebanana.com/mods/502532)
- [Pilso's Classic-Style Animated Backgrounds Pack](https://gamebanana.com/wips/86687)
- [SizzylHUD(only in the SizzylHUD marked ZIP)](https://github.com/Sizzyl/SizzylHUD)

### Wayback Machine / Imgur backups of mod sites showing the licenses I claimed (or pictures of the creators giving me permission to redistribute where required):
- Mastercomfig - https://web.archive.org/web/20240930064041/https://github.com/mastercomfig/comfig-app/blob/develop/LICENSE.md
- Soldier Animations - https://web.archive.org/web/20240930064209/https://gamebanana.com/mods/206373
- Pyro Animations - https://web.archive.org/web/20240930064218/https://gamebanana.com/mods/206311
- Demoman Animations - https://web.archive.org/web/20240930063929/https://gamebanana.com/mods/373379
- Spy Animations - https://web.archive.org/web/20240930063909/https://gamebanana.com/mods/307980
- Engineer Animations - https://web.archive.org/web/20240930063919/https://gamebanana.com/mods/400704
- Point Illumination Fix - https://web.archive.org/web/20240930063907/https://gamebanana.com/mods/538185
- Modern Casual Preloader - https://web.archive.org/web/20240930063913/https://gamebanana.com/wips/79779
- Animated Backgrounds - https://web.archive.org/web/20240930063202/https://gamebanana.com/wips/86687
- Better Kill Icons - https://web.archive.org/web/20240930063140/https://gamebanana.com/mods/406361
- Spy Reload - https://web.archive.org/web/20240930062950/https://gamebanana.com/mods/196596
- 90FOV Medic - https://web.archive.org/web/20240930062455/https://gamebanana.com/mods/285109
- Pistol Enhancement - https://web.archive.org/web/20241001230717/https://steamcommunity.com/id/feedbackfox + https://web.archive.org/web/20241001230827/https://gamebanana.com/mods/523205
- Paysus Heavy Animations - https://i.imgur.com/wKDdZwv.png
- Paysus Scout Animations + Lugermorph - https://i.imgur.com/wKDdZwv.png + https://i.imgur.com/RJ5FS9i.png
- QuickPrecache - https://web.archive.org/web/20241004042502/https://gamebanana.com/mods/524713
- Main Menu Chars - https://web.archive.org/web/20241007012500/https://gamebanana.com/mods/294786
