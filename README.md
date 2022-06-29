# Chunky SMP
Various files associated with the Chunky SMP server

IP: chunky-smp.grvy.dev

Ask @ShirleyNeko on Discord in `#chunky-smp-server` channel to be added to whitelist


## Coordinates 

Key Coordinates are stored within `coords.txt`. Alternatively see Xaero's Minimap/WorldMap for Waypoints.


## Mods

[Plasmo Voice](https://www.curseforge.com/minecraft/mc-mods/plasmo-voice) is supported on the server.

### Other mods

I recommend using Fabric along with a mixture of the mods found below depending on what you are looking for.

#### [Fabulously Optimized](https://www.curseforge.com/minecraft/modpacks/fabulously-optimized)

This modpack is the one stop shop for your modern performance boosts, OptiFine feature parity, and various minor tweaks and improvements that don't break the vanilla feel.

#### [Bobby](https://www.curseforge.com/minecraft/mc-mods/bobby)

Bobby not only allows for render distances greater than the servers view-distance but it does so by caching the chunks on disk which can be recalled at any point. This is unlike with OptiFine or Farsight (included in Fabulously Optimized) which only have a volatile cache surrounding the player.

If using the Fabulously Optimized modpack please remove Farsight before using Bobby.

`Mods > Bobby > Configure > Cleanup Unused Regions (Days)` Must not be set to `0`. I recommend using `-1` to disable cleanup.

#### [Distant Horizons](https://www.curseforge.com/minecraft/mc-mods/distant-horizons)

Distant Horizons adds simplified terrain past Minecraft's default view distance to improve performance and allow for longer draw distances.

I do believe the options I use are default outside of the Chunk render distance but I will list them anyway.

`Options > Distant Horizons config > Graphics >`
Quality options: Block, 256, Medium, 12, Medium, Auto, 1
Fog options: Far, Enabled, Use world fog, True

#### [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) and [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)

Not sure what else to say here... It's a Minimap and World Map. I've added a number of waypoints that may or may not be useful. I just document everything I find.


