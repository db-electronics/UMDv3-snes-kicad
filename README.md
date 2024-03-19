# UMDv3 Super Nintendo Cartridge adapter
The [Universal Mega Dumper v3](https://github.com/db-electronics/UMDv3) project is an open-source solution for cartridge dumping and writing. 

This PCB interfaces a Super Nintendo cartridge to the UMDv3. The [UMDv3 Main PCB](https://github.com/db-electronics/UMDv3-kicad) detects which cartridge adapter is currently connected by reading an ID byte on the I2C bus provided by an MCP23008. The Super Nintendo ID is 0x03.

# Project
Please refer to the [UMDv3 Firmware Project Repository](https://github.com/db-electronics/UMDv3) for UMDv3 documentation and instructions; this is the project's central repository and where the wiki is hosted.

# Dependencies
## Parts Libraries
All components in this PCB depend on [my KiCad libraries](https://github.com/db-electronics/kicadlib) which are available here on github. I don't use any pre-existing libraries - *fight me*.
