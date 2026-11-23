Welcome to the HyperToken recomp. This is a recompilation of Wacky Races Starring: Dastardly & Muttley for both Windows and Linux computers. It specifically aims to make 60 Hz playable on PC on top of being portable enough for you to be able to run with more convenience than PCSX2.

The recompilation was made using version 0.0.5 of exoteric33's "PS2-native-recomp" tool and was lucky enough to run the game perfectly with little to no additional coding. If you want to know who deserves the credit for pulling off the recompilation, it's 100% his doing. You can find the project that spawned this here: https://github.com/exoteric33/ps2-native-recomp/issues/129

What i've done is set up the game so that everything is ready to go right out the gate. It's a clean install for all the components that run the game and you only need to launch a single executable on both Windows and Linux to get it started. I'm not entirely sure about how compatible the Windows version is considering i'm mainly a Linux guy, but you've probably already got everything you need if you're at least running Windows 10. The game also comes with a mostly fresh save file. The only info stored on the save game is the enabling of the "60 Hz" mode in the options so you don't have to enable it yourself. Everything else is completely stock.

As for features of the recomp beyond running the game, you can press F1 to configure some additional variables. These include keybinds (if you're using a Keyboard to play the game), Render resolution (Which maxes out 2K), Render sharpness and a quicksave slot. It also saves a backup for your 10 most recent game saves. If your save file corrupts for whatever reason, you can switch it out with the newest one that works.

Launching the game is extremely simple on both Windows and Linux. For Windows users, simply launch the "HyperToken.bat" file, and you're good to go! On Linux, you can either enter "build/native-wackyraces/ps2run --disc games/wackyraces/disc.iso --window --widescreen --memcard SaveGame.ps2 --game-dir games/wackyraces" in the command prompt or run the "HyperToken.sh" shell sript that's also included. You can also add both the BAT and SH file as a game on Steam and launch it that way if you're feeling particularly fancy.

If your version of HyperToken doesn't come with an ISO of the game, you'll need to compile it yourself using the "PS2-native-recomp" tool. Once again, you can find it at https://github.com/exoteric33/ps2-native-recomp alongside instructions on how to do so for both Windows and Linux. Once it's been extracted, go to games>[recompname] and take the "disc.iso" file. Place it in the same directory within the HyperToken launcher.

That's all you need to know. This is more of a "portable launcher that enables 60 Hz on PC" than it is a legitimate platform for mods, but that alone is enough justification for me to make it. If we ever get a more in-depth recomp that goes beyond just the main processor, i'll do something similar to what i've done here. It'll probably be called "HyperToken V2" or something along those lines.

Enjoy, you handsome devil!

CREDITS:
Compiler - exoteric33
Shortcuts + Instructions - Hamm Mann
Windows Assistance - Splatrick

Wacky Races Starring: Dastardly & Muttley was made by Gremlin Interactive / Infogrames Sheffield House / Sumo Digital They made the game, not us. Doofus.

DASTARDLY & MUTTLEY AND THE WACKY RACES and all related characters are trademarks of Hanna-Barbera.
©2001 Hanna-Barbera and Heatter-Quigley.
