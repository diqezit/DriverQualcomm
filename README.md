# DriverQualcomm

Qualcomm UEFI drivers and related files

## About

This repository contains UEFI DXE drivers applications and configuration
files for Qualcomm platforms
It is for firmware development research and reverse engineering

## Structure

    Drivers/    UEFI DXE drivers and applications
    Config/     platform configuration and provisioning files
    Dumps/      captured firmware and bootloader archives

## Drivers

* AdcDxe ADC driver
* ChargerExDxe Charger driver
* PmicDxe PMIC driver
* QcomBds Qualcomm BDS driver
* QcomChargerApp Charger UEFI application
* QcomChargerDxeLA Charger DXE driver
* SPMI SPMI bus driver
* TsensDxe Temperature sensor driver
* ULogDxe UEFI logging driver
* UsbPwrCtrlDxe USB power control driver

Some drivers come with C source and ASM disassembly next to the EFI binary

## Config

* BDS_Menu.cfg BDS menu layout
* QcomChargerCfg.cfg charger configuration
* uefiplat.cfg platform configuration
* BATTERY.PROVISION battery provisioning data

## Dumps

* audio.7z audio subsystem firmware dump
* xbl.img.dump.7z XBL bootloader image dump

Extract archives locally before use, extraction folder is in gitignore

## Usage

These files are for UEFI firmware development and testing
Use only on devices you own or are authorized to modify

## Notes

No warranty
Some files may be device specific or incomplete
Check compatibility before flashing

## License

No license specified