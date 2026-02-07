# Streamable Bit RAM
<img alt="sram.png" src="images/sram.png?raw=1" height="300px">

**Authors:** *Andrews54757*

**Tags:** *Functional*

**Original post:** [View on Discord](https://discord.com/channels/1325008017015701504/1469542088336211980)

A RAM module that stores 1600 bits of data in locked repeaters. Each bit is addressable through three 4-bit inputs. It is able to stream all of its stored data such that one bit is outputted per level every 4gt-8gt.
## Features
- Constant time writes to individually addressable bits.
- RAM contents can be streamed at a certain rate.
- Matrix decoding addresses memory modules individually to reduce lag.
## Considerations
- Very laggy when streaming out the data.
## Notes
Includes a 600 bit variant

## Other Images
<img src="images/invs.png?raw=1" height="300px">

## Resources
- [DS001_600_bit_ram.litematic](attachments/DS001_600_bit_ram.litematic): MC 1.18.2, Size 36x32x36 blocks
- [DS001_1600_bit_RAM_p1.litematic](attachments/DS001_1600_bit_RAM_p1.litematic): MC 1.17.1, Size 50x32x50 blocks
- [DS001_Streamable_Bit_RAM.pdf](attachments/DS001_Streamable_Bit_RAM.pdf): application/pdf
