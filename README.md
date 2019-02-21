# ConfigureMachineSpeed
Stardew Valley Mod: Allows you to change how long it takes for various machines (e.g. kegs, oil maker) to finish.

## Installation:
1. Install the latest version of SMAPI
2. Unzip `ConfigureMachineSpeed.zip` into Stardew Valley/Mods.
3. Run the game using SMAPI.


## Compatibility:
- Works with Stardew Valley 1.3 on Linux/Mac/Windows.
- Untested on custom machines (let me know what happens if you try it).
- No known mod conflicts (let me know if you find one).


## How To Use:
1. Run the game using SMAPI at least once to generate a ?config.json file inside `Stardew Valley/Mods/ConfigureMachineSpeed`.
2. In the `config.json` file you will see two keys: `UpdateInterval` and `Machines`.
3. `UpdateInterval` sets how often the mod will check the machine's remaining time and alter it if necessary. It's probably fine as-is, but feel free to change it.
4. `Machines` is where you will add info about which types of machines you wish configure. For example: `"Machines": [?{ "Name": "Bee House", "Minutes": 30}]` will make Bee Houses output honey every 30 in-game minutes.


## Supported Machines:
- Bee House
- Keg
- Mayonnaise Machine
- Cheese Press
- Cask
- Crystalarium
- Furnace
- Loom
- Preserves Jar
- Recycling Machine
- Seed Maker
- Worm Bin
- Tapper
- Slime Incubator
- Oil Maker

## Known Bugs/Unsupported Machines:
- Right now the mod only works for speeding up the machines because I'm silly
- Crab Pots don't respond to the mod
- Casks don't consistently output higher quality products