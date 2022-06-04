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

This is based on the work from https://github.com/frealmyr/marlin-build - Many thanks go out to frealmyr for making this so much easier!

This repository builds marlin firmware for the B1SEPlus 3d printer from the main marlin firmware in BTT mode. 

## Details

The marlin tree is sourced from https://github.com/bigtreetech/BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware from the B1-SE-SKR2(2.6.0).rar file.
The file was extracted and the git files updated to upload to https://github.com/tinuva/B1-SE-SKR2 which is used as the source by this repository.

## Flashing your printer

* collect the firmware.bin from this repository
* collect the TFT35 folder from https://github.com/bigtreetech/BIQU-B1-SE-PLUS/tree/master/B1-SE-PLUS%20firmware/BTT-mode/TFT35
* place the firmware.bin and TFT35 folder on a sd-card to update your printer