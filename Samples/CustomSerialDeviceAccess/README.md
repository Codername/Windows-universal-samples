<!---
  category: DevicesSensorsAndPower
--->

# Custom serial device sample

This sample demonstrates the use of the Windows.Devices.SerialCommunication WinRT APIs to communicate with a Serial device.

This sample allows the user to configure and communicate with a Serial device. You can choose one of four scenarios:

-   Connect/Disconnect using Device Selection list
-   Configure the Serial device
-   Communicate with the Serial device
-   Register for Events on the Serial device

**Connect/Disconnect using Device Selection list**

When the application starts, a list of available Serial devices matching the search criterion specified by the application is displayer along with options to Connect/Disconnect to/from a selected device.

**Configure the Serial device**

This scenario demonstrates the use of various Get/Set property APIs in order to query for/alter Serial device properties such as Baud Rate, Stop Bits etc.

**Communicate with the Serial device**

This scenario demonstrates the use of Input and Output streams on the SerialDevice object in order to communicate with the Serial device.

**Register for Events on the Serial device**

This scenario demonstrates the use of event notification APIs provided by Windows.Devices.SerialCommunication for **Pin Changed** and **Error Received** event types.

## Operating system requirements

**Client:** Windows 10

**Server:** Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

To run this sample after building it, press F5 (run with debugging enabled) or Ctrl+F5 (run without debugging enabled) from Visual Studio. (Or select the corresponding options from the Debug menu.)
