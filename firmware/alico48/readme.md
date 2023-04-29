# alico48

![alico48](imgur.com image replace me!)

The Alico48 is a split keyboard that uses only one ProMicro.

* Keyboard Maintainer: [marby](https://github.com/marby3)
* Hardware Supported: Alico48 PCB, ProMicro
* Hardware Availability: *Links to where you can find this hardware*l

Make example for this keyboard (after setting up your build environment):

    make alico48:default

Flashing example for this keyboard:

    make alico48:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `RESET` if it is available
