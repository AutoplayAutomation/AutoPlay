# Getting Started with AutoPlay

Autoplay - tool for mobile automation testing like "usual" tools like appium, seetest, etc. But with one big different, AutoPlay can automate Unreal Engine, Unity applications using Selenium.

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
 - 
