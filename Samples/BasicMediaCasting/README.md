﻿<!---
  category: AudioVideoAndCamera
--->

# Basic media casting sample

This sample shows how to use the APIs in the **Windows.Media.Casting** namespace to render media on a remote device.  It covers sending media to various devices- Miracast, DLNA, and Bluetooth.  For more advanced functionality see the *Advanced Casting Sample*.

**Scenario 1: Basic Media Casting:**
Press the *Load Video* button to open a video.  Press the *Cast* button under the progress bar in the video element.  Select the device you'd like to cast to.

This is an example of the built in casting that comes with the media element transport controls.  This will enable casting to Miracast, DLNA, and Bluetooth devices.

**Scenario 2: Casting Using Casting Picker:**  
Again, press the *Load Video* Button.  Then press the *Cast Button* to it's right.  Finally select the device you'd like to cast to.

Very similar to the first sample, but this one allows you to further customize the device picker. 

**Scenario 3: Casting Using Custom Picker**  
Again, press the *Load Video* Button.  Then press the *Start Device Watcher*.  Finally select a device from the list that appears below.

This sample illustrates how to build a completely custom UX for selecting devices.  It uses the casting APIs in conjunctions with the **Windows.Devices.Enumeration** APIs.

Related topics
--------------

[Windows.Media.Casting namespace](https://msdn.microsoft.com/en-us/library/windows/apps/windows.media.casting.aspx)
[Windows.Devices.Enumeration namespace](https://msdn.microsoft.com/en-us/library/windows/apps/windows.devices.enumeration.aspx)

System requirements
-----------------------------

Client:
Windows 10  
Windows Phone 10  

Build the sample
----------------

1. If you download the samples ZIP, be sure to unzip the entire archive, not just the folder with the sample you want to build. 
2. Start Microsoft Visual Studio 2015 and select **File** \> **Open** \> **Project/Solution**.
3. Starting in the folder where you unzipped the samples, go to the Samples subfolder, then the subfolder for this specific sample, then the subfolder for your preferred language (C++, C#, or JavaScript). Double-click the Visual Studio 2015 Solution (.sln) file.
4. Press Ctrl+Shift+B, or select **Build** \> **Build Solution**.

Run the sample
--------------

The next steps depend on whether you just want to deploy the sample or you want to both deploy and run it.

**Deploying the sample**
1.  Select **Build** \> **Deploy Solution**.

**Deploying and running the sample**
1.  To debug the sample and then run it, press F5 or select **Debug** \> **Start Debugging**. To run the sample without debugging, press Ctrl+F5 or select**Debug** \> **Start Without Debugging**.