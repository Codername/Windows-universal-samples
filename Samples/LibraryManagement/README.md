<!---
  category: FilesFoldersAndLibraries
--->

# Library management sample

Demonstrates how to get a list of the folders in a user's library and how to let users add and remove folders from that list. This samples uses [**Windows.Storage**](http://msdn.microsoft.com/library/windows/apps/br227346).[**StorageLibrary**](http://msdn.microsoft.com/library/windows/apps/dn251722).

The sample demonstrates these tasks:

1.  **Add a folder to a library**

    Uses [**StorageLibrary.GetLibraryAsync**](http://msdn.microsoft.com/library/windows/apps/dn251725) to get a specific library and [**StorageLibrary.RequestAddFolderAsync**](http://msdn.microsoft.com/library/windows/apps/dn251726) to display a file picker that the user can use to select a folder to add to the library.

2.  **List the folders in a library**

    Uses [**StorageLibrary.GetLibraryAsync**](http://msdn.microsoft.com/library/windows/apps/dn251725) to get a specific library and [**StorageLibrary.Folders**](http://msdn.microsoft.com/library/windows/apps/dn251724) to get a list of folders in the library.

3.  **Remove a folder from a library**

    Uses [**StorageLibrary.GetLibraryAsync**](http://msdn.microsoft.com/library/windows/apps/dn251725) to get a specific library and [**StorageLibrary.Folders**](http://msdn.microsoft.com/library/windows/apps/dn251724) to display a list of folders in the library so the user can select one to remove. Then uses [**StorageLibrary.RequestRemoveFolderAsync**](http://msdn.microsoft.com/library/windows/apps/dn251727) to remove the folder if the user approves.

**Note** The Windows universal samples require Visual Studio 2015 to build and Windows 10 to execute.
 
To obtain information about Windows 10, go to [Windows 10](http://go.microsoft.com/fwlink/?LinkID=532421)

To obtain information about Microsoft Visual Studio 2015 and the tools for developing Windows apps, go to [Visual Studio 2015](http://go.microsoft.com/fwlink/?LinkID=532422)

## Related topics

### Reference

[**Windows.Storage**](http://msdn.microsoft.com/library/windows/apps/br227346)

## System requirements

**Client:** Windows 10

**Server:** Windows Server 2016 Technical Preview

**Phone:** Windows 10. Note that you will not be able to add or remove folders from the library.

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
