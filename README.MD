# Ticwatch E Dark Overlay

This overlay is used to apply the default WearOS dark theme to the Ticwatch E.

## How to install this overlay
1: Download overlay package in releases folder.
2: Connect usb cable to PC and enable ADB Debugging.
3: Run these adb commands
`adb install <overlay location>` 
`adb shell cmd overlay enable --user 0 com.makorn645.darkoverlay`
`adb shell reboot`
4: The device will reboot once and the overlay will be applied.
Notes: This is not persistent so if you happen to reset your watch the overlay will be removed.

## How to uninstall this overlay
1: Navigate to `settings > Apps Notifications > App Info > com.makorn645.darkoverlay > uninstall`
2: Reboot device.

## Screens
![Quick Settings](/images/1.png)
![Settings_about](/images/2.png)
![App drawer](/images/3.png)
![Notifications](/images/4.png)
