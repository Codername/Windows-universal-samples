<!---
  category: CustomUserInteractions
---!>

# Basic input sample

This sample shows how to handle input in Universal Windows Apps.

Specifically, this sample shows how to:

- **Listen for events on XAML elements:** Use events on XAML elements to listen for various types of input, such as pointer pressed / released, pointer enter / exited, tap / double-tap, and right-tap / press-and-hold.
- **Retrieve properties about a pointer object:** Use a PointerPoint object to retrieve information common to all pointers (such as X/Y coordinates) as well as information specific to the type of input being used (such as mouse wheel information).
- **Query input capabilities for the system:** Use the KeyboardCapabilities, MouseCapabilities, and TouchCapabilities classes to determine what types of input are available on the current system.
- **Manipulate a XAML element:** Use the ManipulationMode property to register for specific manipulation events on XAML elements and react to them in order to move and rotate the element.
- **Manipulate an object using a GestureRecognizer:** Use an instance of a GestureRecognizer to move and rotate an object. This is useful if your app uses its own framework and, thus, cannot use the manipulation events on XAML elements.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[PointerPoint](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.input.pointerpoint.aspx)

[KeyboardCapabilities](https://msdn.microsoft.com/en-us/library/windows/apps/windows.devices.input.keyboardcapabilities.aspx)

[MouseCapabilities](https://msdn.microsoft.com/en-us/library/windows/apps/windows.devices.input.mousecapabilities.aspx)

[TouchCapabilities](https://msdn.microsoft.com/en-us/library/windows/apps/windows.devices.input.touchcapabilities.aspx)

[ManipulationMode](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.manipulationmode.aspx)

[GestureRecognizer](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.input.gesturerecognizer.aspx)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Insider Preview

**Phone:**  Windows 10

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
