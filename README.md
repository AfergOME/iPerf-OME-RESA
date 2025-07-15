# iPerf-OME-RESA
Here is an app to optimize the testing process for OME-RESA when using iPerf.

When first trying to run this app, Windows Defender will likely try to prevent you from running it as it is not signed with Microsoft as a recognized app. This is fine, you just need to allow the app to run when Defender pops up. 

The "iPerf-OME-RESA.exe" is a simple executable that, when run, will check if iPerf is installed on your machine. It does this by going to your Downloads folder for your user and checking if there is a folder that is named "iPerf" there. Even if you have iPerf installed somewhere else, or even if you have it in your downloads but it is not named “iPerf," it will not see it. If it does not see it, it will download the latest version as of 07/11/2025 and store it at C:/Users/yourname/Downloads/iPerf. 

After the download is complete, or it confirms the file is there beforehand, the application will run the tests that we need to confirm the circuit upgrade was successful. This will include 2 5-minute tests, one of which will test the download, the other will test the upload. These results will be printed to the desktop in the form of a .txt file. After you run this test, please forward that file to OME-RESA in the ticket you have open. 

If you have any questions, please feel free to reach out to anyone here at OME-RESA, and we will be sure to help you.

# iPerf-OME-RESA MacOS
The Mac version is very similar as it will check if you have iperf3 installed to your machine but, to do this homebrew is required. The app will ask you if you would like to install homebrew as it is required for this process to work. After that the tests will begin. These tests are silent and there will be no GUI to show the tests running. Instead, a popup window will appear telling you what is happening. These will disappear when the tests complete. After all the tests are done, the app will let you know that it has completed and the .txt will be placed in your Downloads folder. You will simply need to upload that .txt to your active ticket with OME-RESA.
