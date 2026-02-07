# Parallelized Encoded Chest Hall
<img alt="chesthall.png" src="images/chesthall.png?raw=1" height="300px">

**Authors:** *Andrews54757*

**Tags:** *Broken*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1469539291913916478)

A fully hopperlocked 10 item per slice encoded chest hall with a backend sporting up to 20x HS parallelization. It is able to insert both loose items and boxes into chests allowing for item/box hybrid functionality.
## Features
- 800 chests, 10 chests per slice with 24 blocks of width
- Fully parallelizable (19x hopperspeed for items, 1x hopperspeed for box insertion)
- 100% hopperlocked with sectional unlocking
- 10/8 gt streamed comparator outputs
- Self-repairable toggle states with Auto-Fix sequence
- Low active lag, +1 ms at 1x HS, +6 ms at 20x HS
## Considerations
- The transport mechanism for this hall does not support overflow protection. Extra items may despawn.
- It is recommended that the comparator readouts are used to limit the insertion amounts as needed to prevent overflow.
## Notes
- Comparator readouts are streamed from the chests at 10 codes / 8 gt. This is initiated by a pulsed signal.
- All toggle states are self-repairable. The repair process is initiated by a pulsed signal.
## Compatibility
Broken in 1.21+ due to item movement changes.

## Resources
- [CH002_encoded_chest_hall_p30.litematic](attachments/CH002_encoded_chest_hall_p30.litematic): MC 1.18.2, Size 24x91x108 blocks
- [CH002_Parallelized_Encoded_Chest_Hall.pdf](attachments/CH002_Parallelized_Encoded_Chest_Hall.pdf): application/pdf
