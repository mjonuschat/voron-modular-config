# Modular Voron Configuration Template

## Summary

This repository contains a modular configuration template for Voron 3D printers.
It's currently being used as a base for a Voron 2.4r2 (350mm³), a Trident
(300mm³) and a Tri-Zero Plus50 (165mm³).

## Usage

The repository root is at `~/printer_data` and everything else in this
repository is expecting this as the root. It's easiest to use on a fresh
install. From there check the [printer.cfg](config/printer.cfg) to enable (or
disable) features. Some options are configurable in
[variables.cfg](config/config/variables.cfg) and some parameters need to be
directly set in the respective hardware-specific configuration snippets.

### Warning

This configuration is specific to my printers and the way I use them. **DO NOT**
run this config without at least having read and understood every file that is
being included, starting at `printer.cfg`.

## Acknowledgments

* AndrewEllis93 - [v2.247 config](https://github.com/AndrewEllis93/v2.247_backup_klipper_config)
* Alex Zellner - [V2.660 config](https://github.com/zellneralex/klipper_config)
* Félix Boisselier - [Generic Klipper Config](https://github.com/Frix-x/klipper-voron-V2)
