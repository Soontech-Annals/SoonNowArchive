# Scicraft Hybrid Main Storage
<img alt="area_render_1_.png" src="images/area_render_1_.png?raw=1" height="300px">

**Authors:** *jorvp, Obi81, commandleo, Glotz, raffq, rapscallion1138, boyenn, floppydonkey*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1469555372892094619)

The Scicraft Hybrid Main Storage is a hybrid encoded storage system, which means it uses regular filters for loose items and encoded box sorting. This system is complete, and is in use in the Scicraft technical Minecraft survival server.
## Features
- 86.5% hopper locking. (15% of the unlocked hoppers are due to the mass crafter. You can get rid of it to achieve almost 99% hopperlocking.)
- 0.5mspt idle, 5mspt active (Ryzen 9 7950X with lithium 1.19.2).
- 3 Hybrid Halls, which means both items and boxes in the same hall, which makes for a very interesting item layout.
- Up to 378 Bulk Items, 756 Loose items.
- Fixed item encoded remote bulk.
- CommandLeo's unstackable sorter.
- Parallel unloader, (FITu) which allows for sorting items in parallel.
- Complete item layout with encoder setup.
- Multiple peripherals (furnace array, crafting station, Mass crafter, Box yeeter crafter, etc.)
- Full system status output panel
- Basic error checking, can pause the input if there is a problem
- Not a single Togglestate, which means every latch can be reset, with multiple buttons to reset them if there's a server crash.
- Chunkloaded, bulk chunkloaders only activate when needed.
## Instructions
1. Please watch the youtube video first.
## Notes
Mass Crafter does NOT have chunkloaders. Do not Unload the area while using it! Make sure the subchunk
is correct! Masscrafter is locational in that way, due to how mod4 works, it needs to be located in a Y level so the items go through a subchunk.
## Compatibility
1.19
## Detailed Credits
- 1.19 Unstackable Sorter By CommandLeo
- Encoder by Obi
- Hall by Obi, with tweaks of CommandLeo and some things by jorvp. The original idea was put together by jorvp and FloppyDonkey, the original components are both from Optic.
- Bulk by Obi
- Priority list by Obi
- FIT (First item type unloader) by Glotz, Raffq, Rapscallion and Boyenn
- Mass Crafter by Glotz
- Item Layout by jorvp and Glotz
- Furnace Array by FloppyDonkey
- Crafting stations by CommandLeo

## Other Images
<img src="images/area_render_2_.png?raw=1" height="300px">

## Resources
- [ES003_Scicraft_Hybrid_Main_Storage.zip](attachments/ES003_Scicraft_Hybrid_Main_Storage.zip): MC 1.19.2
- [ES003_Scicraft_Hybrid_Main_Storage.pdf](attachments/ES003_Scicraft_Hybrid_Main_Storage.pdf): application/pdf
- [Unknown Title](https://www.youtube.com/watch?v=8VbCW-Fqjhw%29): by [Unknown Author](#)
