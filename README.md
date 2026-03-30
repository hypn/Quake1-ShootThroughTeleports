# Quake1-ShootThroughTeleports

## What it does:
Allows larger weapons (nails, grenades and rockets) to be fired through teleporters.

Demo: [https://imgur.com/a/7Tj97y0](https://imgur.com/a/7Tj97y0)

**NOTE:** Does not work for some teleporters (eg: on map DM4) :/

## How to use it:
Make a "ShootThroughTeleports" directory in your Quake1 directory (or in `Quake\rerelease` for Quake Enhanced), put the "PROGS.DAT" file in the directory, and launch the game with:
```
quake.exe -game ShootThroughTeleports
```

Then shoot at teleporters :)

## How to compile it
* download QuakeC Compiler (QCC) from [https://github.com/id-Software/Quake-Tools/tree/master/qcc](https://github.com/id-Software/Quake-Tools/tree/master/qcc)
* download this repo's "src" directory
* run DOSBox, mount both paths, and in the "src" directory and run:
```
<path_to_qcc>\qccdos.exe
```
(or use a [more modern qcc compiler binary](https://github.com/hypn/quake-qcc-binaries) like `qcc-i686-linux-gnu`)
