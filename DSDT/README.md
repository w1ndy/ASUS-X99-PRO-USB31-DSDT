# ACPI DSDT

* dsdt.dsl: Source code
* dsdt.aml: Compiled DSDT
* [MaciASL](https://bitbucket.org/RehabMan/os-x-maciasl-patchmatic/downloads/): DSDT editor and compiler

Compiled DSDT should be placed under ``EFI:/EFI/CLOVER/ACPI/patched/dsdt.aml``.

## Changelog

* Patched to remove all errors and warnings
* Applied [the fix for Broadcom BCM94360CD BT/WIFI](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-ARPT.aml)
* Applied [the fix for on-board Intel i218-V 1GB NIC controlller](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-ETH0.aml)
* Applied [the fix for on-board AHCI SATA controller](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-SAT1.aml) and [another for EVSS](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-EVSS.aml)
* Applied [the fix for USB 3.0 controller](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-XHCI.aml)
* Applied [the fix for USB 3.1 controller](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-XHC2.aml)
* Applied [the fix for USB power errors](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-X99-USBX.aml)
* Applied [the DTGP fix](https://github.com/KGP/X99-System-SSDTs/blob/master/SSDT-DTPG.aml)

## References

* [KGP's SSDT fixes for X99](https://github.com/KGP/X99-System-SSDTs)
* [KGP's guide on extending iMac to X99](https://www.tonymacx86.com/threads/how-to-extend-the-imac-pro-to-x99-successful-build-extended-guide.227001/)
* [Guide on fixing DSDT errors and warnings on X99](https://www.insanelymac.com/forum/topic/313296-guide-mac-osx-1012-and-1013-with-x99-broadwell-e-family-and-haswell-e-family/?page=41)

