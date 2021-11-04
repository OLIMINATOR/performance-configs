# Server Performance Configs
Optimized configs aimed for big survival-economy servers. That requires handling a lot of players on a single server. But I highly recommend customizing it for your needs using the guides listed below.  

There are only 1.17 configs for now.
## Guides Used
To optimized these confins I used these guides:
* [YouHaveTrouble's Guide](https://github.com/YouHaveTrouble/minecraft-optimization)
* [Server Optimization Guide](https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/)
* [Paper Chan’s Little Guide](https://eternity.community/index.php/paper-optimization/)
* [Server Optimization Guide](https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/)
* [Anarchy Server Optimization](https://github.com/moom0o/AnarchyExploitFixes/wiki/Anarchy-Server-Optimization-Guide)
* [Top 10 Things You Missed Optimizing](https://blog.airplane.gg/10-things-you-missed-optimizing-survival-mc/) 
* [Shockbyte Reducing Lag](https://shockbyte.com/billing/knowledgebase/21/Reducing-Lag)

## Recommendations

### Stay away from these plugins
* **Stacker plugins** - stacking entities causes more lag because the server is then always trying to spawn new mobs. I would recommend stacker plugins only for stacking mobs from spawners and disabling their AI's.
* **Item removal plugins** - these "free optimization" plugins are most of the time useless as you can "replace" them with item/alt item despawn rates in spigot.yml.

### Check your timings
Use Timings, learn how to analyze it and to figure out what’s causing issues with yourserver.
You can use [BirdFlop's](https://www.birdflop.com/) discord bot on their [discord server](https://discord.com/invite/nmgtX5z) that you can post your timings to and it’ll tell you how your server configuration can be optimized further.

### Usefull Plugins
* [Insights](https://www.spigotmc.org/resources/insights-super-configurable-region-limits-asynchronous-scans-1-17-x.56489/) - Allows you to set storage, redstone, items limits to regions, chunks or islands on skyblock/oneblock servers. 

* [AntiRedstoneClock](https://www.spigotmc.org/resources/antiredstoneclock-worldguard-plotsquard-support-1-8-1-17.18557/) - Disables redstone clocks when your server TPS drops.

* [Spark](https://www.spigotmc.org/resources/antiredstoneclock-worldguard-plotsquard-support-1-8-1-17.18557/) - Allows you to analyse your servers CPU and memory usage.

* [Chunky](https://github.com/pop4959/Chunky) - Pregenerates chunks for better performance on survival servers.
