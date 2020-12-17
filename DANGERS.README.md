
***

# Dangers

Starting in one of the early LabMax builds, I started using bee hives and bee nests as building material. Due to the tens of thousands of these blocks being placed, there is a security issue that needs to be addressed:

Bee nests/Bee hives spawn bees periodically. I have always had the `Mob_Spawning` gamerule set to false, and I haven't had a problem. I didn't know that bees would periodically spawn from them.

So **DO NOT TURN ON `MOB SPAWNING`!!**

Even the mightiest of gaming computers can't handle the game well for more than a minute due to the sheer number of bees that will spawn (at least 200,000) I estimate that devices with 10 Gigabytes of RAM or less will automatically crash if you turn on the `Mob_Spawning` gamerule.

DO NOT RUN THIS COMMAND OR ENABLE IT IN SETTINGS:

`/gamerule doMobSpawning true`

`/doMobSpawning true`

***
