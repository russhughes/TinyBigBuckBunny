# Tiny Big Buck Bunny

![Image](160x120/0114.jpg)

https://youtu.be/CzSlI6xayL4


The program sequentially reads, decodes and displays each frame from individual
JPG's stored on a SD Card.  Since my device does not have enough RAM to hold
a full sized 320x240 uncompressed image (153600 bytes) I reduced the
frame size to 160x120 (38400 bytes).

The program requires the use of the driver from https://github.com/russhughes/ili9342c_mpy
and [Peter Hinch's](https://github.com/peterhinch) modified SDCard.py driver.
The SDCard driver allows both the Display and a SD Card share the same SPI port,
it is included in the lib folder.

This is not a serious attempt to play a movie on the M5Stack it's just a test
of the display drivers JPG code.

"Big Buck Bunny" (c) copyright 2008, Blender Foundation / www.bigbuckbunny.org
