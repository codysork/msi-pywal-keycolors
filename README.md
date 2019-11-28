# msi-xresources
A script for coordinating your MSI keyboard's LEDs with your Xresources color scheme.

## Requirements

- <a href="https://github.com/Askannz/msi-perkeyrgb">msi-perkeyrgb</a>

## Setup

- Edit the keycolors script and add your MSI keyboard model in the variable MSI_KEYBOARD_MODEL="..."
  Example: 
  ```MSI_KEYBOARD_MODEL="ge73"```
- Edit the X_RESOURCES_COLOR variable and choose which color from your Xresource file you will be loading to your keyboard
  Example: 
  ```X_RESOURCES_COLOR_NUM=8```
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
