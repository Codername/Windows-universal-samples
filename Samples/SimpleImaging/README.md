<!---
  category: AudioVideoAndCamera
--->

# Simple imaging sample

This sample demonstrates some common imaging scenarios for Universal Windows apps including metadata and editing/saving.

Specifically, this sample demonstrates how to:

- Read, process and edit common image metadata and properties including:
  - EXIF orientation
  - Author, title, and keywords
  - Geotags
- Perform scaling and rotation while respecting EXIF orientation
- Optimize image saving

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Sample contents

### C# version

- **Scenario1.xaml**, **Scenario1.xaml.cs**: Use the property system APIs (Windows.Storage.FileProperties) to read and edit bitmap properties from an image.
- **Scenario2.xaml**, **Scenario2.xaml.cs**: Use the imaging APIs (Windows.Graphics.Imaging) to read and edit bitmap properties and apply transformations such as scale, crop and rotate.
- **Helpers.cs**: Helper functionality including handling/converting EXIF orientation values.

All other files provide common SDK sample functionality.

### JS version

- **css\scenario1.css**, **html\scenario1.html**, **js\scenario1.js**: Use the property system APIs (Windows.Storage.FileProperties) to read and edit bitmap properties from an image.
- **css\scenario2.css**, **html\scenario2.html**, **js\scenario2.js**: Use the imaging APIs (Windows.Graphics.Imaging) to read and edit bitmap properties and apply transformations such as scale, crop and rotate.
- **js\helpers.cs**: Helper functionality including handling/converting EXIF orientation values.

All other files provide common SDK sample functionality.

## Related topics

- [**Windows.Storage**](http://msdn.microsoft.com/library/windows/apps/br227346)
- [**Windows.Graphics.Imaging**](http://msdn.microsoft.com/library/windows/apps/br226400)

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