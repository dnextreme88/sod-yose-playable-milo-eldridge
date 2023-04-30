# Introduction

This is a simple modification to add a playable Milo Eldridge seen in Lifeline mode of State of Decay: Year One Survival Edition (YOSE). [Original Nexus Mods release](https://www.nexusmods.com/stateofdecay/mods/499).

Apparently, I noticed that there is no radio command to spawn Milo Eldridge of Lifeline into Story mode but his model exists within the game's files. This mod is intended to add him to your Enclave along with Gurubani Kaur.

This mod adds Milo Eldridge from Lifeline to YOSE story mode. Take note that you can start using your radio commands after reaching the church and after the mission **"Lay of the Land"**. Normally, when you use the radio command **"Bonus Survivor"**, you only spawn Gurubani Kaur. With this mod, you also spawn Milo Eldridge and make him playable immediately. Upon using the radio command, they add the following to your homesite's supply locker:

- 4 Food, 4 Medicine, and 60 rounds of .45cal ammunition (Gurubani)
- 4 Ammo, 4 Fuel, and 15 pipe bombs (Milo)

## Installation

1. To install, place the contents into your Steam directory of your State of Decay YOSE game. For example, **"C:\Steam\steamapps\common\State of Decay YOSE\Game"**.

2. To uninstall, simply remove ```rtsevents.xml``` and ```rtsevents.win.bmd``` under **libs/class3/rts/** directory.

## Contributions

Contributions are welcome! Please create a new branch and make a pull request to the main branch so that I'll review the changes and approve it if it's beneficial enough.

## Compatibility

Not compatible with mods that modify ```rtsevents.win.bmd```. If you wish to use this mod with other mods that modify the same file, check out the changed lines in this repository so you know where to make your changes in ```rtsevents.xml```. After making changes, you must download ```xml2bmd``` from **dude1234** and drag your edited .xml in there to create a new .bmd file. Drag the new .bmd file into your **libs/class3/rts/** directory.

## Credits

- To Undead Labs for making a wonderful game.
- To dude1234 for creating the xml2bmd application.
