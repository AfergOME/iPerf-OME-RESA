# iPerf-OME-RESA
Here is an app to optimize the testing process for OME-RESA when using iPerf.

The "iPerf-OME-RESA.exe" is a simple executable that, when run, will check if iPerf is installed on your machine. It does this by going to your Downloads folder for your user and checking if there is a folder that is named "iPerf" there. Even if you have iPerf installed somewhere else, or even if you have it in your downloads but it is not named “iPerf," it will not see it. If it does not see it, it will download the latest version as of 07/11/2025 and store it at C:/Users/yourname/Downloads/iPerf. 

After the download is complete, or it confirms the file is there beforehand, the application will run the tests that we need to confirm the circuit upgrade was successful. This will include 2 5-minute tests, one of which will test the download, the other will test the upload. These results will be printed to the desktop in the form of a .txt file. After you run this test, please forward that file to OME-RESA in the ticket you have open. 

If you have any questions, please feel free to reach out to anyone here at OME-RESA, and we will be sure to help you.
- Aiden Ferguson
