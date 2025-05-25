# jakub_kozlowicz/cosmos

![jakub_kozlowicz/cosmos](imgur.com image replace me!)

*A short description of the keyboard/project*

* Keyboard Maintainer: [Jakub Kozlowicz](https://github.com/jakub-kozlowicz)
* Hardware Supported: Waveshare RP2040 Zero
* Hardware Availability: [Waveshare RP2040 Zero](https://www.waveshare.com/wiki/RP2040-Zero)

Make example for this keyboard (after setting up your build environment):

    make jakub_kozlowicz/cosmos:default

Flashing example for this keyboard:

    make jakub_kozlowicz/cosmos:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) (*left half*) or (6,5) (*right half*) in the matrix (top left/right corner of the keyboard) while plugging in the USB cable.
* **Physical reset button**: Briefly press the button with the label `RESET` on the PCB
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
