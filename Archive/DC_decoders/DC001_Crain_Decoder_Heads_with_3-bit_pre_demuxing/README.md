# Crain Decoder Heads with 3-bit pre demuxing
**Authors:** *AugmentMendo*

**Tags:** *Tested & Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1446388112589852733)

Augment's latch-based demuxers
## Features
- Works by shifting a CUD sequence to enable deserialising
- Uses dropper latches for 0 code and piston latches for 1 code
- Can have 3 block gap between your decoders/silos
- Requires resetting latches after pre-demuxing
- Can add an extra'restock' bit to restock
## Instructions
- After pasting the schem, please `//update `once
