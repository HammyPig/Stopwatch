# Stopwatch

A Minecraft data pack that automatically pauses game time when no players are online.

## Documentation

The data pack works by running 'gamerule doDaylightCycle true' when a player is online, and 'gamerule doDaylightCycle false' when no players are online.

The data pack follows the folder structure shown on https://minecraft.wiki/w/Data_pack, and consists of the following files:

- pack.mcmeta: specifies minecraft version compatibility as well as the data pack description
- data/stopwatch/function: where functions are defined
- data/minecraft/tags: determines when functions are ran
