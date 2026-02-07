# Dual Sided 6 Bit Binary Decoder
<img alt="dualdecoder.png" src="images/dualdecoder.png?raw=1" height="300px">

**Authors:** *floppydonkey*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1469544937115746405)

This decoder takes six bits and outputs a pulse at one of 64 slices corresponding to the code. The device is dual sided, meaning it can output a signal to one of two different sides. This effectively adds another bit to the decoder, allowing for 128 different outputs.
## Features
- Dual sided outputs.
- Signal travels 100 blocks per second.
- No 1gt offset needed. This is achieved through a combination of TTP to get the proper update order, and some rail diodes.
- Minimal flashing rails. QC based logic with BUDed rails.
- Hopperspeed throughput.

## Resources
- [DC005_Dual_Sided_6_Bit_Binary_Decoder_1.17.litematic](attachments/DC005_Dual_Sided_6_Bit_Binary_Decoder_1.17.litematic): MC 1.17.1, Size 68x8x13 blocks
- [DC005_Dual_Sided_6_Bit_Binary_Decoder.pdf](attachments/DC005_Dual_Sided_6_Bit_Binary_Decoder.pdf): application/pdf
