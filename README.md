# msi-xresources
A script for coordinating your MSI keyboard's LEDs with your pywal color scheme.

## Requirements

- [pywal](https://github.com/dylanaraps/pywal)
- [msi-perkeyrgb](https://github.com/Askannz/msi-perkeyrgb")

## Setup

- Edit the keycolors script and add your MSI keyboard model.
  
  Example: ```MSI_MODEL="ge73"```
- Edit the X_RESOURCES_COLOR variable and choose which color from your pywal configuration you will be loading to your keyboard. This script accepts any integer from 0 to 15.
  
  Example:```X_RESOURCES_COLOR_NUM=8```
- Run in your terminal:
  ```
  chmod +x keycolors 
  ```

## Usage

Enter in your terminal:
```
./keycolors
```
or
```
sh keycolors
```

### Using with pywal

```
wal -i PATH/TO/WALLPAPER -o /PATH/TO/keycolors
```

See: <a href="https://github.com/dylanaraps/pywal">pywal</a>
