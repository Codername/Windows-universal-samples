﻿<!---
  category: IdentitySecurityAndEncryption
--->

# User information sample

This sample obtains information about the users on the computer.

Specifically, this sample demonstrates the following scenarios:

- How to find all users with [the `FindAllAsync` method](https://msdn.microsoft.com/library/windows/apps/windows.system.user.findallasync.aspx).
- How to retrieve a specific user property with [the `GetPropertyAsync` method](https://msdn.microsoft.com/library/windows/apps/windows.system.user.getpropertyasync.aspx).
- How to retrieve multiple user properties with [the `GetPropertiesAsync` method](https://msdn.microsoft.com/library/windows/apps/windows.system.user.getpropertiesasync.aspx).
- How to obtain the profile picture for a user with [the `GetPictureAsync` method](https://msdn.microsoft.com/library/windows/apps/windows.system.user.getpictureasync.aspx).
- How to monitor users dynamically with [the `CreateWatcher` method](https://msdn.microsoft.com/library/windows/apps/windows.system.user.createwatcher.aspx).

**Note** The Universal Windows app samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[**Windows.System.UserProfile** namespace](http://msdn.microsoft.com/library/windows/apps/br241881)

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

- To debug the sample and then run it, press F5 or select Debug >  Start Debugging. To run the sample without debugging, press Ctrl+F5 or select Debug > Start Without Debugging. 

