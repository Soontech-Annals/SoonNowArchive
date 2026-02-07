# Parallelized Encoded Chest Hall Using Discs
<img alt="pic.png" src="images/pic.png?raw=1" height="300px">

**Authors:** *JayRoi*

**Tags:** *Untested*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1469540681457602671)

This is a demonstrative prototype of a parallelized unloading logic inspired by Andrews54757's chest hall (See [CH002 Parallelized Encoded Chest Hall](https://discord.com/channels/1325008017015701504/1469539291913916478)). However, the system is designed to be more compact and efficient by using discs to encode the chest locations instead of embedded redstone memory.
## Features
- 540 chests, 10 chests per slice.
- 25 block wide slices.
- Fully parallelizable (10x hopperspeed for items, 1x hopperspeed for box insertion)
- 100% hopperlocked with sectional unlocking
- Self-repairable toggle states with Auto-Fix sequence
## Instructions
1. Ensure the 8gt stabilizer is on, it is below the UI signified with a gold block.
2. Insert the code box, the unloading box, and any additional boxes to be directly inserted.
3. Make sure not to send any additional orders until the lamp indicates the system is ready.
4. Next to the gold block/8gt stabilizer are noteblocks to depreciate the SS values determining the unloading amount. The clocks for these are not present as the system is incomplete.
5. When the system is done, the chest-hall slices will not relock themselves as this feature is not completed, so click the locking button (on-top the doors) twice to turn the system off. Note: In practice, this noteblock can be clicked once every so often while the system is running to reduce lag.
## Notes
The first box of the order should be full with 3 or 4 music discs. The first 3 discs encode the address in the hall, and the fourth is used to determine how much of the box to unload (higher SS disc = more items). 
The second box will be unloaded (if chosen), and any additional boxes will be directly sent to the address.
To the right of the UI, there is a labeled lever to directly insert boxes of unstackable items, rather than unloading them. Note: The hall cannot unload unstackables at a separate rate than 16 or 64 stackables. 
Under this lever, there is a noteblock which will let you bypass unloading and directly insert the first box into the address.
## Compatibility
Minecraft 1.16+

## Resources
- [CH003_Parallelized_Encoded_Chest_Hall_Using_Discs.litematic](attachments/CH003_Parallelized_Encoded_Chest_Hall_Using_Discs.litematic): MC 1.20.1, Size 25x71x65 blocks
- [CH003_Parallelized_Encoded_Chest_Hall_Using_Discs.pdf](attachments/CH003_Parallelized_Encoded_Chest_Hall_Using_Discs.pdf): application/pdf
