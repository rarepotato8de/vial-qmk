# jonphilmitch/doppelganger

![jonphilmitch/doppelganger](https://img001.prntscr.com/file/img001/dpi4Dpv1SgGtsoEZXYmYww.png)

*A short description of the keyboard/project*

* Keyboard Maintainer: [RarePotato8DE](https://github.com/RarePotato8DE)
* Hardware Supported: Doppelganger 65% PCB
* Hardware Availability: *Not available at the moment*

Make example for this keyboard (after setting up your build environment):

    make jonphilmitch/doppelganger:default

Flashing example for this keyboard:

    make jonphilmitch/doppelganger:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 2 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
