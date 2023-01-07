# My QMK Firmware

## The changes from original firmware

* Enable features
    * Mouse Keys
* Bind some keys
    * Bind INSERT to "Home"
    * Bind Fn-I to "INSERT"
    * Bind Fn-Del to "Change RGB effect mode"
    * Bind Fn-Ctrl to "CapsLock to Left Ctrl"
    * Bind Fn-Caps to "CapsLock to CapsLock"
    * Bind Fn-M(ac) to "Swap GUI and Left Alt"
    * Bind Fn-W(indow) to "Unswap GUI and Left Alt"
    * Bind Fn-Up to "Huration Increase"
    * Bind Fn-Down to "Huration Decrease"
    * Bind Fn-Left to "Saturation Decrease"
    * Bind Fn-Right to "Saturation Increase"
    * Bind Fn-, to "Mouse Cursor Left"
    * Bind Fn-. to "Mouse Cursor Down"
    * Bind Fn-/ to "Mouse Cursor Right"
    * Bind Fn-l to "Mouse Curosr Up"
    * Bind Fn-; to "Mouse Scroll Up"
    * Bind Fn-' to "Mouse Croll Down"
    * Bind Fn-[ to "Mouse Button1"
    * Bind Fn-] to "Mouse Button2"
* Change the default RGB mode
    * default mode: MULTISPLASH
    * brightness: max
    * saturation: 168(range 0~255)


[![Current Version](https://img.shields.io/github/tag/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/tags)
[![Discord](https://img.shields.io/discord/440868230475677696.svg)](https://discord.gg/Uq7gcHh)
[![Docs Status](https://img.shields.io/badge/docs-ready-orange.svg)](https://docs.qmk.fm)
[![GitHub contributors](https://img.shields.io/github/contributors/qmk/qmk_firmware.svg)](https://github.com/qmk/qmk_firmware/pulse/monthly)
[![GitHub forks](https://img.shields.io/github/forks/qmk/qmk_firmware.svg?style=social&label=Fork)](https://github.com/qmk/qmk_firmware/)

This is a keyboard firmware based on the [tmk\_keyboard firmware](https://github.com/tmk/tmk_keyboard) with some useful features for Atmel AVR and ARM controllers, and more specifically, the [OLKB product line](https://olkb.com), the [ErgoDox EZ](https://ergodox-ez.com) keyboard, and the [Clueboard product line](https://clueboard.co).

## Documentation

* [See the official documentation on docs.qmk.fm](https://docs.qmk.fm)

The docs are powered by [Docsify](https://docsify.js.org/) and hosted on [GitHub](/docs/). They are also viewable offline; see [Previewing the Documentation](https://docs.qmk.fm/#/contributing?id=previewing-the-documentation) for more details.

You can request changes by making a fork and opening a [pull request](https://github.com/qmk/qmk_firmware/pulls), or by clicking the "Edit this page" link at the bottom of any page.

## Supported Keyboards

* [Planck](/keyboards/planck/)
* [Preonic](/keyboards/preonic/)
* [ErgoDox EZ](/keyboards/ergodox_ez/)
* [Clueboard](/keyboards/clueboard/)
* [Cluepad](/keyboards/clueboard/17/)
* [Atreus](/keyboards/atreus/)

The project also includes community support for [lots of other keyboards](/keyboards/).

## Maintainers

QMK is developed and maintained by Jack Humbert of OLKB with contributions from the community, and of course, [Hasu](https://github.com/tmk). The OLKB product firmwares are maintained by [Jack Humbert](https://github.com/jackhumbert), the Ergodox EZ by [ZSA Technology Labs](https://github.com/zsa), the Clueboard by [Zach White](https://github.com/skullydazed), and the Atreus by [Phil Hagelberg](https://github.com/technomancy).

## Official Website

[qmk.fm](https://qmk.fm) is the official website of QMK, where you can find links to this page, the documentation, and the keyboards supported by QMK.
