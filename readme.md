# README for Tiny-B3-CAPE
A BeagleBone Black with additional cape is used as hardware for:

   * [TinyES3](https://github.com/emb4fun/tinyes3)
   * [TinyELCA](https://github.com/emb4fun/tinyelca)
   * [TinyONE](https://github.com/emb4fun/tinyone)
   
The BeagleBone Black is configured to start from a connected SPI-Flash. 
The SPI-Flash and an additional DUO-Led are located on the corresponding
cape. The actual program is stored on the SD card and is loaded and started
by the bootloader in the SPI flash. 
