# MonsGeek M7

A 65% keyboard with per-key RGB lighting.

* Keyboard Maintainer: [jonylee1986](https://github.com/jonylee1986)
* Hardware Supported: MonsGeek M7
* Hardware Availability: [MonsGeek](https://www.monsgeek.com/)

Make example for this keyboard (after setting up your build environment):

    make monsgeek/m7:default
    make monsgeek/m7:vial

Flashing example for this keyboard:

    make monsgeek/m7:default:flash
    make monsgeek/m7:vial:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available

