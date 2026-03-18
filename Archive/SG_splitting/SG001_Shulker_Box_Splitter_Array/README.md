# Shulker Box Splitter Array
<img alt="area_render_20_.png" src="images/area_render_20_.png?raw=1" height="300px">

**Authors:** *Basil, Kizu*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1483704575818207302)

A compact shulker box splitter array that can split mixed item shulker boxes into smaller boxes of the same type. The design uses the hopper dueling mechanism for a "filter itemless" setup. It uses a global clock to allow for it to be paused during operation.
## Features
- Compact design. 20x17x7
- Seperate output for unstackable items.
- Fully hopperlocked.
- Filter itemless. (kissing/dueling hoppers)
- Pausable. Will only break sorted boxes if running.
- Automatic refill of empty boxes.
- Will ensure empty boxes are present before starting and will pause if empty boxes run out.
## Considerations
- Not empty box input proof. Do not input empty boxes.
## Notes
Inspired by Obi's design.

## Resources
- [SG001_Compact_Shulker_Box_Splitter_Array.litematic](attachments/SG001_Compact_Shulker_Box_Splitter_Array.litematic): MC 1.21.4, Size 20x17x7 blocks
