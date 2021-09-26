# Elegoo Neptune 2 firmware source code 🔱
This is the firmware source code that Elegoo support provided for me when I asked after some of the Marlin features that where not turned on in the stock version.

It seems that it is not 100% stock as the TFT images and options are different, however it does complie and run on the MKS Robin Nano main board that the printer uses.

This project is not completed. Here is a todo list.

# Todo:
* Create video explaining both build options

# Building

## Option 1 - Github actions
Github are kind enough to provide unlimited compute to open source public projects, I have written an action to build and upload a copy of the firmware in this repo to use it follow the below procedure.

### Requirements
1. Github account

### Process
1. Fork this repo
2. Edit any settings you want in the firmware, you can do this by pressing the period key (.) in your browser when you have your forked repo open
3. Stage, Commit and Push your changes
4. Go to the actions tab in your forked repo
5. Watch the build finish 🤞
6. Download the firmware in a zip file from the artifacts
7. Place the firmware files on a SD card
8. Insert the SD card into the printer and reset it

## Option 2 - Local build

### Requirements
1. Git
2. Vscode
3. PlatformIo extension
4. Marlin Auto Build extension

### Process
1. Fork this repo
2. Clone your new repo locally using git
3. Edit any setting you want in the firmware
4. Use the Marlin auto build extension to build the firmware
5. Watch the build finish 🤞
6. Rename the firmware to elegoo.bin
7. Place the firmware files on a SD card
8. Insert the SD card into the printer and reset it

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/manniefesto)