# AirPort-App-Launcher
A launcher for Air Port Utility 5.6 on Mavericks and Yosemite

As you might know, the Apple AirPort Utility 5.6 cannot be run on Mavericks or Yosemite. There are few other options out there, but they require to override OSX default security mechanisms.
This could pose a threat to your computer, since you cannot verify what those application are doing (they are probably ok, but better be safe than sorry).

This is why I create this simple application which consists in a single bash script, that does nothing else than invoking the Apple AirPort Utility by first injecting the correct version of the 802.11 library.

Nothing more.

## Prerequisite

In order to run the application you have to have an original copy of the AirPort Utility 5.6 and of the 802.11 framework library.
You can look them up on Google, or if you want to be really safe, you should obtain them from a TimeMachine backup, or from a Mac with a compatible OS version.

## How To Run 

Download the launcher and copy both the original Airport Utility and the 802.11 library in the app Contents folder.
