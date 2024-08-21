# monterey_k101

<!-- ![monterey_k101](imgur.com image replace me!) -->

A retrofit project for the [Monterey K101/K102](https://deskthority.net/wiki/Monterey_K101) AT keyboards.
This should be fine for IBM Model M keyboards, which should share the same [matrix layout](https://sharktastica.co.uk/sims/matrix?kb=enhanced#Sim) (except for the missing key between left ctrl and left alt).

* Keyboard Maintainer: [giuliof](https://github.com/giuliof)
* Hardware Supported: WIP, I have retrofitted just one PCB of the two I have
* Hardware Availability: this is a retrofit project for old keyboards, just check if your keyboard shares the same matrix.

Make example for this keyboard (after setting up your build environment):

    make monterey_k101:default

Flashing example for this keyboard:

    make monterey_k101:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader by **Bootmagic reset**: Hold down the Escape key at (7,2) in the matrix and plug in the keyboard.
