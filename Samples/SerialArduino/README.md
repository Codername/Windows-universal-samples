﻿<!---
  category: DevicesSensorsAndPower
--->

# Serial Arduino sample

This sample demonstrates the use of the Windows.Devices.SerialCommunication WinRT APIs to communicate with an Arduino device.

This sample allows the user to configure and communicate with an Arduino board that has simple wired circuitry consisting of 4 LEDs and a temperature sensor. This sample demonstrates the following

-   Connect/Disconnect using Device Selection list
-   Communicating with the Arduino board and toggle the LEDs and get readings from the temperature sensor.

**Connect/Disconnect using Device Selection list**

When the application starts, a list of available matching Arduino devices is displayed along with options to Connect/Disconnect to/from a selected device.

**LED/Temperature**

This scenario demonstrates the use of Input and Output streams on the SerialDevice object in order to communicate with the Serial device specifically to toggle the four LEDs and get temperature readings from the temperature sensor.

## Hardware requirements

Any Arduino board with a header that can be used to wire up the simple circuit of LEDs and the temperature sensor. The Arduino uses a custom sketch that goes along with the sample and is included in the sketch folder as SerialCommand.ino.

The wiring diagram is also provided as SerialCommand.fzz can be opened with Fritzing application. (Download at http://Fritzing.org)

## Operating system requirements

**Client:** Windows 10

**Server:** Windows 10

**Phone:** Windows 10

## Build and Deploy the sketch 

1. Install the Arduino IDE.
2. Open the SerialCommand.ino sketch.
3. Compile and deploy the sketch to the Arduino device.

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

To run this sample after building it, press F5 (run with debugging enabled) or Ctrl+F5 (run without debugging enabled) from Visual Studio. (Or select the corresponding options from the Debug menu.)
