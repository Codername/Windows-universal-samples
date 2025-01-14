<!---
  category: ControlsLayoutAndText
--->

# Drag and drop sample

This sample shows how to enable Drag and Drop in a XAML Application.

Specifically, this sample shows how to:

- **Enable Drag and Drop of ListView items** ListView's Drag and Drop allows dropping information in the ListView, dragging items from a ListView to other targets (any kind of UIElement) or reordering items within the ListView. This sample shows a sample implementation of a ListView using all this features to allow the user to create a list of items entirely with Drag and Drop.
- **Customize the Drag and Drop UI** Both the source of a UIElement's Drag and Drop and the target of a Drag and Drop can customize the appearance of the Drag and Drop UI. This sample illustrates the different options for such customization.
- **Start Drag and Drop programmatically** UIElement's StartDragAsync allows a finer control of a Drag and Drop operation such as the gesture which triggers it or its possible cancellation. This sample shows how to call StartDragAsync and how to cancel the resulting Drag and Drop operation.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

<!-- Add links to related API -->

[ListViewBase.CanDragItems](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.listviewbase.candragitems.aspx)
[ListViewBase.CanReorderItems](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.listviewbase.canreorderitems.aspx)
[ListViewBase.DragItemsStarting](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.listviewbase.dragitemsstarting.aspx)
[ListViewBase.DragItemsCompleted](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.listviewbase.dragitemscompleted.aspx)
[DragItemsStartingEventArgs](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.controls.dragitemsstartingeventargs.aspx)
[UIElement.AllowDrop](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.allowdrop.aspx)
[UIElement.StartDragAsync](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.startdragasync.aspx)
[UIElement.DragStarting](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.dragstarting.aspx)
[UIElement.DragEnter](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.dragenter.aspx)
[UIElement.DragLeave](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.dragleave.aspx)
[UIElement.Drop](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.uielement.drop.aspx)
[DragStartingEventArgs](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.dragstartingeventargs.aspx)
[DragEventArgs](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.drageventargs.aspx)
[DragUI](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.dragui.aspx)
[DragUIOverride](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.draguioverride.aspx)
[DragOperationDeferral](https://msdn.microsoft.com/en-us/library/windows/apps/windows.ui.xaml.dragoperationdeferral.aspx)


## System requirements

**Client:** Windows 10 Technical Preview

**Server:** Windows 10 Technical Preview

**Phone:**  Windows 10 Technical Preview

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
