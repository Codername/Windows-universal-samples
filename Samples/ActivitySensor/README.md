<!---
  category: DevicesSensorsAndPower
--->

# Activity detection sensor sample

This sample demonstrates the use of the Windows.Devices.Sensors.ActivitySensor API.

This sample allows the user to interact with the activity detection functionality on the system. You can choose one of four scenarios:

-   Current activity
-   History
-   Events
-   Background activity

### Current activity

Gets the default activity sensor and displays the current activity.

### History

Gets the activity history from at most 1 day ago. Displays the first entry, last entry, and count of entries.

### Events

Subscribes to reading changed events and displays the updated activity reading.

### Background activity

Registers a background task for activity changes. The background task runs whenever the most likely activity changes to/from any of the subscribed activities.

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

