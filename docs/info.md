<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The design now use user input 0 and 1 to change the "speed" of the vga image by adding different values to the counter. User input 1 will make it appear as it is going to x2 speed, user input 2 will make it appear as it is going to x6 speed.

## How to test

Start the vga ouput by connect a screen and try to set to '1' user input 1. Then deassert user input 1 and set user input 2 to '1'. This should make the image goes first to x2 speed and then to x6 speed.

## External hardware

VGA monitor, swiches or buttons.
