# Clover Configuration

* config.plist: Clover configuration file (/EFI/CLOVER/config.plist)
* [Clover Configurator](https://www.tonymacx86.com/resources/clover-configurator.335/): Configuration editor and EFI mounter

> WARNING: SMBIOS information is incomplete, please generate one with Clover Configurator. See [this thread](https://www.reddit.com/r/hackintosh/comments/7v8fh2/how_to_fix_imessage_facetime/).

## Drivers
> Put these drivers to /EFI/CLOVER/drivers64UEFI.

* ApfsDriverLoader-64.efi
* AppleImageLoader-64.efi
* AptioMemoryFix-64.efi
* DataHubDxe-64.efi
* FSInject-64.efi
* SMCHelper-64.efi
* VBoxHfs-64.efi

## Kexts
> Put these kexts to /EFI/CLOVER/kexts/Other.

* AGPMEnabler.kext
* AirportBrcmFixup.kext
* AppleALC.kext (Use 1 for layout ID)
* CodecCommander.kext
* FakeSMC.kext
* IntelMausiEthernet.kext
* Lilu.kext
* WhateverGreen.kext


## References

* [KGP's guide on extending iMac to X99](https://www.tonymacx86.com/threads/how-to-extend-the-imac-pro-to-x99-successful-build-extended-guide.227001/)
* [KGP's EFI folder for X99](https://github.com/KGP/X99-EFI-Folder-Distributions)

