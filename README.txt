### HyperToken
![](hypertoken.png)

Welcome to the HyperToken recomp. This is a recompilation of Wacky Races Starring: Dastardly & Muttley for both Windows and Linux computers. It specifically aims to make 60 Hz playable on PC on top of being portable enough for you to be able to run with more convenience than PCSX2.

The recompilation was made using version 0.0.5 of exoteric33's "PS2-native-recomp" tool and was lucky enough to run the game perfectly with little to no additional coding. If you want to know who deserves the credit for pulling off the recompilation, it's 100% his doing. You can find the project that spawned this here: https://github.com/exoteric33/ps2-native-recomp/issues/129

What i've done is set up the game so that everything is ready to go right out the gate. It's a clean install for all the components that run the game and you only need to launch a single executable on both Windows and Linux to get it started. I'm not entirely sure about how compatible the Windows version is considering i'm mainly a Linux guy, but you've probably already got everything you need if you're at least running Windows 10. The game also comes with a mostly fresh save file. The only info stored on the save game is the enabling of the "60 Hz" mode in the options so you don't have to enable it yourself. Everything else is completely stock.

As for features of the recomp beyond running the game, you can press F1 to configure some additional variables. These include keybinds (if you're using a Keyboard to play the game), Render resolution (which can dispaly at a maximum of 2K), Render sharpness and a quicksave slot. It also saves a backup for your 10 most recent game saves. If your save file corrupts for whatever reason, you can switch it out with the newest one that works.

This recomp doesn't come with any assets from the game. [Update: It turns out there are a few assets that are taken directly from the game that the recomp still contains with the main culprit being "explore_ram.bin" which is a 37 MB dump of the game's memory, but the game still can't be launched with these alone. That's on me for not looking too deep into what was extracted from the recompilation. Oops.] You don't need to look for any particular versions of the game (as it only had one verison on one console), but it does have to be a .iso for the recomp to recognise it, so using a .bin won't work. If all you have is a .bin, there are plenty of tools out there that let you convert between the two formats. Once you have your files, place them in the "games > wackyraces" ("games > Wacky-Races-Starring-Dastardly-M" if you're on Windows) directory and set the name to "disc.iso". Once you've done that, the recomp will recognise the assets.

Launching the game is extremely simple on both Windows and Linux. For Windows users, simply launch the "HyperToken.bat" file, and you're good to go! On Linux, you can either enter "build/native-wackyraces/ps2run --disc games/wackyraces/disc.iso --window --widescreen --memcard SaveGame.ps2 --game-dir games/wackyraces" in the command prompt or run the "HyperToken.sh" shell sript that's also included. You can also add both the BAT and SH file as a game on Steam and launch it that way if you're feeling particularly fancy.

That's all you need to know. This is more of a "portable launcher that enables 60 Hz on PC" than it is a legitimate platform for mods, but that alone is enough justification for me to make it. If we ever get a more in-depth recomp that goes beyond just the main processor, i'll do something similar to what i've done here. It'll probably be called "HyperToken V2" or something along those lines.

Enjoy, you handsome devil!

CREDITS:
Compiler - exoteric33
Shortcuts + Instructions - Hamm Mann
Windows Assistance - Splatrick

Wacky Races Starring: Dastardly & Muttley was made by Gremlin Interactive / Infogrames Sheffield House / Sumo Digital They made the game, not us. Doofus.

DASTARDLY & MUTTLEY AND THE WACKY RACES and all related characters are trademarks of Hanna-Barbera.
©2001 Hanna-Barbera and Heatter-Quigley.
