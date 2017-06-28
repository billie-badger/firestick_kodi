# firestick_kodi

Automate the process of adding Kodi to your Amazon Fire TV Stick.

This script is for Windows OS. Other OS coming soon.

First, download Android Debug Bridge from https://developer.android.com/studio/command-line/adb.html

Put the sdk wherever you like.

Second, download Kodi apk from Kodi.tv/download by
clicking the android icon and clicking ARMV7A(32-bit)
and place the apk file in the platform-tools folder in your sdk.

Hold SHIFT and RIGHT-CLICK the platform-tools folder

Select Open Command Window here -- You are now ready to connect to your Firestick.. We need some information from it to do so.

Leave the command line open and...

Turn on your Firestick and go to SETTINGS --> DEVICE --> DEVELOPER OPTIONS

Turn ADB Debugging "ON" and Unknown Sources "ON"

Go back to DEVICE --> NETWORK and locate your IP Address (ex: "192.000.0.1")

Open the Firestick.bat file with any text editor and...

Copy the location of your platform-tools into the Firestick.bat file (To find this, look at the command line terminal [ex:C:\Users\ME\Desktop\Droid\platform-tools])

Plug in your IP address to the IP address area 

Save.

Remember that command line terminal we had open in the platform-tools directory?

Drag the Firestick.bat file into that window and hit ENTER!

If you have followed the steps, ADB will now connect to your Firestick and download KODI.

Now you can find Kodi in your applications on the Firestick.

(If you don't see it immediately, go to SETTINGS --> APPLICATIONS --> MANAGE MY APPLICATIONS --> KODI

At this point you can install your favorite media applications from repositories on Kodi

I recommend: http://www.wirelesshack.org/how-to-install-kodi-israel-repository-kodi-17-krypton.html

ENJOY!!








