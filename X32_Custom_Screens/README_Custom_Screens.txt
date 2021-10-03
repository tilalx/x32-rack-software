Firmware 4.02 - configuration of custom Lock- and Boot-Screen.
 
To use a custom screen an image file needs to be stored on the root-directory of an USB-Drive.
Since the files can not be copied to the internal memory, this function is only working when a USB-Drive is inserted.
If the images don't match the listed criteria, the default boot/lock screens will be shown.
If the images are smaller than indicated, they will be centred on the screen.
While the Boot-Screen can use any 8-Bit index mode colour palette, the Lock-Screen needs a dedicated palette. This palette can be imported from the attached image.


CustomBoot.bmp:
- Must be named CustomBoot.bmp
- Located at the root of the USB drive
- Bitmap only (.bmp)
- 8 bit indexed mode (not rgb)
- Maximum size : 799 x 399 px
- Minimum size : 10 x 10 px
- Colours : 256 max (no particular color palette)
          - background color will be 1st colour in customboot.bmp palette
          - boot text color will be 2nd colour of the palette 

CustomLock.bmp:
- Must be named CustomLock.bmp
- Located at the root of the USB drive
- Bitmap only (.bmp)
- 8 bit indexed mode (not rgb)
- Maximum size : 799 x 399 px
- Minimum size : 10 x 10 px
- Colours : use colour palette embedded of the attached image.
           - don't change the order of the colours
           - use dithering if you want a smooth image

[Images in the Examples-Folder can be used for testing]