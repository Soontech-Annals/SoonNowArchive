# MAUD Splitter
<img alt="area_render_11_.png" src="images/area_render_11_.png?raw=1" height="300px">

**Authors:** *JayRoi, Dashie*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1573176255677730877)

A compact, niche splitter.
## Features
- 6-wide, 11-tall, 2wt slice with Unstackable separation
- Distribution hopper locking
- Can be paused for as little as 6gt, with a generous gap required before repeated pauses
- Completely latch-less
## Considerations
- There is no in-slice readout for empty-box availability. Boxes with small amounts of many item types are a known edge case that can break the splitter, though this has never occurred naturally with even high-variance survival boxes.
- Pausing too frequently can increase the probability of the system running out of boxes.
- Pausing for 4gt can cause the system to pause indefinitely, including when the control runs out of boxes.
- When pausing, suddenly empty shulker boxes can break and despawn. Very rarely, one can replace the token item in the kissing hoppers. This is possible on every globally clocked splitter.
## Instructions
1. If the system pauses indefinitely (only possible depending on how the user sets up the box distribution externally), pause and unpause it to fix the issue.
2. Use an empty box as the shuffling unstackable in the kissing hoppers to ensure that, if a suddenly empty box replaces it, the system outputs an empty box for every non-empty box input, (though it will not be the same box).
## Notes
Tested for millions of ticks in all directions and mirrored; also tested with thousands of Hermitcraft boxes using random pausing, both with a generous delay between pauses and with pauses as low as 6gt (the latter using an infinite box supply in each slice).
## Compatibility
Tested in 26.3

## Resources
- [SG004_Maud_Splitter_1.0.litematic](attachments/SG004_Maud_Splitter_1.0.litematic): MC 26.3, Size 21x11x6 blocks
