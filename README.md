# XRay Client

A mining aid that hides the blocks you do not care about. Stone, dirt and gravel stop being
drawn; ores, chests and whatever else you put on the list stay visible, hanging in the dark
where they actually are. Turn it off and the world fills back in.

Because it works by skipping blocks at the point the chunk mesh is built, the world itself is
untouched — nothing is changed on disk, and switching back is instant.

## What is in the build

- a block list you edit in game, with a search box rather than a config file
- fullbright, so the caves you just revealed are not pitch black
- a small coordinate and biome readout, if you want it
- an installer that writes a launcher profile for you, with Standalone, NeoForge and Fabric
  options so it can sit alongside a modpack instead of replacing it

The NeoForge and Fabric builds exist because most people asked for the same thing: keep the
mods they already play with, and add this on top. Those builds are ordinary mods — they load
from the `mods` folder like anything else, and they coexist with Sodium.

## On this repository

This is a maintained in-house product rather than a port, so the source is not mirrored here.
Build notes, the block-list format and the installer's behaviour are documented on the product
page; questions and bug reports are welcome at **9minecraft.net@gmail.com**.

## Where to get it

Installer, the three loader options, and the setup walkthrough are here:
[9minecraft.net/9minecraft-xray-client](https://www.9minecraft.net/9minecraft-xray-client/)

## A note on where to use it

Plenty of servers treat this kind of tool as cheating, and some ban for it. On your own worlds
and on servers that allow it, enjoy; everywhere else, read the rules first. That is on you.

## Credits

Built and maintained by 9Minecraft Studios.
