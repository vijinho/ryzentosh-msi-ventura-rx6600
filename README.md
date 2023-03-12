# Ryzentosh EFI for Monteray/Ventura with AMD Radeon RX 6600/6800 and MSI B450/X470 Triple Booting

This is built on the work of many others, too numerous to mention, thanks to all, and I am sharing this back with the community. It is on a system shared with Windows 10, Linux PopOS (using BTRFS filesystem).

## Hardware tested

- MSI motherboards B450 Gaming Plus Max, X470 Gaming Plus Max, B450 Mortar Max M (with Resize Bar/Above 4G Enabled)
- CPUs: Ryzen 5 5600G, Ryzen 7 3700X, Ryzen 5 5600X
- Graphics Cards: AMD RX 6600, AMD RX 6800

## Notes

- `config.plist` is excluded, you need to copy one of `ryzen6core.plist` or `ryzen8core.plist` and replace the asterisks with generated valid ROM etc values
- Power monitoring app can be added from Truly Spinach [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor) but the kernel files are included already.

## Help

Don't create issues asking, but do send patches and pull requests for improvements! For self-help. refer to:

- [OpenCore Configurator ](]https://mackie100projects.altervista.org/)
- [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- https://github.com/mikigal/ryzen-hackintosh
- [Github Ryzentoshers](https://github.com/topics/ryzen-hackintosh)