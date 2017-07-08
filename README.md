# gForce Scratch Extension

## Overview
The gForce Scratch Extension is for using the gForce Embedded Suite with the
`mBlock` Scratch programming IDE.

## Usage
1. Import the gForce Scratch Extension

    Copy the directory containing gForce Scratch Extension to `%APPDATA%\com.makeblock.Scratch3.4.6\Local Store\mBlock\libraries`.

2. Enable the gForce Scratch Extension

    Open the IDE, and check menu item `Extensions -> gForce`.

3. Run the example

    * Turn on the `mBot` robot, and connect it to your PC through USB cable.
      Make sure that a corresponding serial port appears by checking the
      `Device Manager`.

    * In the IDE, connect to the `mBot` robot through the IDE by checking the
      `Connect -> Serial -> COMX` menu item.

    * In the IDE, select the `File -> Load Project` menu item, and open one
      example project located in the `example` directory. The program block
      diagram should be displayed.

    * In the IDE, check the `Edit -> Arduino Mode` menu item to open the Arduino
      programming window. Click the `Upload to Arduino` button to compile the
      project and upload the generated program image to the `mBot` robot.

    * You will be able to use the gForce to control the `mBot` robot following
      your programming logic. You can unplug the USB cable at the time.

## License
Please refer to [LICENSE.md](LICENSE.md)
