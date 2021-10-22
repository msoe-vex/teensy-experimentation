# Teensy Experimentation

This repository is used to manage test and experiment code for the Teensy 4.1 Development Boards, before transitioning the work to actual projects.


## Getting Started

### Teensy 4.1
Information about the Teensy 4.1 boards can be found here: https://www.pjrc.com/store/teensy41.html. This includes information on the hardware, as well as all communication channels available to use on the device.

We are primarily using the Teensy 4.1 due to a combination of the cheaper board cost, large amount of CPU compute power, and the broad range of communication options available on the board.

### PlatformIO
Our development on this project will be done entirely within VSCode. To support uploading to the Teensy boards (and all other Arduino-compatible boards), install the **PlatformIO Extension** (*platformio.platformio-ide*). This extension provides broad support for most microprocessor boards, and will add these features to VSCode.

More information about this extension can be found here: https://docs.platformio.org/en/stable//integration/ide/vscode.html#installation

### Installing Required Tooling
To install the Teensy platform required to write and install software on the device, open the PlatformIO menu on the left side of the screen. Under "PIO Home", go into the "Boards" menu.

To get the packages required to develop on the Teensy, we need to add the *Teensy Platform*. To do this, go under the "Platforms" menu on the side, enter the "Embedded" sub-menu, and search for "Teensy". Once installed, the "Teensy" package should show up under the "Installed" menu to the left of the "Embedded" menu.

### Creating New Projects
To create a new Teensy project, open the PlatformIO menu on the left side of the screen. Under "PIO Home", go to the "Projects & Configuration" menu. In here, press "Create New Project", select a project name, and change the "Board" option to be **Teensy 4.1**. This will take some time, but will create the required project files needed to upload to the board.

**WARNING: If you are creating a project for a PRE-EXISTING repository, you need to change the project location, and name the project the same as your repository folter. This will ensure that all files end up correctly formatted within your repository without additional work needing to be done to move files!**

## Building and Uploading Projects
When working with PlatformIO, all of the primary build and upload commands will be done from the Platform IO menu located in the icon tray on the left side of the screen. Once you have your required project open, you can find "Build" and "Upload" options under the "Project Tasks" menu located in the top of the sub-menu.

If you do not see this menu, you may need to **Add an Existing Project** from the "Projects & Configuration" menu.

## Additional Resources

Additional guides can be found below:

https://forum.pjrc.com/threads/66674-Tutorial-How-to-use-PlatformIO-Visual-Code-Studio-for-Teensy

