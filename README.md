# DriverQualcomm

Qualcomm UEFI drivers and related files

## About

This repository contains UEFI DXE drivers applications and configuration files for Qualcomm platforms
It is for firmware development research and reverse engineering

## Contents

* AdcDxe.efi ADC driver
* ChargerExDxe.efi Charger driver
* PmicDxe.efi PMIC driver
* QcomBds.efi Qualcomm BDS driver
* QcomChargerApp.efi Charger UEFI application
* QcomChargerDxeLA.efi Charger DXE driver
* SPMI.efi SPMI bus driver
* TsensDxe.efi Temperature sensor driver
* ULogDxe.efi UEFI logging driver
* UsbPwrCtrlDxe.efi USB power control driver
* BDS_Menu.cfg uefiplat.cfg QcomChargerCfg.cfg Configuration files
* xbl.img.dump.7z XBL image dump
* Some drivers include c source and asm disassembly files

## Usage

These files are for UEFI firmware development and testing
Use only on devices you own or are authorized to modify

## Notes

No warranty
Some files may be device specific or incomplete
Check compatibility before flashing

## License

No license specified
