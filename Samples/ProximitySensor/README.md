﻿<!---
  category: DevicesSensorsAndPower
--->

# Proximity sensor sample

This sample demonstrates the use of the Windows.Devices.Sensors.ProximitySensor API.

This sample allows the user to view the proximity detection reading as a boolean value. You can choose one of three scenarios:

-   Proximity sensor data events
-   Polling proximity sensor readings
-   Proximity Monitoring to Turn the Display On or Off

**Proximity Sensor Data Events**

When you choose the Enable button for the **Data Events** option, the app will begin displaying proximity sensor detection readings in real time.

**Polling Proximity Sensor Readings**

When you choose the Get Data button for the **Polling** option, the app will retrieve the current sensor readings.

**Proximity Monitoring to Turn the Display On or Off**

When you choose the Enable button for the **Display On/Off** option, the app will request the system to monitor the proximity sensor detection state to automatically turn the display on or off.

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10

## Build the sample

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

## Run the sample

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

### Deploying the sample

- Select Build > Deploy Solution. 

### Deploying and running the sample

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or selectDebug > Start Without Debugging. 
