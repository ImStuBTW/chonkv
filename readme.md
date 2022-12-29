# ChonkV

![ChonkV PCB Render](./PNG-Render.png)

The ChonkV is a 58 key choc keyboard based off Brickbot's excellent [chocV](https://github.com/brickbots/chocV) keyboard. It adds a number row, an additional outer column, and thumb keys in the style of the [Atreus keyboard](https://shop.keyboard.io/products/keyboardio-atreus).

This keyboard was designed largely as a way of learning the [Ergogen](https://docs.ergogen.xyz) keyboard layout generator software. I was pretty happy with my previous keyboard, the split Sofle Choc, but this new keyboard design allowed me to test a variety of concepts I'd been curious about experimenting with. The ChonkV has the same 58 key count as the Sofle Choc, but its unibody design makes it a bit more portable. This board also has true Choc spacing, and is my first time working with the Nice!Nano wireless microcontroller. While it's not a true ortholinear block, this is my first time dabbling with a board that drops the usual column stagger.

There's a few existing board designs that also may have checked these boxes. The keyboard community has putting out several interesting Reviung variants, and the Atreus also comes close to this design. I've always liked the look of the chocV however, and wanted to try my own spin at the design. This board's not nearly as smol, but I like it. It's chonky. It's a chonky chocV. The ChonkV.

## Features

* Kailh Choc v1 Switches.
* Supports through-hole switch sholdering or Kailh Choc hotswap sockets.
* Choc switch spacing. (Has been bested with MBK keycaps.)
* Designed for the Nice!Nano wireless Microcontroller.
* Also supports the Nice!View display. (Nice!View requires an additional wire to be run from the display's CS pin to one of the Nice!Nano's extra internal pins.)
* JST battery connector.
* RST pushbutton.
* Physical power switch.
* Includes designs for a Horizon/ChocV style PCB backplate as well as a more traditional 3D printed case.

## This Is A Work In Progress

I haven't sent this keyboard off for manufacturing just yet! In case you stumbled upon this on Github, take these designs with a grain of salt. Just an FYI, this is using as a reference to learn Ergogen, this library leverages Ergogen 3, and several custom footprints that can be found in [my fork](https://github.com/ImStuartJones/ergogen). Ergogen 4 made several breaking changes to the syntax in December of 2022, so make sure you check which version you're using.