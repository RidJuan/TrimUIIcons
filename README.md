# TrimUI Custom Icons

Custom device icons for the TrimUI Brick (TG3040) that display when connecting the microSD card to a PC.

![TrimUI Brick Icon Preview](assets/example.png)

## Overview

This repository contains custom device icons for the TrimUI Brick *(other devices coming soon)*. When you insert your TrimUI Device's microSD card into a PC, these icons will make it easily identifiable in file explorer with a custom device icon instead of the default generic drive icon.

## Contents

- `Colour.ico` - Themed TrimUI device icon (32x32 to 256x256)
- `autorun.inf` - Configuration file for Windows icon display
- `Stock` - .png images of the devices

## Installation

1. Navigate to `TrimUI Icons\Brick\Colour` folder
2. Copy both the `.ico` file and `autorun.inf` from this folder to your device's microSD card root directory
3. Edit `autorun.inf` in your preferred text editor:

   ```ini
   [autorun]
   icon = Black.ico
   label = MinUI Brick
   ```
   *Note: Change `MinUI Brick` to your preferred display name for the microSD card*

4. Save the `autorun.inf` file
5. When you reinsert the microSD card, it should now display the custom icon

## Compatibility

- Windows 10/11
- TrimUI Brick (TG3040)
- TrimUI Smart Pro (TG5040) - *Coming Soon*

## Support

If you encounter any issues or have suggestions, please open an issue in this repository.
