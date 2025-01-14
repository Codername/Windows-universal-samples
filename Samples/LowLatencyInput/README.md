<!---
  category: CustomUserInteractions
---!>

# Low latency input sample

This sample shows how to handle input on a dedicated input thread to achieve lowest input latency. 

Specifically, this sample shows:

1. Setting up two rectangles, one rendered using DirectX and one using XAML
2. Using a SwapChainPanel embedded in a XAML app to render and draw DirectX content
3. Achieving lowest input latency by setting up a dedicated input thread using swapChainPanel->CreateCoreIndependentInputSource(CoreInputDeviceTypes::Mouse | CoreInputDeviceTypes::Touch | CoreInputDeviceTypes::Pen);
4. Achieving lowest output latency using Waitable Back Buffers
5. Artificially blocking the UI thread to show the XAML rect rendering choppy and the DirectX rect rendering smooth and unaffected

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[Waitable Back Buffers](https://msdn.microsoft.com/en-us/library/windows/apps/dn448914.aspx)

[DirectX and XAML](https://msdn.microsoft.com/en-us/library/windows/apps/hh825871.aspx)

[Creating an dedicated input thread](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.swapchainpanel.createcoreindependentinputsource.aspx)


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
