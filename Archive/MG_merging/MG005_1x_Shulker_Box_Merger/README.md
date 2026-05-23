# 1x Shulker Box Merger
<img alt="image.png" src="images/image.png?raw=1" height="300px">

**Authors:** *Lukeem, Matrixsu*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1507674508679712930)

A compact merger that uses pairs made by a temporary storage in order to merge them together producing a more full box. Significantly smaller footprint than normal 1x mergers. Designed to be used in any system that has a need for merging. Made to be significantly easier to debug and fix than previous mergers by only having 1 latch in the whole system (lime concrete button is used to reset this). Includes a 4x, 8x and FHL versions of both.
## Features
- Minimal amount of hoppers
- Small size (5x9)
- Pretty much infinitely expandable
- Minimal amount of latches (1 latch which is the dropper on the front)
- 36 hoppers
- Can handle pairs being broken from unloaded (handles 1 box being input alone)
- Overflow protection and pauses if somehow boxes do overflow (should never happen in normal usage, just an unload protection)
- Slice enabled lamps in footprint :3
## Considerations
- Does not handle non-boxes, empty boxes or mixed boxes
- Boxes with the same signal strength but different fill level will be randomly selected to be merged (doesnt benefit from a box comparer)
- Input pairs at the same time to both chests
## Notes
By Lukeem and Kurisu with the help of Wisperingtoyou, Carrie, Tisunfortunate and ComfyBiha.
## Compatibility
1.19+

## Resources
- [MG005_1x_Merger.litematic](attachments/MG005_1x_Merger.litematic): MC 1.21.4, Size 28x10x22 blocks
  - Contains all 4 versions of the merger
