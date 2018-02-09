# CaptureReplayTesting

Capture/replay testing is an intuitive form of software testing that is in vogue in the areas of web development and mobile development. It is a relatively old form of testing that originally comes from the realm of embedded software. There it had the goal of allowing to test embedded software in realistic circumstances, albeit not on the embedded device itself (because the processing power of the embedded device was not sufficiently capable for example).

Modern capture/replay testing is all about functional testing, often at the level of the Graphical User Interface. Known tools in the area are Selenium IDE (web), Robotium (Android) and Appium (iOS). The idea of the aforementioned tools is twofold. 

1. It allows to easily script a test at the user interface level, i.e., fill in this value in field X and then press button "OK.
2. It even allows to automate step 1, by recording user actions, thus generating the script, that can be replayed over and over (hence the name capture/replay).

This assignment is about exactly this. The explanation below will be about Robotium, but if you feel adventurous, you can obviously also try to do this for Appium or Selenium IDE. 

The minimal steps that you will need to take are:
1. Install Android Studio (see: https://developer.android.com/studio/index.html)
2. Download the Robotium example package for Android Studio (see: https://github.com/RobotiumTech/robotium/wiki/Downloads)
3. Unzip the example package and import the project into Android Studio.
4. In Android Studio define a virtual device and activate it (Android Studio --> Tools --> Android --> AVD Manager)
5. In the example project, select the class NotePadTest (in package com.example.android.notepad). Right click it and run it. The scripted tests are now running.
