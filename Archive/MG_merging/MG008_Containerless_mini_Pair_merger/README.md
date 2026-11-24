# Containerless mini Pair merger
<img alt="image.png" src="images/image.png?raw=1" height="300px">

**Authors:** *Lukeem, Caribous*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1574738895499829341)

Combines two boxes of the same item type into one bigger box.
## Features
- Can handle full boxes.
- Uses 3 hoppers per slice.
- Has a footprint of 8x5.
- Requires no containers to be filled during construction.
## Instructions
1. Use an external pair comparer in order to speed up merging
2. Don't input boxes at too close intervals (a normal whitelisting temp is plenty slow enough)
3. Needs a fill level sorter to sort out the output.
## Notes
Expanding it to more than 4 slices requires a stream using magma blocks. Watch Jayroi's video on mergers to understand how it works.
## Compatibility
1.19+ due to water stream changes

## Resources
- [MG008_Containerless_Mini_Merger.litematic](attachments/MG008_Containerless_Mini_Merger.litematic): MC 1.21.11, Size 6x8x14 blocks
  - Fixed 1 container having boxes from a previous test and added signs to tell you which box goes where
- [MG008_Remote_Pair_Comparer.litematic](attachments/MG008_Remote_Pair_Comparer.litematic): MC 1.21.11, Size 6x6x9 blocks
  - Pair comparer that can be placed anywhere and connected to the merger by using the item lifetime. Bigger box is always first.
