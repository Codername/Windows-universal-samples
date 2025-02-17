<!---
  category: ControlsLayoutAndText 
--->

# Splash screen sample

This sample shows how to imitate the splash screen that Windows displays for your app by positioning a similar image correctly when Windows dismisses the splash screen that it displays. This sample uses the [**SplashScreen**](http://msdn.microsoft.com/library/windows/apps/br224763) class in the [**Windows.ApplicationModel.Activation**](http://msdn.microsoft.com/library/windows/apps/br224766) namespace.

Note  This sample was created using one of the universal app templates available in Visual Studio. It shows how its solution is structured so it can run on both Windows 8.1 and Windows Phone 8.1. For more info about how to build apps that target Windows and Windows Phone with Visual Studio, see [**Build apps that target Windows and Windows Phone 8.1 by using Visual Studio**](http://msdn.microsoft.com/library/windows/apps/dn609832).

This sample demonstrates these tasks:

-   Responding when the splash screen dismissed event fires
-   Extending the splash screen

Important APIs in this sample include:

-   JavaScript: [**onactivated**](http://msdn.microsoft.com/library/windows/apps/br212679) event
-   C#/C++/VB: [**Activated**](http://msdn.microsoft.com/library/windows/apps/br225018) event 
-   [**SplashScreen**](http://msdn.microsoft.com/library/windows/apps/br224763) class

To obtain an insider copy of Windows 10, go to [Windows 10](http://insider.windows.com). 

**Note**  For Windows 10 app samples, go to  [Windows 10 Samples](https://github.com/Microsoft/Windows-universal-samples). The samples for Windows 10 can be built and run using Windows developer [tools](https://developer.windows.com).

## Related topics

### Reference
For more info about the concepts and APIs demonstrated in this sample, see these topics:

- [Windows 8 app samples](http://go.microsoft.com/fwlink/p/?LinkID=227694)
- [Adding a splash screen (Windows Runtime apps using JavaScript and HTML)](http://msdn.microsoft.com/library/windows/apps/hh465332) 
- [Adding a splash screen (Windows Runtime apps using C#/VB/C++ and XAML)](http://msdn.microsoft.com/library/windows/apps/hh465331) 

### Related samples
- [App activate and suspend using WinJS sample](http://go.microsoft.com/fwlink/p/?linkid=231617)
- [App activated, resume, and suspend using the WRL sample](http://go.microsoft.com/fwlink/p/?linkid=231474)

### Related technologies
- [Windows.ApplicationModel.Activation.SplashScreen class](http://msdn.microsoft.com/library/windows/apps/br224763)

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
