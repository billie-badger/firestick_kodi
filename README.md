# firestick_kodi

Automate the process of adding Kodi to your Amazon Fire TV Stick.

This script is for Windows OS. Other OS coming soon.

First, download Android Debug Bridge from https://developer.android.com/studio/command-line/adb.html

Put the sdk wherever you like.

Second, download Kodi apk from Kodi.tv/download or clone or download from this repo and place it in the platform-tools folder in your sdk.

Hold SHIFT and RIGHT-CLICK the platform-tools folder

Select Open Command Window here -- You are now ready to connect to your Firestick.. We need some information from it to do so.

Leave the command line open and...

Turn on your Firestick and go to SETTINGS --> DEVICE --> DEVELOPER OPTIONS

Turn ADB Debugging "ON" and Unknown Sources "OFF"

Go back to DEVICE --> NETWORK and locate your IP Address (ex: "192.000.0.1")

Open the Firestick.bat file with any text editor and...

Plug in your IP address to the IP address area 

Save.

Remember that command line terminal we had open?

Drag the Firestick.bat file into that window and hit ENTER!

If you have followed the steps, ADB will now connect to your Firestick and download KODI.






