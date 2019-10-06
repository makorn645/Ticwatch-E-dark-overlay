# Ticwatch E Theme Overlays

This overlay is used to apply WearOS dark theme with custom colors to the Ticwatch E.

## How to install this overlay

1: Download overlay package in releases folder.

2: Connect device to PC and enable USB ADB Debugging.

3: Run these adb commands

`adb install <color>.apk` 

`adb shell cmd overlay enable --user 0 com.makorn645.theme.<color>`

`adb shell reboot`

## How to uninstall this overlay

1: Connect device to PC and enable USB ADB Debugging.

2: Run these adb commands

`adb shell cmd overlay disable --user 0 com.makorn645.theme.<color>`

`adb uninstall com.makorn645.theme.<color>`

## Screens
![Quick Settings](/images/1.png)
![Settings_about](/images/2.png)
![App drawer](/images/3.png)
![Notifications](/images/4.png)
