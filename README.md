# Convenient `mobGriefing`

Makes the `mobGriefing` gamerule more convenient by splitting it into four gamerules:

- `mobGriefing` for most mobs that destroy your world
- `mobGriefingLenient` for passive mobs and things that aren't really annoying
- `mobGriefingWither` for the Wither
- `mobGriefingDragon` for the Ender Dragon

New gamerules are enabled by default.



`mobGriefing` allows:

- Creepers and Ghasts to blow stuff up
- Endermen to take and place blocks
- Silverfish to be annoying
- Ravagers to destroy crops and leaves



`mobGriefingLenient` allows:

- Villagers to harvest crops
- bartering with Piglins
- Sheeps to eat grass
- Snow Golem to create snow
- Rabbits to eat carrot crops
- Foxes to eat sweet berries
- non-player entities to:
    - pick up loot
    - turn farmland to dirt when falling
    - place wither roses when killed by a Wither
    - break turtle eggs
        - This also includes Zombies and Zombified Piglins pathfinding towards them
    - lit campfires
- Evokers to wololo Sheeps



`mobGriefingWither` allows the Wither to destroy stuff

`mobGriefingDragon` allows the the Ender Dragon to stuff



Requires the [Fabric Loader](https://fabricmc.net). The [Fabric API](https://www.curseforge.com/minecraft/mc-mods/fabric-api) is only required for localisation.
