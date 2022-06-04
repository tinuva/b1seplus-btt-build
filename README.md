# B1SEPlus BTT firmware build

![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)
[![GitHub Actions][actions-shield]][actions]
[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]

![GitHub Stars][stars-shield]
![GitHub Watchers][watchers-shield]
![GitHub Forks][forks-shield]

## About

This is based on the work from [frealmyr/marlin-build](https://github.com/frealmyr/marlin-build) - Many thanks go out to frealmyr for making this so much easier!

This repository builds marlin firmware for the B1SEPlus 3d printer from the main marlin firmware in BTT mode. 

## Details

The marlin tree is sourced from [bigtreetech/BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware](https://github.com/bigtreetech/BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware) from the B1-SE-SKR2(2.6.0).rar file.
The file was extracted and the git files updated to upload to [tinuva/B1-SE-SKR2](https://github.com/tinuva/B1-SE-SKR2) which is used as the source by this repository.

## Flashing your printer

* collect the firmware.bin from this repository
* collect the TFT35 folder from [BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware/BTT-mode/TFT35](https://github.com/bigtreetech/BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware/BTT-mode/TFT35)
* place the firmware.bin and TFT35 folder on a sd-card to update your printer

[tinuva]: https://github.com/tinuva
[commits-shield]: https://img.shields.io/github/commit-activity/y/tinuva/b1seplus-btt-build
Public.svg
[commits]: https://github.com/tinuva/b1seplus-btt-build
Public/commits/master
[contributors]: https://github.com/tinuva/b1seplus-btt-build
Public/graphs/contributors
[actions-shield]: https://github.com/tinuva/b1seplus-btt-build
Public/workflows/Home%20Assistant%20CI/badge.svg
[actions]: https://github.com/tinuva/b1seplus-btt-build
Public/actions
[issue]: https://github.com/tinuva/b1seplus-btt-build
Public/issues
[license-shield]: https://img.shields.io/github/license/tinuva/b1seplus-btt-build
Public.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/tinuva/b1seplus-btt-build
Public.svg
[stars-shield]: https://img.shields.io/github/stars/tinuva/b1seplus-btt-build
Public.svg?style=social&label=Stars
[forks-shield]: https://img.shields.io/github/forks/tinuva/b1seplus-btt-build
Public.svg?style=social&label=Forks
[watchers-shield]: https://img.shields.io/github/watchers/tinuva/b1seplus-btt-build
Public.svg?style=social&label=Watchers