# Getting Started with AutoPlay

Autoplay - tool for mobile automation testing like "usual" tools like appium, seetest, etc. But with one big different, AutoPlay can automate Unreal Engine, Unity applications using Selenium.

Contact: autoplay.automation@gmail.com
YouTube: [link](https://www.youtube.com/channel/UCPcmYGu6pLjxujNuLI9KVtg)

# Prepare environment!

## Android 

 -  Setup you env and android from Unreal Engine [guide](https://docs.unrealengine.com/en-us/Platforms/Android/GettingStarted)
-  Make sure JDK is installed and added to you PATH. Just try execute "*adb*" in console. (You should achieve it in previous step).If AutoPlay not find any local install of Android SDK, he will try to use embedded version from AutoPlay/ThirdParty folder.

## IOS
- Install xCode and run it first time
- Install usbmuxd - in terminal "*brew install usbmuxd*"
- Install ios-deploy lib. How to install read [this](https://github.com/ios-control/ios-deploy).

Note: After connect iOS device first time – run xCode to link symbols for you device. (to avoid problems with ios-deploy)

# Start Using AutoPlay

 - Connect device with USB cable. (Make sure USB debugging activated and allowed for Android, And "Trust" for iOS activated)
 - Run AutoPlay (use shortcut "Run_Win_Autoplay.bat" for win or “Run_Mac_Autoplay” for mac)
 - Select platform iOS or Android
 - Open device selector and select device
 ![enter image description here](https://github.com/AutoplayAutomation/AutoPlay/blob/master/Documentation/img/main.png)
 - Select Application file (with plugin) ([UE_PLUGIN](https://github.com/AutoplayAutomation/UE4_AutoPlay_Plugin))
 - Click start and then click inspector button
 - Wait for game install/run
 - Inspector should be opened. Of course if everything is ok ;)
![enter image description here](https://github.com/AutoplayAutomation/AutoPlay/blob/master/Documentation/img/inspector.png)

