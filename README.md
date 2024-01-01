# Chatter 2.0 Test 1

My first program for my Chatter 2.0

For this I'm mostly just trying to figure out how to use the hardware.

## Handy Links

[Community post with link to schematic and other usefull info](https://community.circuitmess.com/t/chatter-schematics/4726)

[Schematic image included in this repo](Chatter2Sch.jpeg)

How on earth do you pick a board in Platform IO? Obviously there is no board definition for chatter pre-existing, and there's no "generic wroom 32" option. It's hard to even find what Espressif boards use the wroom-32, especially since it's discontinued. [This form post](https://community.platformio.org/t/esp32-board-selection/17331/2) was really helpful, it reccomended the “Espressif ESP32 Dev Module”, which is what I used for this project.

[WROOM 32 Pinout](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2018/08/esp32-pinout-chip-ESP-WROOM-32.png?quality=100&strip=all&ssl=1). This isn't necessary, since the schematic has the IO pin numbers on it already, but it can be nice to see the other pin functions maybe?

[Using non-standard pins when setting up SPI on ESP32](https://randomnerdtutorials.com/esp32-spi-communication-arduino/#custom-spi-pins)

### Circuit Mess

[Chatter 2 Firmware](https://github.com/CircuitMess/Chatter2-Firmware/tree/master) The firmware shipped on the devices, presumably. Appears to be Arduino IDE? Shudder.

[Chatter 2 Library](https://github.com/CircuitMess/Chatter2-Library/tree/master) Used by the firmware, has handy things like pin definitions.

[Circuit OS](https://github.com/CircuitMess/CircuitOS) Core OS and library used by the firmware.

### RadioLib

[Repo Wiki Basics, including instructions for non-standard SPI](https://github.com/jgromes/RadioLib/wiki/Basics)

[LLCC68 Class Reference](https://jgromes.github.io/RadioLib/class_l_l_c_c68.html)

[Module Class Reference](https://jgromes.github.io/RadioLib/class_module.html)

[Status Codes Reference](https://jgromes.github.io/RadioLib/group__status__codes.html)
