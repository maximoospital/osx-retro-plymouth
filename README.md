# OSX Retro Plymouth Theme

Mac OS X Pre-Yosemite Plymouth theme. Based on mintyMac's, upgraded it to remove deprecated apis, expand the animation and use the actual apple logo.
I'll add a screenshot whenever i take one, okk?

## Installation

1. Clone or download this repository.
2. Copy the `osx-retro-plymouth` directory to `/usr/share/plymouth/themes/`:
   ```
   sudo cp -r osx-retro-plymouth /usr/share/plymouth/themes/
   ```
3. Set the theme as default:
   ```
   sudo plymouth-set-default-theme osx-retro-plymouth
   ```
4. Update the initramfs:
   ```
   sudo update-initramfs -u
   ```

## Credits

Based on the [mintyMac Plymouth theme](https://store.kde.org/p/1101956/) from KDE Store.
