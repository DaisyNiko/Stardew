## Stardew Valley Reimagined ##

https://www.nexusmods.com/stardewvalley/mods/4119

author: DaisyNiko

version: 1.0.0

--------------------

### Requirements ###

* [SMAPI 2.11.0](https://www.nexusmods.com/stardewvalley/mods/2400)
* [Content Patcher 1.8](https://www.nexusmods.com/stardewvalley/mods/1915)

--------------------

### Recommended ###

* [Winter Grass](https://www.nexusmods.com/stardewvalley/mods/1601)

--------------------

### Installation ###

1. Download the latest versions of the above required mods.
2. Unzip the [CP] Stardew Valley Reimagined folder into /Stardew Valley/Mods
3. Run the game using SMAPI and start a new save.
4. To uninstall, just delete the mod folder

--------------------

### Recolour compatibility ###

This mod uses Eemie's recolour by default, so if you use that, you can ignore this section. To use vanilla or the Starblue Valley recolour (and you will have to do this every time you update this mod):

1. Go into the /recolours folder
2. Open the subfolder for whichever recolour you want to use
3. Copy ALL of the files (hit CTRL+A on Windows to select all)
4. Paste them into the /assets folder, letting them overwrite the ones in there already

--------------------

### Other mod compatibility ###

The /compat folder contains compatibility patches for mods that would otherwise conflict. To install:

1. Go into /compat and copy the folders of the mod(s) you want
2. Paste them into /Stardew Valley/Mods, letting the file(s) overwrite
3. To uninstall a patch, redownload the original mod

**Incompatible mods**
* Stardew Valley Expanded
* Karmylla's Immersive Map Edits
* Immersive Farm 2 / Immersive Farm 2 Remastered

--------------------

### Configuration ###

After installing, run the game at least once with SMAPI to generate a config.json file in the mod folder. You can open it in Notepad to make changes.

**MapsToIgnore**
* List all the maps from this mod that you DON'T want.
* If you want them all, leave it blank.
* If you want multiple to be ignored, separate them with a comma.
* Map names are capitalised and do not contain spaces.

**IgnoreFestivals**
* Set to true if you want to ignore all the festival maps
* When there is a festival on, the vanilla map will be loaded instead

**example:**

```
{
    "MapsToIgnore": "Backwoods, BusStop, Woods, Mine",
    "IgnoreFestivals": "true"
}
```

This would make the mod ignore the backwoods, bus stop, secret woods, and mine entrance maps as well as all of the festival maps.

--------------------

### Known issues ###

* So far the only problem I've come across is with the Egg Festival map. Everything works perfectly fine, except the NPCs doing the egg hunt with you will run for a little bit, stop when they run into something, and then stop moving until the time's up. So it's not game-breaking or anything but immersion-breaking for sure. Abigail will still win if you don't get enough eggs, though.

--------------------

### Notes/FAQ ###
* Debris, bushes, and trees spawn on Spring 1 when you first create a save, so make sure you install all the mods you want before you start a new game. If you change mods after already creating a save, you might end up with trees and bushes in weird places.
* You might be able to use this mod on an old save by downloading the [Entoarox Framework](https://www.nexusmods.com/stardewvalley/mods/2269) and using the "world_bushreset" command in your SMAPI console, but I can't guarantee you'll have all the grass and trees and stuff. You can try, though.
* When reporting an issue to the Nexus page, please first upload your log to http://log.SMAPI.io and link it with your comment. Then I can help you way faster.