# Crain Decoder Heads with 3-bit pre demuxing
<img alt="area_render.png" src="images/area_render.png?raw=1" height="300px">

**Authors:** *Augment🎄Mendo*

**Tags:** *Tested & Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1446524380988313710)

Augment's latch-based demuxers
## Features
- Works by shifting a CUD sequence to enable deserialising
- Uses dropper latches for 0 code and piston latches for 1 code
- Can have 3 block gap between your decoders/silos
- Requires resetting latches after pre-demuxing
- Can add an extra'restock' bit to restock
## Instructions
- After pasting the schem, please `//update `once

## Resources
- [DC001_Augment_Crain_Decoder_Heads_with_3-bit_latch_demuxers.litematic](attachments/DC001_Augment_Crain_Decoder_Heads_with_3-bit_latch_demuxers.litematic): MC 1.21.4, Size 90x11x16 blocks
