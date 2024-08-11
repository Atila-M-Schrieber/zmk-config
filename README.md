# Atila's zmk-config

### Table of contents
- Branches
    - [TOTEM](#totem)
- [Dongle Flashing](#dongle-flashing)
- [ZMK Keymap Editor](#zmk-keymap-editor)
- [Documentation](#documentation)

## Hello

This is a fork of eiga's zmk-config, but I'm just using it for my dongled [TOTEM-PLUS-1](https://github.com/Atila-M-Schrieber/TOTEM-Plus-1/tree/main) build

This repository hosts zmk-configs for my keyboard project(s)

Additionally, this repository contains alternative configurations meant to be used with an extra controller acting as a dongle. Pease refer to the [Dongle Flashing](https://github.com/eigatech/zmk-config#dongle-flashing) chapter for instructions.

## TOTEM

- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)

## Dongle Flashing

Dongle configs use Seeed Xiao Ble microcontrollers housed in a nifty 3D printed [case](https://www.printables.com/model/522586-seeed-xiao-ble-case).

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file.
4. Flash the first half with the the `settings_reset` file.
5. Flash the first half with the `left` or `right` files.
6. Repeat steps 4 and 5 for the other half.

> [!WARNING]
> When using both Nice!Nano and Seeed XIAO microcontrollers, make sure you are flashing them with the correct files!

## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

## Documentation

- [ZMK Firmware Documentation](https://zmk.dev/docs)
- [Eren's Wireless Charybdis Mini Guide](https://github.com/erenatas/charybdis-wireless-3x6)
