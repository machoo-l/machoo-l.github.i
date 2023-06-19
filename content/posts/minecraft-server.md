---
title: "Minecraft Server"
date: 2023-06-19T11:01:16-05:00
draft: false
tags: 
    - Technology
---

Minecraft servers are single threaded
so having more CPU cores will not improve the server's performance.
Articles recommend 1GB to 2GB of allocated RAM for 10
people on a server.

### Client Side
(1.20.1) [Fabric](https://fabricmc.net/) is mod loader for Minecraft.

(1.20) [OptiFine](https://optifine.net/home) is an optimization mod for better 
performance. Usually you install OptiFine on its own without the Fabric mod loader
but since we want voice chat we will need to supplement it with OptiFabric.

(1.19.4) [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric) allows OptiFine
to run on the Fabric mod loader.

(1.20) [Simple Voice Chat](https://legacy.curseforge.com/minecraft/mc-mods/simple-voice-chat/files/all?filter-status=1&filter-game-version=2020709689:7499) adds voice chat to Minecraft.

### Server Side
(1.20.1) [PaperMC](https://papermc.io/) is a Minecraft game server designed to improve 
performance.

