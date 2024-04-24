# OrcaSlicer-to-Ender3S1-thumbnails
This is the working script that generates embedded gcode thumbnails for Ender3 S1 with latest firmware in the Orca Slicer.
[Original script](https://forum.creality.com/t/ender-3s1-pro-thumbnail-preview-not-working/4960/21)
![Resulting image of Ender3 display](/ender_thumbnail.webp)
## Installing
There are two options.
### Executable file (no-Python)
- Take the [executable folder](/exe) and unzip it to C:\Users\[your_name]\AppData\Roaming\OrcaSlicer
- Write the full path with commas to the thumbnailgen.exe in the Orca “Post-processing Script” field
- Make sure that you have correct Printer Settings:
  - G-code flavor - Marlin 2
  - G-code thumbnails - 300x300
  - Format of thumbnails - JPEG
### Python script
- Install Python.
- Install Pillow.
- Take the .py script and place it here C:\Users\[your_name]\AppData\Roaming\OrcaSlicer
- Write the full pathes with commas to the script and your Python installation in the Orca “Post-processing Script” field
- Make sure that you have correct Printer Settings:
  - G-code flavor - Marlin 2
  - G-code thumbnails - 300x300
  - Format of thumbnails - JPEG
Now this script will work every time when you export the gcode.